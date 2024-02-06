In this document, you can find a list of ideas that are proposed by the Scala Organisation for Google Summer of Code 2024.

If you are interested in becoming a contributor on any idea, please reach out to your potential mentor. You can also reach Scala Center at [scala.center(at)epfl.ch](mailto:scala.center@epfl.ch).

If you would like to be a mentor and propose your own idea, please submit a PR editing this file (e.g. see [2023's projects](Past%20years%20ideas/2023.md)), adding your project to the list, following the format of other projects below.

# Project Ideas

## [TEMPLATE] Project Title

|Title                   |Project Title|
|------------------------|-|
|Link to Project         |Provide a link to a website or a Git repository of your project.|
|Brief Description       |Please describe in a few sentences what the project is about.|
|Expected Outcome        |Specify the success criteria for the project. What are the deliverables, how do you know that it is done?|
|Prerequisites           |What minimal skills and knowledge the contributor needs to have to succeed on this project?|
|Ideal Prerequisites     |What would would be the ideal skillset you are looking for on the project.|
|Expected Difficulty     |How hard would it be to complete the project?|
|Expected Time Commitment|Can be either: "Medium project – 175 hours" or "Large project – 350 hours"|
|Spoken Language         |Which language can you speak?|
|Mentor                  |FirstName LastName (GitHub: [@foo](https://github.com/foo), Email: [foo@gmail.com](mailto:foo@gmail.com)) |
|Co-mentor               | |



## Doodle Canvas

|Title                   |Doodle Canvas|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle/|
|Brief Description       |Doodle is a library for 2D graphics. It has good support for producing structured images, but sometimes you just want to blast pixels onto a screen. This project aims to add support for that.|
|Expected Outcome        |A Doodle algebra or algebras that support writing pixels, and probably lines, circles, and other shapes, directly onto the screen.|
|Prerequisites           |Basic Scala knowledge|
|Ideal Prerequisites     |Some understanding on tagless final style.|
|Expected Difficulty     |Easy – straightforward task, path for execution visible right now, very little uncertainty|
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
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
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com))|
|Co-mentor               | |

## Generate Scala Documentation website with Scaladoc

|Title                   |Generate Scala Documentation website with Scaladoc|
|------------------------|--------------------------------------------------|
|Link to Project         |https://github.com/scala/docs.scala-lang/|
|Brief Description       |Scaladoc for Scala 3 has a modern UI and is developed to render static websites. We would like to use it to replace Jekyll in rendering the documentation website.|
|Expected Outcome        |We would like a MVP of the website, generated via Scaladoc. We'd need to add support for some Jekyll features such as `include`, and our custom tabs liquid extension.|
|Prerequisites           |some Scala knowledge|
|Ideal Prerequisites     |familiarity with Jekyll, fundamentals of CSS and JS|
|Expected Difficulty     |Medium - We mostly expect pure engineering to bring in the needed Jeykll features, which can be tested on the present documentation sources. As a stretch goal the participant may want to work on styling the pages, create a plug-in system for Scaladoc, or work on incremental documentation builds.|
|Expected Time Commitment|Large project – 350 hours|
|Mentor                  |Jamie Thompson (GitHub: [@bishabosha](https://github.com/bishabosha), Email: [jamie.thompson@bath.edu](mailto:jamie.thompson@bath.edu)) |
|Co-mentor               | |

## Dotty-cps-async:  support for extensible effect stacks.

|Title                   |Support for extensible effect stacks in dotty-cps-async|
|------------------------|-|
|Link to Project         |https://github.com/rssh/dotty-cps-async|
|Brief Description       |Add support for effect stacks into dotty-cps-async.|
|Expected Outcome        |Project module with working code and documentation for users and effect stack providers.|
|Prerequisites           |Some Scala knowledge|
|Ideal Prerequisites     |Basic knowledge of functional programming and understanding of effect stacks|
|Expected Difficulty     |Medium – path for execution visible right now, but possible high variations of efforts depend of unknown technical details|
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Ruslan Shevchenko (GitHub: [@rssh](https://github.com/rssh), Email: [ruslan@shevchenko.kiev.ua](mailto:ruslan@shevchenko.kiev.ua))|
|Co-mentor               | |

## Scala CLI: scripting protocol

|Title                   |Scripting protocol for Scala CLI|
|------------------------|--------------------------------|
|Link to Project         |https://github.com/VirtusLab/scala-cli|
|Brief Description       |Extend Scala CLI with a scripting protocol that can be used to e.g. create source generators. (building on Bloop's built-in support) |
|Expected Outcome        |You can build a Scala CLI project that will run a source generator (e.g. Protobuf or Smithy). Configuration of script is handled via directives or CLI args, script itself is a self contained scala cli project executed with main method.|
|Prerequisites           |Some familiarity with Scala, understanding of serialization|
|Ideal Prerequisites     |Familiarity with Bloop and Scala-CLI, passion for developer tooling|
|Expected Difficulty     |Medium - protocol needs to expose metadata that is compatible with Scala CLI, and to be extensible in the future (core components are already done, such as Bloop integration) |
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Jamie Thompson (GitHub: [@bishabosha](https://github.com/bishabosha), Email: [jamie.thompson@bath.edu](mailto:jamie.thompson@bath.edu)) |
|Co-mentor               | |

## Scaladex: new artifact page

|Title                   |New artifact page in Scaladex|
|------------------------|--------------------------------|
|Link to Project         |https://github.com/scalacenter/scaladex|
|Brief Description       |Add a new page in Scaladex to browse through the list of all artifacts of a project. See full description in [scalacenter/scaladex#1337](https://github.com/scalacenter/scaladex/issues/1337)|
|Expected Outcome        |We can deploy the new version of Scaladex where it is possible to browse through the artifacts of a project by their names.|
|Prerequisites           |Some familiarity with Scala and SQL. Basic knowledge about HTML and CSS.|
|Ideal Prerequisites     |Familiarity with Scala's `Future`, akka-http, doobie|
|Expected Difficulty     |Medium - most of the implementation can be adapted from the existing code |
|Expected Time Commitment|Medium project – 175 hours|
|spoken Language         |French and English|
|Mentor                  |Adrien Piquerez (GitHub: [@adpi2](https://github.com/adpi2), Email: [adrien.piquerez@epfl.ch](mailto:adrien.piquerez@epfl.ch)) |
|Co-mentor               | |

