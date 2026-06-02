## ## MVVM (Restaurant Example)

## View (Customer/UI)

-Customer যেমন খাবার দেখে এবং Order দেয়, View-ও তেমনি Data দেখায় এবং User Input নেয়।

## ViewModel / State Holder (Waiter)

-Waiter Customer-এর Order নেয় এবং Kitchen-এ পৌঁছে দেয়।
-Kitchen থেকে খাবার এনে Customer-কে দেয়।
-ViewModel ঠিক একইভাবে View এবং Data Layer-এর মধ্যে যোগাযোগ করে।
-এছাড়া Loading State, Error State, Product List, Cart Items ইত্যাদি State Manage করে।

## Model (Food/Data)

-Restaurant-এ খাবার যেমন মূল Data,  Model-ও তেমনি Data Structure।
-API Response, Database Data, User Data ইত্যাদি Model-এর মাধ্যমে Represent করা হয়।

## Business Logic (Restaurant Rules)

-Restaurant-এর Discount Rule, VAT Rule, Offer Rule, Delivery Rule যেমন Restaurant-এর Business Rule,
-তেমনি Application-এর Discount Calculation, Coupon Validation, Shipping Charge Calculation, Tax Calculation ইত্যাদি Business Logic।

## Repository (Food Manager)

Repository-কে Kitchen বললে পুরোপুরি ঠিক হয় না। Kitchen আসলে API Server / Database / Firebase হতে পারে।

Repository-এর আসল কাজ হলো Data কোথা থেকে আসবে সেটা সিদ্ধান্ত নেওয়া।
-Data API থেকে আনবে?
-Cache থেকে আনবে?
-Local Database থেকে আনবে?
-Firebase থেকে আনবে?

ViewModel শুধু বলে:"আমাকে Products দাও"

Repository বলে: "ঠিক আছে, আমি যেখান থেকে প্রয়োজন Data এনে দিচ্ছি।"

Repository Pattern-এর সুবিধা:
আজ Data API থেকে আসছে। আগামীকাল Client বলল:"Firebase ব্যবহার করবো" তখন শুধুমাত্র Repository-এর ভিতরের Implementation পরিবর্তন করতে হবে।

ViewModel এবং UI-এর কোনো পরিবর্তন লাগবে না।

## Data Flow:

View (Customer/UI)

↓
ViewModel / State Holder (Waiter)

↓
Repository (Data Manager)

↓
API / Firebase / Database / Cache

↓
Model (Food/Data)

↓
ViewModel

↓
View
