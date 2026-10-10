# Versatia

A framework for Paper 1.21.4 plugins written in Kotlin. Annotate, build, done: dependency
injection, lifecycle functions, listener registration and resource extraction are declared in the
plugin's sources and resolved at **compile time** into a descriptor that the runtime executes.
Nothing is scanned on the server, errors show up as compiler errors, and private classes stay private.

<p align="center">
  <a href="https://versatiaframework.github.io/VersatiaDocs/"><img alt="Documentation" src="https://img.shields.io/badge/Documentation-versatiaframework.github.io-3f51b5?style=for-the-badge&logo=readthedocs&logoColor=white"></a>
  <a href="https://github.com/VersatiaFramework/VersatiaExamples"><img alt="Examples" src="https://img.shields.io/badge/Examples-one%20feature%20per%20repository-3f51b5?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

Start with the **[documentation](https://versatiaframework.github.io/VersatiaDocs/)**: installation,
a first plugin in ten minutes, then one page per feature, each pointing at the example repository
that shows it.

| Repository | Role |
|---|---|
| [VersatiaAPI](https://github.com/VersatiaFramework/VersatiaAPI) | the library plugins compile against, with the compile-time step |
| [VersatiaCore](https://github.com/VersatiaFramework/VersatiaCore) | the runtime: a Paper plugin that interprets the descriptors; a **private** repository, distributed as a JAR |
| [VersatiaDocs](https://github.com/VersatiaFramework/VersatiaDocs) | the documentation site |
| [VersatiaExamples](https://github.com/VersatiaFramework/VersatiaExamples) | the catalogue of example plugins, one feature each |
