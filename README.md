# Docs-as-Code

Docs-as-Code project demonstrates the use of Asciidoc to generate software documentation. Combining models from the following sources:

+ [Arc42](https://arc42.org/download)
+ [C4-model](https://c4model.com/)
+ Architecture Decision Records

Generation of diagrams is supported using PlantUML.

## Getting Started

### Libraries

+ **AsciidoctorJ** is the official library for running Asciidoctor on the JVM. Using AsciidoctorJ, you can convert AsciiDoc content or analyze the structure of a parsed AsciiDoc document from Java and other JVM languages.

[AsciiDoctorJ](https://asciidoctor.org/docs/asciidoctorj/)

+ asciidoctor-gradle-plugin

+ asciidoctorj-diagram

Asciidoctor Diagram is a set of Asciidoctor extensions that enable you to add diagrams, which you describe using plain text, to your AsciiDoc document.

The extensions supports:

- [GraphViz](https://graphviz.gitlab.io/_pages/doc/info/lang.html)
- [PlantUML](http://plantuml.sourceforge.net/)

+ asciidoctorj-pdf

+ gradle 

+ Graphviz

[Graphviz](http://www.graphviz.org/)

### Prerequisites

+ Java installed
+ [Graphviz](https://graphviz.gitlab.io/) installed (needed to generate diagrams)

## Running

Execute the documentation generation by:
`./gradlew asciidoctor`

The generated documentation can be found at:

+ `/build/asciidoc/index.html` (HTML website)
+ `/build/asciidoc/index.pdf` (PDF document)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The documentation template is inspired by the ARC42 model/C4-Model and Architecture Decision Records.
