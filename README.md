# scala-kata-kickstart
Minimal Scala project for kick-starting Coding Katas with Scala + ScalaTest

## How to start?

1. start the sbt console with `./activator` or `activator.bat`

2. In the sbt console, compile the project with `compile`.
   The project should compile without any errors.

3. In the sbt console, let the tests run with `test`.

More commands:

- `test` launches all tests
- `testOnly *Spec` launches only the tests with the full name matching `*Spec`
- `testQuick` launches only the tests that failed and the tests impacted by the changes
- `~<command>` trigger the <command> each time the code is changed. For example, `~testQuick`


## Integration in IDE

### Intellij

In [Intellij](https://www.jetbrains.com/idea/):

1. install the [Scala plugin](https://confluence.jetbrains.com/display/SCA/Getting+Started+with+IntelliJ+IDEA+Scala+Plugin)
   (no need to install a Scala SDK before)

2. create a new project from existing sources by selecting the file `build.sbt`.


### Scala IDE (based on Eclipse)

In [Scala IDE](http://scala-ide.org/):

1. Start the sbt console

2. Enter `eclipse with-source=true`

3. Open the generated project with Scala IDE.

[Look at the documentation for more info](http://scala-ide.org/docs/user/gettingstarted.html).