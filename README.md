In this document, you can find a list of ideas that are proposed by Scala Center for Google Summer of Code 2023.

If you are interested in any idea or would like to propose your own, please reach out to your potential mentor. You can also reach Scala Center at [scala.center(at)epfl.ch](mailto:scala.center@epfl.ch).

# Project Ideas

## Doodle Canvas

|Title                   |Doodle Canvas|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle/|
|Brief Description       |Doodle is a library for 2D graphics. It has good support for producing structured images, but sometimes you just want to blast pixels onto a screen. This project aims to add support for that.|
|Expected Outcome        |A Doodle algebra or algebras that support writing pixels, and probably lines, circles, and other shapes, directly onto the screen.|
|Prerequisites           |Basic Scala knowledge|
|Ideal Prerequisites     |Some understanding on tagless final style.|
|Expected Difficulty     |Easy – straightforward task, path for execution visible right now, very little uncertainty|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
|Co-mentor               | |


## Doodle UI

|Title                   |Doodle UI|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle-explore/|
|Brief Description       |Develop a basic cross-platform UI toolkit. In Doodle Explore we have the basics of a cross-platform UI toolkit. The aim of this project is to extract that toolkit and develop it into a more widely usable tool. Developing a toolkit can be a lot of work. To keep the scope to a reasonable level we're not expecting a high degree of customizability from this toolkit: it's use case is quickly creating a workable UI and other libraries should be used in a lot of custom interactivity is required.|
|Expected Outcome        |Code to implement the library and documentation for the library.|
|Prerequisites           |Good understanding of Scala.|
|Ideal Prerequisites     |Some understanding of Scala 3, reactive programming, UI toolkits, and tagless final.|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Long project – 350 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com))|
|Co-mentor               | |


## Doodle Bitmap Convolutions

|Title                   |Doodle Bitmap Convolutions|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle/issues/94|
|Brief Description       |Add support for bitmap convolutions to Doodle. The link has more, including a Github project laying out the steps.|
|Expected Outcome        |Working code and documentation.|
|Prerequisites           |Some Scala knowledge.|
|Ideal Prerequisites     |Basic knowledge of bitmap convolutions, some understanding of tagless final.|
|Expected Difficulty     |Easy – straightforward task, path for execution visible right now, very little uncertainty|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com))|
|Co-mentor               | |


## Quote pattern matching enhancements

