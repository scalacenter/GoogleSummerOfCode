In this document, you can find a list of ideas that are proposed by the Scala Organisation for [Google Summer of Code 2025](https://summerofcode.withgoogle.com/).

## Application

If you are interested in becoming a contributor on any idea, please reach out to your potential mentor using their email address specified with the project. You can also reach Scala Center at [scala-gsoc(at)epfl.ch](mailto:scala-gsoc@epfl.ch).

If you would like to be a mentor and propose your own idea, please submit a PR editing this file (e.g. see [2024's projects](Past%20years%20ideas/2024.md)), adding your project to the list, following the format of other projects below.

## Rules

You can read the full rules of the program at the following links: [Rules](https://summerofcode.withgoogle.com/rules), [Terms and Conditions](https://summerofcode.withgoogle.com/terms/contributor), [Help](https://summerofcode.withgoogle.com/help).

And here are the requirements for the potential contributor's proposal: [Writing a proposal](https://google.github.io/gsocguides/student/writing-a-proposal).

However, here are some rules that we'd like to emphasize since they are not visible enough at the above links:

- The program is geared towards beginners first and foremost. It is intended to **be a learning experience** for people at the very beginning of their careers. It is also intended to **give an opportunity** to people who would otherwise not have one. It is NOT a freelance job. Therefore, when making an acceptance decision on a potential contributor, we will prioritize disadvantaged backgrounds and contributors at the very beginning of their careers.
- **IMPORTANT - EPFL Students**: Please note that, according to GSoC rules, there are restrictions on accepting students from an organization's host university. For Scala Center, the host university is EPFL. We can only accept up to 1 student from EPFL, so please take it into account if you're studying at EPFL and consider applying.

## Project Ideas

### Doodle Bitmap Convolutions

| Title                    | Doodle Bitmap Convolutions                                                                                              |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/doodle/issues/94                                                                       |
| Brief Description        | Add support for bitmap convolutions to Doodle. The link has more, including a Github project laying out the steps.      |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Some Scala knowledge.                                                                                                   |
| Ideal Prerequisites      | Basic knowledge of bitmap convolutions, some understanding of tagless final.                                            |
| Expected Difficulty      | Easy – straightforward task, path for execution visible right now, very little uncertainty                              |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Doodle Skia Backend

| Title                    | Doodle Skia Backend                                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/doodle/issues/175                                                                      |
| Brief Description        | Add a Skia backend for Doodle, using the Skiaj bindings.                                                                |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Some Scala knowledge.                                                                                                   |
| Ideal Prerequisites      | Some understanding of type classes or tagless final.                                                                    |
| Expected Difficulty      | Easy – straightforward task, path for execution visible right now, very little uncertainty                              |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Krop Template Engine

| Title                    | Krop Template Engine                                                                                                    |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/krop/issues/14                                                                         |
| Brief Description        | Create an HTML template engine for the Krop web framework.                                                              |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Intermediate Scala knowledge and basic HTML knowledge.                                                                  |
| Ideal Prerequisites      | An understanding of parsing.                                                                                            |
| Expected Difficulty      | Medium – some design decisions need to be made and the implementation is not straightforward.                           |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Business4s Projects

| Title                    | Workflows4s Web UI                                                                                                                                                                                 |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | https://github.com/business4s/workflows4s                                                                                                                                                          |
| Brief Description        | Implement web user interface for Workflows4s. Design the API and implement both server and web side using scala and scala.js. See https://github.com/business4s/workflows4s/issues/19 for details. |
| Expected Outcome         | Proof of concept of the UI that can present progress of a workflow instance.                                                                                                                       |
| Prerequisites            | Basic scala skills, basic frontend skills, basic knowledge of HTTP APIs (e.g. REST).                                                                                                               |
| Expected Difficulty      | Medium                                                                                                                                                                                             |
| Expected Time Commitment | Large project - 350 hours                                                                                                                                                                          |
| Spoken Language          | English                                                                                                                                                                                            |
| Mentor                   | Voytek Pituła (GitHub: [@Krever](https://github.com/Krever), Email: [w.pitula@gmail.com](mailto:w.pitula@gmail.com))                                                                               |
| Co-mentor                | Dave Smith (Github: [@davesmith00000](https://github.com/davesmith00000), Email: [david.smith@purplekingdomgames.com](mailto:david.smith@purplekingdomgames.com))                                  |

| Title                    | ChatOps4s Prototype                                                                                                                                       |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | To be created under https://github.com/business4s                                                                                                         |
| Brief Description        | Prototype of library/toolkit allowing to easily send messages and receive input from chat platforms (e.g. Slack)                                          |
| Expected Outcome         | Prototype that allows getting information in and out Slack with as little effort as possible. Research on how hard will it be to support other platforms. |
| Prerequisites            | Ability to research and consume external APIs. Basic exposure to some chat platform (Slack, Discord, MS Teams)                                            |
| Expected Difficulty      | Medium                                                                                                                                                    |
| Expected Time Commitment | Medium project - 175 hours                                                                                                                                |
| Spoken Language          | English                                                                                                                                                   |
| Mentor                   | Voytek Pituła (GitHub: [@Krever](https://github.com/Krever), Email: [w.pitula@gmail.com](mailto:w.pitula@gmail.com))                                      |
| Co-mentor                | -                                                                                                                                                         |

| Title                    | ChatOps4s Prototype - Discord Backend                                                                                                                                       |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | To be created under https://github.com/business4s                                                                                                         |
| Brief Description        | Extension of the library to handle Discord                                                                                                                |
| Expected Outcome         | Integration with Discord that allows to get information in and out of it through ChatOps4s api.                                                           |
| Prerequisites            | Ability to research and consume external APIs. Basic exposure to some chat platform (Slack, Discord, MS Teams)                                            |
| Expected Difficulty      | Medium                                                                                                                                                    |
| Expected Time Commitment | Medium project - 175 hours                                                                                                                                |
| Spoken Language          | English                                                                                                                                                   |
| Mentor                   | Voytek Pituła (GitHub: [@Krever](https://github.com/Krever), Email: [w.pitula@gmail.com](mailto:w.pitula@gmail.com))                                      |
| Co-mentor                | -         

| Title                    | ChatOps4s Prototype - MS Teams Backend                                                                                                                                       |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | To be created under https://github.com/business4s                                                                                                         |
| Brief Description        | Extension of the library to handle MS Teams                                                                                                               |
| Expected Outcome         | Integration with MS Teams that allows to get information in and out of it through ChatOps4s api.                                                          |
| Prerequisites            | Ability to research and consume external APIs. Basic exposure to some chat platform (Slack, Discord, MS Teams)                                            |
| Expected Difficulty      | Medium                                                                                                                                                    |
| Expected Time Commitment | Medium project - 175 hours                                                                                                                                |
| Spoken Language          | English                                                                                                                                                   |
| Mentor                   | Voytek Pituła (GitHub: [@Krever](https://github.com/Krever), Email: [w.pitula@gmail.com](mailto:w.pitula@gmail.com))                                      |
| Co-mentor                | -                                                                                                                                                         |

| Title                    | DomainDocs4s Exploration                                                                                                                                                              |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | https://github.com/business4s/domainDocs4s                                                                                                                                          |
| Brief Description        | Implement a library that allows to collect metadata and generate domain documentation based on Scala code                                                                                  |
| Expected Outcome         | Ability to collect metadata into reusable format and generate at least a single documentation format (e.g. glossary of terms). Exploration of what other formats could be supported |
| Prerequisites            | Basic Scala skills. Willingness to look into Scala AST. Basic understanding of DDD and general domain-driven mindset.                                                               |
| Expected Difficulty      | Medium                                                                                                                                                                              |
| Expected Time Commitment | Medium project - 175 hours                                                                                                                                                          |
| Spoken Language          | English                                                                                                                                                                             |
| Mentor                   | Voytek Pituła (GitHub: [@Krever](https://github.com/Krever), Email: [w.pitula@gmail.com](mailto:w.pitula@gmail.com))                                                                |
| Co-mentor                | -                                                                                                                                                                                   |

### Play Framework Support in Metals

| Title                    | Play Framework Support in Metals                                                                                              |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/scalameta/metals-feature-requests/issues/50 https://github.com/scalameta/metals-feature-requests/issues/89 |
| Brief Description        | Add support for Play Framework specific files in Metals language server                                                       |
| Expected Outcome         | Working code and documentation.                                                                                               |
| Prerequisites            | Intermediate Scala knowledge and basic HTML knowledge.                                                                        |
| Ideal Prerequisites      | An understanding of parsing and language server protocol.                                                                     |
| Expected Difficulty      | Medium – some design decisions need to be made and the implementation is not straightforward.                                 |
| Expected Time Commitment | Medium project – 175 hours                                                                                                    |
| Mentor                   | Tomasz Godzik (GitHub: [@tgodzik](https://github.com/tgodzik), Email: [tomek.godzik@gmail.com](mailto:tomek.godzik@gmail.com))|
| Co-mentor                |                                                                                                                               |

### Cyfra: Support for basic GPU computations on data streams with fs2 integration

|Title                   |                                   |
|------------------------|------------------------------------------|
|Link to Project         | https://github.com/ComputeNode/cyfra                                     |
|Brief Description       | Cyfra is a GPU runtime and a DSL that makes Scala a viable choice for GPU programming. Goal of the project is to implement support for GPU computations on data streams with focus on usability.  |
|Expected Outcome        | Cyfra should enable developers that do not have background in GPU programming to write a simple data processing pipeline in Cyfra that performs compute on GPU and efficiently manages memory. The pipeline should be interoperable with fs2. |
|Prerequisites           | Some experience with Scala, and interest to learn a bit about GPUs. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Szymon Rodziewicz ([LinkedIn](https://www.linkedin.com/in/szymon-r-04951895/), Github: [szymon-rd](https://github.com/szymon-rd), Email: [szymonrodant@gmail.com](mailto:szymonrodant@gmail.com)) |
|Co-mentor               | - |

### Cyfra: Real-time rendering pipeline

|Title                   |                                   |
|------------------------|------------------------------------------|
|Link to Project         | https://github.com/ComputeNode/cyfra                                     |
|Brief Description       | Cyfra is a GPU runtime and a DSL that makes Scala a viable choice for GPU programming. Goal of the project is to implement a basic real-time Vulkan rendering pipeline.  |
|Expected Outcome        | Cyfra should enable developers to create programs that will render scenes from a basic one-step Vulkan pipeline in real time. It should support rendering to a window, a data stream, and a file. |
|Prerequisites           | No Scala experience is required, but basic experience with GPU programming would be helpful. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Szymon Rodziewicz ([LinkedIn](https://www.linkedin.com/in/szymon-r-04951895/), Github: [szymon-rd](https://github.com/szymon-rd), Email: [szymonrodant@gmail.com](mailto:szymonrodant@gmail.com)) |
|Co-mentor               | - |

### Cyfra: Real time SDF editor

|Title                   |                                   |
|------------------------|------------------------------------------|
|Link to Project         | https://github.com/ComputeNode/cyfra                                     |
|Brief Description       | Cyfra is a GPU runtime and a DSL that makes Scala a viable choice for GPU programming. Goal of the project is to implement a real-time SDF (signed distance fields) editor as a VSCode extension.  |
|Expected Outcome        | Cyfra vscode extension should be tool that would allow its users to render 3D SDF-based scenes and see changes in their code reflected in the output in real time. |
|Prerequisites           | Some experience with Scala or TypeScript, and interest to learn a bit about GPUs, Scala, and VSCode extension development. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Szymon Rodziewicz ([LinkedIn](https://www.linkedin.com/in/szymon-r-04951895/), Github: [szymon-rd](https://github.com/szymon-rd), Email: [szymonrodant@gmail.com](mailto:szymonrodant@gmail.com)) |
|Co-mentor               | - |

### Cyfra: Scala Native MVP

|Title                   |                                   |
|------------------------|------------------------------------------|
|Link to Project         | https://github.com/ComputeNode/cyfra                                     |
|Brief Description       | Cyfra is a GPU runtime and a DSL that makes Scala a viable choice for GPU programming. Goal of the project is to make it run on Scala Native.  |
|Expected Outcome        | Fundamental features of the cyfra library should run on Scala Native and make it possible to build efficient real-time rendering and data processing applications. |
|Prerequisites           | Some experience with Scala, and interest to learn a bit about GPUs. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Szymon Rodziewicz ([LinkedIn](https://www.linkedin.com/in/szymon-r-04951895/), Github: [szymon-rd](https://github.com/szymon-rd), Email: [szymonrodant@gmail.com](mailto:szymonrodant@gmail.com)) |
|Co-mentor               | - |


### Scala Native / Scala.js Projects

| Title                   | Scala Bazel Rules for Scala.js and Scala Native |
|-------------------------|------------------------------------------------|
|Link to Project          | https://github.com/bazelbuild/rules_scala |
|Brief Description        | This project aims to develop Bazel build rules for Scala.js and Scala Native, enabling efficient and reproducible builds for both platforms. The project will provide first-class support for Scala projects within the Bazel ecosystem, improving integration and developer experience. |
|Expected Outcome         | Functional and well-documented Bazel rules that allow compiling, testing, and packaging Scala.js and Scala Native projects. Demonstration projects showcasing usage. |
|Prerequisites            | Experience with Scala, build tools (SBT, Bazel), and Scala.js/Scala Native basics. Some familiarity with Bazel rule definitions is a plus. |
|Expected Difficulty      | Medium |
|Expected Time Commitment | Large project - 350 hours |
|Mentor                   | Wojciech Mazur (GitHub: [@WojciechMazur](https://github.com/WojciechMazur), Email: [wmazur@virtuslab.com](wmazur@virtuslab.com))|
|Co-mentor                | TODO |

| Title                   | JMH-Compliant Benchmarking Framework for Scala Native & Scala.js |
|-------------------------|-------------------------------------------------------------|
|Link to Project          | [Scala Native](https://scala-native.org/) / [Scala.js](https://www.scala-js.org/) |
|Brief Description        | This project aims to implement a benchmarking framework similar to JMH (Java Microbenchmark Harness)  allowing for accurate and reliable performance measurements on non JVM platforms. Both Scala Native and Scala.js cannot consume a modified JVM bytecode emitted by JMH framework. The goal is to create a runtime implementation for executing microbenchmarks and a Scala compiler plugin performing required transformations of Scala.js / Scala Native code based on JMH framework compiletime annotations. |
|Expected Outcome         | A benchmarking framework that mimics JMH APIs and produces reliable results for Scala Native and Scala.js. Demonstration benchmarks showcasing usage. |
|Prerequisites            | Good understanding of benchmarking principles, Scala Native, Scala.js, and Scala compiler plugins. Some knowledge of JMH is beneficial. |
|Expected Difficulty      | Hard |
|Expected Time Commitment | Medium project - 175 hours |
|Mentor                   | Wojciech Mazur (GitHub: [@WojciechMazur](https://github.com/WojciechMazur), Email: [wmazur@virtuslab.com](mailto:wmazur@virtuslab.com) )|
|Co-mentor                | Sébastien Doeraene (GitHub: [@sjrd](https://github.com/sjrd), Email: [sjrdoeraene@gmail.com](mailto:sjrdoeraene@gmail.com) ) |

### Scala Native Projects

| Title                   | Incremental Optimization of Scala Native IR |
|-------------------------|-----------------------------------------------|
|Link to Project          | [Scala Native](https://scala-native.org/) |
|Brief Description        | This project aims to implement incremental optimization for Scala Native’s Intermediate Representation (IR), improving compilation speed by reusing results from previous compilation runs instead of optimizing the entire program from scratch. |
|Expected Outcome         | A working prototype of an incremental optimization pipeline for Scala Native IR, with measurable speedups over full optimizations. |
|Prerequisites            | Strong understanding of compilers, Scala Native IR, and optimization techniques. Knowledge of LLVM and incremental compilation strategies is a plus. |
|Expected Difficulty      | Hard |
|Expected Time Commitment | Large project - 350 hours |
|Mentor                   | Wojciech Mazur (GitHub: [@WojciechMazur](https://github.com/WojciechMazur), Email: [wmazur@virtuslab.com](mailto:wmazur@virtuslab.com) )|
|Co-mentor                | Sébastien Doeraene (GitHub: [@sjrd](https://github.com/sjrd), Email: [sjrdoeraene@gmail.com](mailto:sjrdoeraene@gmail.com) ) |

### Difflicious UI

| Title                    | Difflicious UI                                                                                                                                                                                                           |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | https://github.com/jatcwang/difflicious                                                                                                                                                                                  |
| Brief Description        | Implement a Web UI for Difflicious which allows users to explore diffs (test failures) reported by Difflicious. The UI should allow the user to expand and minimize section of the diff output in an interactive manner. |
| Expected Outcome         | Working UI and documentation                                                                                                                                                                                             |
| Prerequisites            | Good working knowledge of Scala and web technologies (Javascript, CSS, HTML). The project will be implemented in Scala.js (most likely with [Laminar](https://laminar.dev/)                                              |
| Expected Difficulty      | Hard                                                                                                                                                                                                                     |
| Expected Time Commitment | Large project - 350 hours                                                                                                                                                                                                |
| Spoken Language          | English                                                                                                                                                                                                                  |
| Mentor                   | Jacob Wang (GitHub: [@jatcwang](https://github.com/jatcwang), Email: [jatcwang@gmail.com](mailto:jatcwang@gmail.com))                                                                                                    |

### Difflicious: Differ for Json type

| Title                    | Difflicious: Differ for Json type                                                                                                                        |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link to Project          | https://github.com/jatcwang/difflicious                                                                                                                                                                                      |
| Brief Description        | Implement a differ which supports JSON types from popular Scala libraries (e.g. [Circe](https://github.com/circe/circe)). The current sealed trait Differ will be completely reworked to support any general disjoint union. |
| Expected Outcome         | A differ that can diff two two `io.circe.Json` values                                                                                                                                                                        |
| Prerequisites            | Good working knowledge of Scala                                                                                                                                                                                              |
| Expected Difficulty      | Hard                                                                                                                                                                                                                         |
| Expected Time Commitment | Medium project - 175 hours                                                                                                                                                                                                   |
| Spoken Language          | English                                                                                                                                                                                                                      |
| Mentor                   | Jacob Wang (GitHub: [@jatcwang](https://github.com/jatcwang), Email: [jatcwang@gmail.com](mailto:jatcwang@gmail.com)) |

### A Pandas Experience

|Title                   | A Pandas Experience |
|------------------------|--------------------------------|
|Link to Project         |https://github.com/Quafadas/scautable |
|Brief Description       |Python through Pandas has a great data import experience. This project aims to replicate parts of that by parsing parts of the datasource _at compile time_, i.e. bringing knowledge of the structure and headers of your datasource inside the compilers knowledge. It's goal is to help you _discover_ your data, rather than force to you to write out it's metadata in advance. It's target audience will be writing non production, data sciency type scripts. Many of the motivating examples come from kaggle.com|
|Expected Outcome        |Can be measured in the increased number of successful test cases. I believe the "fundamental" idea has legs, but is currently limited to a small number of scenarios explored in my free time. The goal of the project is to expand the set of scenarios in which it is useful. Initial easy issues surround details such as correctly parsing headers, checking special characters, improving error messages and writing data back to (e.g. CSV). From there it should be possible to graduate to adding more datasources, for example SQL (hopefully simple - or harder, for example exploring apache parquet.) Stretch goals could include exploring strategies for streaming statistics, deriving visualisations, critiquing the design vs e.g. Kantan.csv, and / or attempting to help the consumer identify the "types" of the data at compile time. |
|Prerequisites           |Basic scala / java knowledge. The barrier to "getting started" ought to be rather low. The initial issues are largely detail driven rather than design driven. Basic experience with testing (munit), CI (GHA) and scala standard library would be enough to contribute. |
|Expected Difficulty     |Easy|
|Expected Time Commitment|Medium project - 175 hours|
|Spoken Language         |English|
|Mentor                  |Simon Parten (GitHub: [@quafadas](https://github.com/foo), Email: [quafadas@gmail.com](mailto:quafadas@gmail.com))|
|Co-mentor               |Volunteers wanted here too I guess :-)|

### Scalus – Scala 3 compiler backend and DApps development platform for Cardano

|Title                   |   Scalus – Scala 3 compiler backend and DApps development platform for Cardano     |
|------------------------|-------------------------------------------------------------------------------------|
|Link to Project         | https://github.com/nau/scalus            |
|Brief Description       | Scalus is a platform for developing full-stacke decentralized applications (DApps) on the Cardano blockchain using a single language, Scala 3, tools and code for frontend, backend and smart contracts development. Scalus implements a Scala 3 compiler backend that compiles Scala to Cardano Plutus Core – a lambda calculus inspired smart contracts language. |
|Expected Outcome        | Enable more Scala 3 features to be compiled to Plutus Core: arbitrary size Tuples, better pattern-matching conversion algorithm. Improvements in our code generator, and various lambda calculus optimizations: inliner, common subexpression eliminator etc. We also expect improvements in Scalus standard library, test coverage and documentations. |
|Prerequisites           | Basic Scala knowledge. Basic understanding of compiler theory and blockchain technology is a plus. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Alex Nemish [Github](https://github.com/nau), Email: anemish@gmail.com |
|Co-mentor               | Ruslan Shevchenko.  [Github](https://github.com/rssh) Email: <ruslan@shevchenko.kiev.ua> |

### Scaladex: Support for Compiler Plugins

| Title                   | Scaladex: Support for Compiler Plugins |
| ----------------------- | -------------------------------- |
| Link to Project         | https://github.com/scalacenter/scaladex/ |
| Brief Description       | Add support for compiler plugins in Scaladex, the index website of open source Scala artifacts. Adapt the UI of the front page, search page and project page to allow searching, and browsing compiler plugins and their versions. See full description in [scalacenter/scaladex#865](https://github.com/scalacenter/scaladex/issues/865) |
| Expected Outcome        | Scaladex should index compiler plugin artifacts, such as [org.typelevel:kind-projector_2.13.16:0.13.3](https://repo1.maven.org/maven2/org/typelevel/kind-projector_2.13.16/0.13.3/). It should show them as a separate platform on the front page, search page and project page. |
| Prerequisites           | Some experience with Scala and SQL. Good knowledge about HTML and css |
| Ideal Prerequisites     | Some knowledge of the Scala ecosystem, such as Scala platforms and binary versions |
| Expected Difficulty     | Medium |
| Expected Time Commitment| Medium project - 175 hours |
| Spoken Language         | English |
| Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com)) |
| Co-mentor               | Adrien Piquerez (GitHub: [@adpi2](https://github.com/adpi2), Email: [adrien.piquerez@gmail.com](mailto:adrien.piquerez@gmail.com)) |

### LLM4S - Implement an agentic toolkit for Large Language Models

|Title                   | LLM4S - Implement an agentic toolkit for Large Language Models                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Link to Project         | https://github.com/rorygraves/llm4s                                                                                                                                                                                                                                                                                                                                                                                                                              |
|Brief Description       | LLM4S is creating a Large Language Model (LLM) toolkit for Scala.  This project uses the power of Scala to make building LLM based applications easier.  LLMs can be used in an agentic style where the LLM is allowed to call provided tools to access resources (such as reading a webpage, or calling an API service to perform a task).  The goal of this project is to implement an agentic loop and basic tools supporting infrastructure within the toolkil. |
|Expected Outcome        | LLM4S should have an agentic LLM toolkit wtih, documentation, examples and basic tools such as file and webbrower usage  to allow users to immediately start building agentic style applications.                                                                                                                                       |
|Prerequisites           | Some exerience of Scala and LLMs.                                                                                                                                                                                                                                                                                                                                                                                                                                |
|Expected Difficulty     | Medium                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|Expected Time Commitment| Large project - 350 hours                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|Spoken Language         | English                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com))                                                                                                                                                                                                                                                                                                                |
|Co-mentor               | Rory Graves ([LinkedIn](https://www.linkedin.com/in/roryjgraves/), Email: [rory.graves@fieldmark.co.uk](mailto:rory.graves@fieldmark.co.uk))                                                                                                                                                                                                                                                                                                                     |

### LLM4S - RAG in a box

|Title                   | LLM4S - RAG in a box                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Link to Project         | https://github.com/rorygraves/llm4s                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|Brief Description       | LLM4S is creating a Large Language Model (LLM) toolkit for Scala.  This project uses the power of Scala to make building LLM based applications easier.  Beyond simple chat use cases we want to make it easy to build LLM based apps.  One of the most common facilities is RAG (Retrieval Augmented Generation) where documents are chunked and embedded and then retrieved to provide context to the question being asked.   The goal is to extend the LLM framework with RAG tools to make building RAG Search easy. |
|Expected Outcome        | LLM4S should have a RAG framework which allows integration with an embedding store.  The framework should support pushing documents into external stores (e.g. Postgress with pgVector or Azure AI Search Service) and implement RAG search over the top of the store, and include documentation, examples.                                                                                                                                                                                                     |
|Prerequisites           | Some exerience of Scala and LLMs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|Expected Difficulty     | Medium                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|Expected Time Commitment| Large project - 350 hours                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|Spoken Language         | English                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|Mentor                  |  Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com))                                                                                                                                                                                                                                                                                                                                                              |
|Co-mentor               | Rory Graves ([LinkedIn](https://www.linkedin.com/in/roryjgraves/), Email: [rory.graves@fieldmark.co.uk](mailto:rory.graves@fieldmark.co.uk))                                                                                                                                                                                                                                                                                                                                                                    |
|Co-mentor               | Dmitry Mamonov ([LinkedIn](https://www.linkedin.com/in/dmamonov/), Email: [dmitry.s.mamonov@gmail.com](mailto:dmitry.s.mamonov@gmail.com))                                    

### LLM4S - Support image, voice and other LLM modalites

|Title                   | LLM4S - Support image, voice and other LLM modalites                                                                                                                                                                                                                                                                                                                        |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Link to Project         | https://github.com/rorygraves/llm4s                                                                                                                                                                                                                                                                                                                                         |
|Brief Description       | LLM4S is creating a Large Language Model (LLM) toolkit for Scala.  This project uses the power of Scala to make building LLM based applications easier.  LLMs support a number of modalities other than chat, e.g., image generation, voice and embeddings.   The goal of this project is to extend the API created in LLM4S to create APIs for calling these other use cases. |
|Expected Outcome        | As well as chat, LLM4S LLM interface should now have support for image, voice (speech to text and text to speech) and embeddeding, giving users access to more usecases.  As well as the API, we will provide examples and documentation.                                                                                                                                   |
|Prerequisites           | Some exerience of Scala and LLMs.                                                                                                                                                                                                                                                                                                                                           |
|Expected Difficulty     | Medium                                                                                                                                                                                                                                                                                                                                                                      |
|Expected Time Commitment| Large project - 350 hours                                                                                                                                                                                                                                                                                                                                                   |
|Spoken Language         | English                                                                                                                                                                                                                                                                                                                                                                     |
|Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com))                                                                                                                                                                                                                           |
|Co-mentor               | Rory Graves ([LinkedIn](https://www.linkedin.com/in/roryjgraves/), Email: [rory.graves@fieldmark.co.uk](mailto:rory.graves@fieldmark.co.uk))                                                                                                                                                                                                                                |


### LLM4S - Tracing Support

|Title                   | LLM4S - Tracing support                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Link to Project         | https://github.com/rorygraves/llm4s                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|Brief Description       | LLM4S is creating a Large Language Model (LLM) toolkit for Scala.  This project uses the power of Scala to make building LLM based applications easier.  As LLM based apps grow it becomes harder to understand the application and LLM interaction flow.  We want to add tracing support into the application and a UI allowing exploration of the application traces, showing the calls, spans, timing and other information to help understand the flow. |
|Expected Outcome        | An exampling tracing feature within the core of LLM5S that emits tracing data consumable by a created UI to allow a user to follow the execution flow of a user developed application.                                     |
|Prerequisites           | Some exerience of Scala and LLMs.                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|Expected Difficulty     | Medium                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|Expected Time Commitment| Large project - 350 hours                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|Spoken Language         | English                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com))                                                                                                                                                                                                                                                                                                                    |
|Co-mentor               | Rory Graves ([LinkedIn](https://www.linkedin.com/in/roryjgraves/), Email: [rory.graves@fieldmark.co.uk](mailto:rory.graves@fieldmark.co.uk))                                                                                                                                                                                                                                                                                                                         |
|Co-mentor               | Dmitry Mamonov ([LinkedIn](https://www.linkedin.com/in/dmamonov/), Email: [dmitry.s.mamonov@gmail.com](mailto:dmitry.s.mamonov@gmail.com))                                                                                                                                                                                                                                                                                                                           |
### Template

|Title                   | |
|------------------------|--------------------------------|
|Link to Project         |Provide a link to a website or a Git repository of your project.|
|Brief Description       |Please describe in a few sentences what the project is about.|
|Expected Outcome        |Specify the success criteria for the project. What are the deliverables, how do you know that it is done?|
|Prerequisites           |What minimal skills and knowledge the contributor needs to have to succeed on this project?|
|Expected Difficulty     |Easy, Medium of Hard|
|Expected Time Commitment|Can be either: "Medium project - 175 hours" or "Large project - 350 hours"|
|Spoken Language         |English|
|Mentor                  |FirstName LastName (GitHub: [@foo](https://github.com/foo), Email: [foo@gmail.com](mailto:foo@gmail.com))|
|Co-mentor               |FirstName LastName (GitHub: [@foo](https://github.com/foo), Email: [foo@gmail.com](mailto:foo@gmail.com))|


-----

## Maintainers

Want to connect with maintainers? The Google Summer Of Code(GSoC) program is maintained by:

- **Scala Center Team** – Join us on [Discord](https://discord.gg/afRW3cGpwP) for general questions and community support.
- **GSoC Org Admin – Kannupriya Kalra** – [LinkedIn](https://www.linkedin.com/in/kannupriyakalra/) | Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com) | Discord: `kannupriyakalra_46520`


