_Programming is the writing contains semetic consistency about the domain story_

- 👋 Hi, I’m @N0FreeLunch
- 👀 I’m interested in programming language theory, concurrency programming, beautiful code, semantic abstract
- 🌱 I’m currently learning Laravel TDD/DDD, DDD with function composition (JS), ReactJS, Golang, Agile software development
- ⭐ I’m a specialist to deal the complexity of software

---

## Main Skill

1. JS/TS : Regexp, DOM manipulation, FP(RamdaJS), OOP, Prototype knowledge, Webpack, event-loop/callback-queue knowledge, blocking/non-blocking, sync/async, React(Mui)
2. PHP : PHP8+, OOP, Language RFC/Reference Analysis
3. Laravel : IOC/DI, RESTful API, EloquentORM, Collection, Batch(Scheduler, Queue, Job), Middleware, Validation, Page Session, API session(Sanctum)/JWT/token Authentication, Event/Listner, Schema/Data Migration, DDD(Layered Architecture, Bounded Context, Ubiquitous Language, Specification Pattern), Pest(Test Framework)
4. AWS : EC2(ALB, Spot Instance, Auto scale), Lambda, RDS, cloudfront, cloudwatch, S3, Athena, Route53, SES/SNS, API Gateway, IAM, Elastic Cache, ECS(EC2, cloudformation), Secret Manager
5. Database : MySQL, Redis, SQLite, PostgreSQL, ERDiagram
6. Web knowledge : HTTP protocol standard, nginx(php server, proxy server, static contents server), SSL certification (let's encrypt), Web security (XSS, SQL Injection, Code/File Injection, CSRF, TLS ...), Secure coding
7. CSS : SASS, Responsive web
8. OS Environment : Linux(AMI, Ubuntu, CentOS, Debian, Alpine), OSX, WSL, Shell Script (Bash)
9. Docker : YAML, docker compose

---

### Experience (student)

- Java, C
- capstone : Transmitting sensor data aduino necklace to smartphone in kindergarten service (Cordova mobile application processes a lot of data from BLE using JS event loop)

---

## Career

- School of computer information department (~ 2018.03)
- ADtech corporation 2018.06 ~ 2021.09
- PinTech corporation 2021.10 ~

---

## Contribution

### Laravel

[official reference document translator 8.x 9.x 10.x](https://github.com/laravelkr/docs/pulls?q=is%3Apr+author%3AN0FreeLunch)

---

## Work (Pin Tech)

#### House rent payment system for real estate company

2022 (Major task)

- Docker setting (To define auto webpack building and composer installing process with considering security and maintanace when deploy build system) (shell script, linux user and file/foler permission, composer, NVM, NodeJS, webpack)
- HTTP request/response logging system (Laravel middleware, Event/Listener, singleton pattern)
- Refactored code MC to MVC architecture structure using laravel-admin library (Layer separation, EloquentORM, interface, abstract class)
- Integrated a user payment status decision logic was separated and improved status logic with more complexity (Eloquent ORM, drawing flow chart, defining binded context)
- Made a batch process that makes zengin file used on Japan interbank payments system. (Add docker queue container, S3, MinIO, Laravel queue/scheduler, eloquentORM chunk, php file handler)
- Version upgrade overcoming the limitation of libraries (webpack:laravel-mix, sass, VanilaJS, Bootstrap, Jquery)
- Improved code to verify PCIDSS(Payment Card Industry Data Security Standard) compliance. (first verification passed)
- Made a module that controls the changes in complexity domain logic for recurring billing start condition.
- Refactored batch processes uses table/record lock to queue/job base code.
- Refactored mud-ball code to groupifided well defined domain context code and testable code.
- Refactored query builder base code to eloquentORM with the concept of specification pattern.
- Refactored incorrect migration data, incorrect seedings, incorrect rollback processes to the right way.
- PHP and Laravel version upgrade. (Laravel 5.8 to 8.x, php 7.3 to 8.1)

2023 (Major task)

- Made batch cancellation APIs and artisan commands. (artisan console, queue, job)
- Improved a batch process create Invoices and Reports using queue/job/triggered by an administrator instead of being solely batched by the scheduler. (job, queue)
- Added batch execution API for QA to test batches. (middleware that resctirct production environment, artisan console)
- Improved bulk change feature for user contract and payment status.
- Refactored the accounting file generation batch. (query builder to eloquent)
- Enhanced account payment system to use saved information when a time file is uploaded.
- Project code quality management. Production server deploy schedule management.
- Project design and task assignment considering path dependence and nudge in social psychology.
- Adoption of static analysis tools. (larastan)
- Refactored card payment system code. Adding unit test. Improving retry payment feature. (Payment API mocking, pest, writting test scenario, customize type that restrict date string, value object)
- Improved code to verify PCIDSS compliance. (customized validation)
- NodeJS and JS pacakge version upgrade (Node16 to 20 LTS)
- Improved invoices and reports for changing Japan invoice policy. (Laravel blade, Code refactor using the parial concept)
- Added parent companies management system that enables to manage child companies. (customizing library session middleware, singleton pattern)
- Created a smart login feature that allows parent accounts to login to child accounts in multi session login environment. (customizing middleware, CSRF, dealing complex M:N relation matching logic, Api Token Login, JS OOP)

2024 (Major task)

- Created a logging feature that record deprecated syntax. (laravel logging/job, monolog libray)
- Added feature test environment. (pest, pgsql/sqlite(inmemory), model factory, fakerPHP)
- Refactored the big troubled email sending logic to encapsulate domain constraints. (TDD)
- Added end-user entry form customize feature
    - Created a management page to customize 100 items.
    - Created form pages ((env: pnpm, Vite, SWC, TS, React) Zustand, SWR, session storage, react-router, Mui, Feature-Sliced Design)
    - Created form pages API with considering external API (TDD, feature test, API-collection/resources, CORS, Two-way encryption)
    - Added new payment status decision flow. (data migration)
    - Improved initial cost issuance logic to match new payment status flow.
    - Refactored the payment method register logic (Divide a lengthy logic into conceptual parts.)
    - Added automatic region input using zip code. (Mui, external API, DB cache)
- Improved the logging of the bank account registration API. (Feature test, data migration)
- Changed the approval number matching pattern from one type to two types. (changed the payemnt batch logic.)

2025 (Major task)

- Added feature test to payment status decision logic. (Pest(Test framework))
- Added 2FA with using Google Authenticator. (laravel blade component, fortify, login lock/unlock, initialize 2FA)

## Work (AD tech)

### SSP (supply side platform) developer, challenging DSP (demand side platform) part

#### AD server development

- Script for showing advertise to media web site from AD network. Being published in media site web page advertise area. (Vanilla JS, webpack(Code Obfuscation), DOM manipulate)
- Crawling advertise sending report and monthly bill data from AD network web site. (php, nodejs, login with hacking login cookie saving logic)
- Maintenance web service that site owner request advertise script. (Laravel)

#### AD network development

- Admin service and user client service development/management/maintenance (Laravel, vue2, vue-router)
- API server development/management/maintenance (Gin, Go, EC2)
- Batch server management/maintenance (AWS Lambda)
- Serving server management/maintenance (Go, Gin, EC2, auto scale, spot instance)

### The Others

#### Video service

- Video service web site management/maintenance (30\~40TB\/month traffic video contents server, 30\~50GB\/month web page traffic server with laravel)

#### E-Commercial site web page

- Listing and showing similar clothes with clothes picture using AI API in EC site. (vanilla JS, webpack, SASS, FP, DOM manipulate, IE compatibility, CoreJS, Babel-polyfill)

#### Web system for people with disabilities

- In-house web system (Domain group and layer design, EC2, SASS, laravel Santurm (session authenticate protocol with ajax), Query result caching, React)

#### Homepage

- Static web site A (Laravel, AWS EC2 lambda SES, SASS), B (React, Nginx, Google App script)

#### Infrastructure

- OS Migration : AMI -> AMI2 (with AWS Graviton)
- Making recoverable servers with saving built server to EBS
- Making server application building process with EC2 instance user data script
- Applying SSL to outdated server with reverse proxy

---

## I’m currently learning

### Javascript

- To learn multi paradigm language coding style
- [RamdaJS](https://github.com/N0FreeLunch/Javascript-Development-Note/tree/main/FuntionalProgramming/RamdaJS)

### ReactJS

- To understand user inteface with reactive architecture (UI = view(state or store))
- [practice](https://github.com/N0FreeLunch/react-study)

### php, laravel

- To learn OOP main language.
- Basic php programming practice without web framework
- [DDD](https://github.com/N0FreeLunch/Laravel-DDD-Note)
- [PHP](https://github.com/N0FreeLunch/PHP_Laravel-Development-Note/tree/main/PHP)
- [laravel](https://github.com/N0FreeLunch/laravel-practice)

### golang

- To learn concurrency programming with go routine and channel
- To make superfast micro service, short latency response server, many request processing server
- To learn the reason of Golang design has different design philosophy comparing with other programming languages
- [golang practice](https://github.com/N0FreeLunch/go-basic)

---

## lay the ground work (go back to basics)

- [bash shell](https://github.com/N0FreeLunch/shellscript-practice/tree/main/practice)
- [Nginx](https://github.com/N0FreeLunch/Nginx-study/tree/main/study)
- [SQL](https://github.com/N0FreeLunch/sql-practice)
- [YAML](https://github.com/N0FreeLunch/yaml)

---

## Interests

- [UI\/UX-study](https://github.com/N0FreeLunch/UIUX-study/tree/main/essay)
- Python (Django [1](https://github.com/N0FreeLunch/django_book) [2](https://github.com/N0FreeLunch/RestaurantShare-with-Django) [3](https://github.com/N0FreeLunch/django-excel) [4](https://github.com/N0FreeLunch/django-board) )
- [Ruby\/Rails](https://github.com/N0FreeLunch/ruby-rails-study)
- [Java](https://github.com/N0FreeLunch/JAVA-study)
- FP lang: [Elm](https://github.com/N0FreeLunch/elm-basic), [Scala](https://github.com/N0FreeLunch/scala-start), [Haskell](https://github.com/N0FreeLunch/haskel-practice)

---

## Future plans

- Elm : To learn functional coding architecture, understand redux principle
- Elixir : To improve pure functional programming skill. To understand actor model
- Scala : To understanding integration funtional programming and object oriented programming
- C++ : To learn avida(evolution simulator), automata theory, formal language
- Rust : To understand concurrency programming without garbage collector
- Python : To learn mathematics using programming, bioinformation, semantic information theory with machine learning, Alphafold
- Haskell : To learn mathematical logic and understand the equivalence of Turing machines and lambda calculus
- Verilog : To make a system with boolean algebra
