In this documnent, you can find a list of ideas that are proposed by Scala Center for Google Summer of Code 2022.

If you are interested in any idea or would like to propose your own, please reach out to your potential mentor. You can also reach Scala Center at scala.center(at)epfl.ch.

# Project Ideas

## Notebook support in Metals

|Title                   | Notebook support in Metals |
|------------------------|-|
|Link to Project         | https://github.com/scalameta/metals |
|Brief Description       | https://github.com/scalameta/metals-feature-requests/issues/236 <br /><br />Overall, VS Code allows to support notebook cells and there is a number of things we would need to do to make it available. These would include automatic setup of almond, integrating with the build definition and adding LSP support for notebook cell.  There is also the possibility of extending the task to making jupiter supported with Metals completions. |
|Expected Outcome        | Users able to create notebook cells in their projects and running them. |
|Prerequisites           | Scala |
|Ideal Prerequisites     | Good knowledge of Scala and experience with notebooks. |
|Expected Difficulty     | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Tomasz Godzik |

## Semantic highlighting in VS Code

|Title                   | Semantic highlighting in VS Code |
|------------------------|-|
|Link to Project         | https://github.com/scalameta/metals |
|Brief Description       | Semantic highlighting is a part of the default LSP spec, which is not yet supported by Metals. This would allow to highlight tokens (keywords etc.) based on the knowledge of the code. Especially useful with things like soft keywords in Scala 3, but not only. Connected issue https://github.com/scalameta/metals-feature-requests/issues/57 |
|Expected Outcome        | Working semantic highlighting |
|Prerequisites           | Scala |
|Ideal Prerequisites     | Scala and a bit of knledge about LSP |
|Expected Difficulty     | Easy – straightforward task, path for execution visible right now, very little uncertainty |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Tomasz Godzik |

## LSP Call hierarchy in Metals

|Title                   | LSP Call hierarchy in Metals  |
|------------------------|-|
|Link to Project         | https://github.com/scalameta/metals |
|Brief Description       | Call hierarchy is part of the LSP spec and allows editors to show the users a hierachy of method calls. More info in the issue https://github.com/scalameta/metals-feature-requests/issues/188 |
|Expected Outcome        | Working call hierarchy |
|Prerequisites           | Scala |
|Ideal Prerequisites     | Scala and a bit of knowledge about LSP |
|Expected Difficulty     | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Tomasz Godzik |

## Resurect Scala Native bindings generator

|Title                   | Resurect Scala Native bindings generator |
|------------------------|-|
|Link to Project         | https://github.com/scala-native/scala-native-bindgen |
|Brief Description       | Scala Native bindings generator is a tool designed to create Scala Native bindings from C header files. In the recent years, this project was not actively maintained, it does no longer align with the current Scala Native API, neighter it does not faciliate new features of Scala, e.g. top level definitions. <br /> |
|Expected Outcome        | 1. Update existing implementation of Scala Native Bindgen to match current API of Scala Native 0.4.x. <br />2. Introduce mechanism for generation of bindings for Scala 3, using opaque types, inlines and other features that might be improve developers experience. <br />3. Optionally introduce mechanism for generating bindings for other languages, e.g. C++, Rust etc. |
|Prerequisites           | Basic knowledge of Scala and C |
|Ideal Prerequisites     | Good knowledge of Scala 3, experience of working with Scala Native |
|Expected Difficulty     | Easy – straightforward task, path for execution visible right now, very little uncertainty |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Wojciech Mazur |

## Optimization of Scala Native linker

|Title                   | Optimization of Scala Native linker  |
|------------------------|-|
|Link to Project         | https://github.com/scala-native/scala-native  |
|Brief Description       | One of Scala Native issues are long build times, especially with larger projects. The problem is especially visible when using optimizer with release mode, for which work currently is not parallised. The goal of this project is to find and improve existing bottlenecks slowing Scala Native build pipeline, which includes speeding up optimizer, introducing incremental compilation and to examine if providing LLVM IR in binary format would improve compiler performance.<br /> |
|Expected Outcome        | 1. Setting up benchmarks measuring performance of Scala Native linker<br />2. Introduction and evaluation of possible optimiazation techniques for Scala Native linker, with the goal of lowering linking times by at least 20% |
|Prerequisites           | Basic Scala 2 / Java, LLVM and C knowledge |
|Ideal Prerequisites     | Good Scala 2 or Java knowledge with additional experience in the JVM profiling. |
|Expected Difficulty     | Hard – involves high degree of uncertainty even for a highly experienced person |
|Expected Time Commitment| Long project – 350 hours |
|Mentor                  | Wojciech Mazur |

## Generation of debugging symbols in Scala Native and integration with LLDB debugger.

|Title                   | Generation of debugging symbols in Scala Native and integration with LLDB debugger.  |
|------------------------|-|
|Link to Project         | https://github.com/scala-native/scala-native |
|Brief Description       | Current code generation of LLVM IR in Scala Native is not capable of producing metadata that could be used by existing debugers. Lack of this feature is one of the blockers for wider usage of Scala Native in complex projects. Goal of this project is adaption of existing code generation pipeline to produce required metadata and to provide initialial integration with LLDB debuger.  <br /> |
|Expected Outcome        | 1. Introduction of debug symbols metadata in LLVM IR generated by Scala Native<br />2. Initial integration of Scala Native with one of existing assembly debuggers, e.g. LLDB, by allowing to lookup variables and source code which is being currently executed. <br />3. Optionally allow to evaluate expressions while using debbuger.     |
|Prerequisites           | Scala, LLVM  |
|Ideal Prerequisites     | Scala, LLVM |
|Expected Difficulty     | Hard – involves high degree of uncertainty even for a highly experienced person |
|Expected Time Commitment| Long project – 350 hours |
|Mentor                  | Wojciech Mazur |

