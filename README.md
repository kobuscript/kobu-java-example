# kobu-java-example

[Kobu](https://github.com/kobuscript/kobu-interpreter) is a domain-specific programming language for constructing 
source code generators.

This example contains two scripts that parse and edit Java files:

* **ToString.kobu**: Create a toString() method for a Java class.
* **Builder.kobu**: Create a builder inner class for a Java class or record.

## Usage

Install the [Kobu Intellij plugin](https://github.com/kobuscript/kobu-intellij) and copy this folder to your Java project. You can create a "kobu" root folder, your use the standard "src/main/kobu", if your project uses Maven or Gradle.

When editing a Java file, the scripts will be available in the editor's context menu.
