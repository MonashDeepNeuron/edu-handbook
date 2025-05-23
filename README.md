# MDN-Edu-Handbook

This repository contains the source code for the Education Training content and activities for new MDN Education members. This book is available online or can be built locally.

## Building

To build this book you need [mdBook](https://rust-lang.github.io/mdBook/index.html) a tool for creating books with Markdown. mdBook can be installed using Cargo - Rust's package manager.

```sh
cargo install mdbook
```

You can build this book you must clone this repository using Git. You can then build it and even serve it to localhost to view in your browser. The serve command will produce a localhost you can view.

```sh
$ git clone https://github.com/MonashDeepNeuron/HPC-Training.git
$ cd HPC-Training

# Build ...
$ mdbook build

# ... or serve build and serve locally
$ mdbook serve --open
```

## Contributors

- Jeevan Vetteel
- Sanithma Mahawithanage
- Justin (Jayus) Thiha
- Tyler Swann

## Code of Conduct, License & Contributing

Refer to the [Code of Conduct](/CODE_OF_CONDUCT.md) and the [License](/LICENSE) for this repository for the expected behavior of contributors and users of the repository. If you have any concerns, open a discussion or contact the appropriate members of Monash DeepNeuron. If you wish to contribute, follow the [contributing guide](/CONTRIBUTING.md).