## Doodle Explorer

|Title                   | Doodle Explorer |
|------------------------|-|
|Link to Project         | https://github.com/creativescala/doodle |
|Brief Description       | Doodle is a library for generative art. Generative art is typically parameterised by several parameters, such as colour and line thickness. The programmer often searches through many settings of these parameters until they find choices they like. The goal of this project is to create a DSL for describing parameter ranges, from which a UI for exploring the parameter space is generated. |
|Expected Outcome        | An embedded DSL that allows the user to specify parameter ranges for a function. from which a UI for exploring the parameter space is generated |
|Prerequisites           | Scala programming knowledge and an interest in generative art. |
|Ideal Prerequisites     | Ideally some knowledge of DSL implementation technique, particularly tagless final. |
|Expected Difficulty     | Easy – straightforward task, path for execution visible right now, very little uncertainty |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Noel Welsh |

## Doodle Bitmap Support

|Title                   | Doodle Bitmap Support |
|------------------------|-|
|Link to Project         | https://github.com/creativescala/doodle/ |
|Brief Description       | Improve Doodle's support for bitmaps, adding additional methods to load bitmaps, and perform convolution operations on them. |
|Expected Outcome        | An extension to Doodle for loading bitmaps and performing convolution operations. |
|Prerequisites           | Basic Scala knowledge |
|Ideal Prerequisites     | Some knowledge of convolution operations. |
|Expected Difficulty     | Easy – straightforward task, path for execution visible right now, very little uncertainty |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Noel Welsh: [noel@noelwelsh.com](mailto:noel@noelwelsh.com) |

## Scala 3 Dataframe

|Title                   | Scala 3 Dataframe |
|------------------------|-|
|Link to Project         | https://github.com/noelwelsh/framed |
|Brief Description       | Scala 3's improved support for macros and extensible records (tuples) opens the possibility for creating a typed data frame that is dramatically more usable than previous attempts in Scala 2. The goal of this project is to complete a proof of concept demonstrating the viability of creating such a system. |
|Expected Outcome        | A library demonstrating the implementation techniques needed to bring a full typed dataframe to fruition in Scala 3 |
|Prerequisites           | Good knowledge of Scala programming |
|Ideal Prerequisites     | Some knowledge of dataframes, and Scala 3's compile-time metaprogramming tools. |
|Expected Difficulty     | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
|Expected Time Commitment| Long project – 350 hours |
|Mentor                  |Noel Welsh: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)  |

## Extract npm dependencies from scalajs-bundler

|Title                   | Extract npm dependencies from scalajs-bundler |
|------------------------|-|
|Link to Project         | https://github.com/scalacenter/scalajs-bundler |
|Brief Description       | scalajs-bundler was initially developed for Scala.js project to declare dependencies on NPM libraries, resolving them, and bundling them together with the Scala.js code with Webpack. As time passed, several new bundlers have come to the scene, and Webpack is not the only contender. Moreover, many Scala.js users report that using scalajs-bundler to drive Webpack causes more problems than it solves, and they prefer to configure and run Webpack themselves. However, the need to declare NPM dependencies and resolving them is still there, and arguably scalajs-bundler does a good job of it.<br /><br />This project is about extracting the `npmDependencies`+npm/yarn management out of scalajs-bundler, in a new, independent sbt plugin. This way, Scala.js users can all rely on this core, and use the bundler of their choice. |
|Expected Outcome        | * The `npmXyz` settings and tasks of scalajs-bundler should be extracted in a separate sbt plugin (perhaps even in a separate repository).<br />* An a appropriate test suite will accompany that plugin.<br />* At least one example project using that plugin and directly integrating with a JS bundler of choice (perhaps Vite or Snowpack) will be showcased.<br />* scalajs-bundler will be adapted to depend on that sbt plugin, to reuse its settings and tasks. |
|Prerequisites           | * Knowing your way around an sbt build |
|Ideal Prerequisites     | * Be familiar with the NPM ecosystem<br />* Have developed an sbt plugin before<br />* Be familiar with Scala.js |
|Expected Difficulty     | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Sébastien Doeraene |

## Write a compatible ExplicitResultTypes rule for Scala 3

|Title                   | Write a compatible ExplicitResultTypes rule for Scala 3 |
|------------------------|-|
|Link to Project         | https://github.com/scalacenter/scalafix |
|Brief Description       | Scalafix provides rules that rewrite or lint your code. One of them is ExplicitResultTypes, that add explicit types to def/val/var. This rule is linked to Scala 2 compiler. We need to rewrite it to interface with the Scala 3 compiler. |
|Expected Outcome        |  A working ExplicitResultTypes |
|Prerequisites           | Required: some experience with Scala, eagerness to learn more about Scala 3. <br /> |
|Ideal Prerequisites     | Preferred: some familiarity with Scalafix and Scalameta. |
|Expected Difficulty     | Medium – doable with high chance of success given creativity and problem-solving skills from the one doing it |
|Expected Time Commitment| Short project – 175 hours |
|Mentor                  | Meriam Lachkar - Brice Jaglin |
|Cantact information     | meriam.lachkar@gmail.com - bjaglin@gmail.com | 