|Title                   |Quote pattern matching enhancements|
|------------------------|-|
|Link to Project         |https://github.com/lampepfl/dotty|
|Brief Description       |In Scala 3's metaprogramming, quoted code allows the type-safe creation of code fragments. Similarly, quoted patterns provide a type-safe way to decompose code fragments. This feature was formalized in "Multi-stage Programming with Generative and Analytical Macros" and then extended with polymorphism in "Scalable Metaprogramming in Scala 3 - Chapter 4". The formalization went beyond what the implementation supported, showing potential for improvement. Specifically, we want to generalize HOAS patterns.|
|Expected Outcome        |Add missing functionality to the quote pattern matching that is available in from the formalization. Or find and understand other limitations of the language that would be required to support those enhancements. There will probably be a mix between the two.|
|Prerequisites           |Experience with compilers, good Scala language knowledge, and basic type theory knowledge.|
|Ideal Prerequisites     |Experience with the dotty compiler|
|Expected Difficulty     |Hard – involves high degree of uncertainty even for a highly experienced person|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Nicolas Stucki (GitHub: [@nicolasstucki](https://github.com/nicolasstucki), Email: [nicolas.stucki@epfl.ch](mailto:nicolas.stucki@epfl.ch))|
|Co-mentor               | |


## dotty-cps-async

|Title                   |dotty-cps-async|
|------------------------|-|
|Link to Project         |https://github.com/rssh/dotty-cps-async|
|Brief Description       |Participate in extending of dotty-cps-async by compiler plugin,  which appply CPS transformation to context function with direct result type, transforming it into monadic style after typing.|
|Expected Outcome        |Compiler plugin, which will allow using  direct style programming without coloring.|
|Prerequisites           |basic knowledge of scala and functional programming|
|Ideal Prerequisites     |+ familiarity with compiler internals.|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Long project – 350 hours|
|Mentor                  |Ruslan Shevchenko (GitHub: [@rssh](https://github.com/rssh), Email: [ruslan@shevchenko.kiev.ua](mailto:ruslan@shevchenko.kiev.ua))|
|Co-mentor               | |


## Infrastructure for compiler plugin testing for dotty-cps-async

|Title                   |Infrastructure for compiler plugin testing for dotty-cps-async|
|------------------------|-|
|Link to Project         |https://github.com/rssh/dotty-cps-async|
|Brief Description       |Develop and sbt plugin,  suited for testing of dotty-cps-compiler plugin, which will provide an environment for creating a virtual small sbt 'test project' for each directory in list with separate set of files to compile and test|
|Expected Outcome        |sbt plugin, which will allows easly create test-cases.  Will be suitable to testing not only dotty-cps-async but  potential other compiler plugins.|
|Prerequisites           |basic knowledge of scala.|
|Ideal Prerequisites     |+ familiarity with sbt internals.|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Ruslan Shevchenko (GitHub: [@rssh](https://github.com/rssh), Email: [ruslan@shevchenko.kiev.ua](mailto:ruslan@shevchenko.kiev.ua))|
|Co-mentor               | |


## io_uring backend for Cats Effect + FS2 JVM

| Title                    | io_uring backend for Cats Effect + FS2 JVM                   |
| ------------------------ | ------------------------------------------------------------ |
| Link to Project          | https://github.com/typelevel/cats-effect                     |
| Brief Description        | Cats Effect is a high-performance, multi-threaded runtime for asynchronous programming in Scala. Its latest development is the capability to do (network) I/O "polling" directly from within the runtime, instead of delegating to an external I/O framework.<br><br>io_uring is a Linux API for making efficient I/O system calls.<br><br>The goals of this project are to:<br>1. develop an io_uring polling system for Cats Effect JVM, and<br>2. use it to implement the socket APIs in FS2.<br>FS2 is a streaming I/O library that powers the Ember HTTP server/client and Skunk PostgreSQL client.<br><br>Prior art includes Netty (which demonstrates how to use io_uring from the JVM) and an existing proof-of-concept that targets single-threaded Scala Native (which demonstrates how to integrate io_uring with Cats Effect / FS2). This project can find inspiration in both :)<br><br>Further reading: https://github.com/typelevel/cats-effect/discussions/3070 |
| Expected Outcome         | An io_uring polling system for Cats Effect and socket implementation for FS2 |
| Prerequisites            | Scala, ability to read Java and C                            |
| Ideal Prerequisites      | Experience with JNI, Java, C, functional programming, Typelevel libraries |
| Expected Difficulty      | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
| Expected Time Commitment | Long project – 350 hours                                     |
| Mentor                   | Arman Bilge (GitHub: [@armanbilge](https://github.com/armanbilge), Email: [armanbilge@gmail.com](mailto:armanbilge@gmail.com))     |
| Co-mentor                | Daniel Spiewak [@djspiewak](https://github.com/djspiewak)    |


## http4s Ember WebSocket client

|Title                   |http4s Ember WebSocket client|
|------------------------|-|
|Link to Project         |https://http4s.org/|
|Brief Description       |http4s Ember is a pure Scala, pure FP HTTP server/client that cross-compiles to Scala JVM, Scala.js, and Scala Native.<br><br>WebSocket is a widely-implemented network protocol, commonly deployed for real-time, two-way communication, for example between a browser and server.<br><br>Ember already implements a WebSocket server. The goal of this project is to implement a WebSocket client for Ember. This will unblock several use-cases, such as running GraphQL Subscriptions or executing commands in a Kubernetes Pod.|
|Expected Outcome        |A WebSocket client for http4s Ember|
|Prerequisites           |Scala, interest in FP and network protocols|
|Ideal Prerequisites     |Experience with Typelevel libraries|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Arman Bilge (GitHub: [@armanbilge](https://github.com/armanbilge), Email: [armanbilge@gmail.com](mailto:armanbilge@gmail.com))|
|Co-mentor               |Christopher Davenport [@ChristopherDavenport](https://github.com/ChristopherDavenport) |

## Pure Scala Open Telemetry implementation

|Title                   |Pure Scala Open Telemetry implementation|
|------------------------|-|
|Link to Project         |https://github.com/typelevel/otel4s|
|Brief Description       |Open Telemetry is an open standard for observability: instrumenting deployed applications and collecting metrics, traces, and logs. The otel4s library defines an idiomatic, FP Scala interface for Open Telemetry clients. However, so far the only implementation is a wrapper around the Open Telemetry Java SDK.<br><br>The goal of this project is to develop a pure Scala Open Telemetry backend that implements the otel4s API interface and speaks the Open Telemetry protocol. This will make it possible to use Open Telemetry in a Scala application while taking full advantage of the high-performance runtimes and cross-platform (Scala.js, Scala Native) targets available in the Scala ecosystem.|
|Expected Outcome        |A pure Scala backend for the otel4s library|
|Prerequisites           |Scala, interest in observability and protocols|
|Ideal Prerequisites     |Experience with Typelevel libraries|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Long project – 350 hours|
|Mentor                  |Arman Bilge (GitHub: [@armanbilge](https://github.com/armanbilge), Email: [armanbilge@gmail.com](mailto:armanbilge@gmail.com))|
|Co-mentor               |Maksym Ochenashko [@iRevive](https://github.com/iRevive) |

## Scala webapp template

|Title                   |Scala webapp template|
|------------------------|-|
|Link to Project         |https://github.com/wiringbits/scala-webapp-template/|
|Brief Description       |Full project description: https://github.com/wiringbits/scala-webapp-template/issues/307<br><br>The Scala Webapp Template is a pragmatic skeleton to build web applications in Scala/Scala.js, including user registration, login, admin portal, and, deployments.<br><br>This project aims to make it easy for non-Scala developers to get into the Scala ecosystem.<br><br>I have discuss with many other devs from the Scala community who agreed that a project like this is a must to attract more people into Scala.<br><br>So far, we have got an adopter coming from php who found the project at Google (see https://twitter.com/NickBelyavski/status/1597755699395952640).|
|Expected Outcome        |I'm hoping that we can improve the project to get far more usable to devs willing to use it.<br><br>I'd start by documenting everything available, and, creating a roadmap for future improvements.|
|Prerequisites           |While Scala knowledge is ideal, we can also benefit from having help from people without experience in Scala, this way, the docs should get more approachable.<br><br>Experience with full stack web applications is ideal.|
|Ideal Prerequisites     |- Intermediate+ Scala experience<br>- Interest in people adopting Scala<br>- Wide experience on Web Applications using different programming languages/frameworks<br>- Scala.js experience<br>- Experience contributing to libraries/frameworks|
|Expected Difficulty     |Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it|
|Expected Time Commitment|Short project – 175 hours|
|Mentor                  |Alexis Hernandez (GitHub: [@AlexITC](https://github.com/AlexITC), Email: [alexis@wiringbits.net](mailto:alexis@wiringbits.net))|
|Co-mentor               | |




