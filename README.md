# Sbt-Base

Giter8 template I use as a starting point for my SBT projects. 

Creates a project with the following setup:

1. Strict scalac options
2. Code formatting using [scalariform](https://github.com/scala-ide/scalariform)
3. Linting using [scapegoat](https://github.com/sksamuel/scapegoat), [scalastyle](https://github.com/scalastyle/scalastyle-sbt-plugin), [wart-remover](https://github.com/puffnfresh/wartremover) and [linter compiler plugin](https://github.com/HairyFotr/linter). The `compilecheck` sbt task runs scapegoat and scalastyle after compilation. 
4. Useful set of sbt plugins ([api-mappings](https://github.com/ThoughtWorksInc/sbt-api-mappings), [stats](https://github.com/orrsella/sbt-stats), [updates](https://github.com/rtimush/sbt-updates), [todo-list](https://github.com/fedragon/sbt-todolist), [clippy](https://scala-clippy.org/))
5. Testing using scalatest and scalacheck
6. Coverage reports using [scoverage](https://github.com/scoverage/sbt-scoverage)

My preferred scalastyle configuration is also included in this repository. 

## To use

1. Install [giter8](https://github.com/foundweekends/giter8)
2. `cd` to your projects directory
3. execute `g8 harshad-deo/sbtbase`
