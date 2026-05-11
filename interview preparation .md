Interview : 

Navigator: Flutter-এ এক screen থেকে অন্য screen-এ যাওয়ার জন্য Navigator use করা হয়। এটি মূলত একটি Stack logic-এ কাজ করে (Push/Pop)।

Stack Real-life Implementation: App-এর undo functionality, browser back button, অথবা screen navigation-এ Stack use হয়।

Array vs Linked List: Array-তে data সিরিয়ালি থাকে এবং index দিয়ে access করা যায়। Linked List-এ প্রতিটি data (node) তার পরের data-র address hold করে।

OOP (Object Oriented Programming): এটি একটি programming paradigm যা Class এবং Object-এর ওপর ভিত্তি করে কাজ করে।

Service Locator: এটি একটি design pattern (যেমন: get_it) যা dependency-গুলোকে এক জায়গায় register করে রাখে যাতে পরে যেকোনো জায়গা থেকে access করা যায়।

Dependency Injection: বাইরে থেকে কোনো class-এর dependency pass করাকে Injection বলে। এটি code-কে testable এবং decoupled করে।

Unit Test: Code-এর ক্ষুদ্রতম অংশ (যেমন একটা function) ঠিকমতো কাজ করছে কিনা তা check করাই হলো Unit Test।

Singleton Pattern: পুরো app-এ কোনো class-এর যখন কেবল একটিমাত্র instance বা object থাকে, তাকে Singleton বলে।

OOP Connections (Inheritance, Interface, Implementation)

Inheritance: বাবা থেকে ছেলে যেভাবে বৈশিষ্ট্য পায় (Parent class থেকে Child class property পায়)।

Interface/Implementation: এটি একটি contract-এর মতো। Interface বলে দেয় "কি করতে হবে" (what to do), আর Implementation বলে দেয় "কিভাবে করতে হবে" (how to do)।

Flutter Framework Internals

State Management: App-এর data change হলে UI-তে তার প্রতিফলন ঘটানোর প্রক্রিয়া। যেমন: Provider, Riverpod, Bloc.

Inherited Widget: এটি widget tree-র একদম নিচ পর্যন্ত data pass করার একটি efficient মাধ্যম।

BuildContext: Widget tree-তে একটি widget-এর location বা ঠিকানা হলো BuildContext।

Trees:

Widget Tree: আমরা কোডে যা লিখি (Configuration)।

Element Tree: Widget এবং Render object-এর মধ্যে bridge হিসেবে কাজ করে (Lifecycle controller)।

Render Tree: Screen-এ পিক্সেলগুলো কিভাবে আঁকা হবে তা নিয়ন্ত্রণ করে (Layout & Painting)।

Async & Reactive Programming:

Stream/Reactive: এটি একটি পাইপের মতো যেখান থেকে অনবরত data আসতে থাকে। Data change হওয়া মাত্রই UI update হয়।

Asynchronous: কোনো বড় কাজ (যেমন API call) করার সময় app-কে freeze না করে background-এ কাজ চালানো।

Event Loop: এটি একটি লুপ যা সবসময় চেক করে কোনো কাজ (Event) পেন্ডিং আছে কিনা এবং সিরিয়ালি তা execute করে।

Advanced Scenarios:

Dynamic Link: এটি এমন এক link যা click করলে সরাসরি app-এর নির্দিষ্ট page-এ নিয়ে যায়। App না থাকলে browser-এ redirect করে।

Query Optimization: Indexing use করা, অপ্রয়োজনীয় SELECT * এড়িয়ে চলা এবং join query-তে সর্তক থাকা।

sql raw senario likho ekta complex senario tahkbey ..
SQL Raw Scenario: মনে করেন ১ মিলিয়ন user-এর মধ্য থেকে যারা গত ১ মাসে $500-র বেশি কেনাকাটা করেছে এবং নির্দিষ্ট সিটিতে থাকে, তাদের list বের করা। এটি একটি complex join এবং aggregation-এর উদাহরণ।

Missing Plugin Management (doren amon ekta app vanaccen ..jeitar plugin nai .. pacakage nai .. apni ata kibabaey manage korben ? )  
সর্বোচ্চ চেষ্টা করবো resource খুঁজে বের করার। Senior-দের help নিবো। না হয় R&D (Research and Development) টাইপ কিছু করবো। Project Manager থেকে time নিবো। Maybe এইভাবে এগোনো যায়।


freelance codecenon ki kaz korcen ??

2-3 ta object acey dekan to ara kivavey connected or kivavaey kaz kore ?? 

Ui design kortey dibey

Last project e ki ki use korcen ?? 
