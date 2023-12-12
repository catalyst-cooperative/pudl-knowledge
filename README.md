# pudl-research

Welcome!

This is a place for "knowledge contributions" to
[PUDL](https://github.com/catalyst-cooperative/pudl). Knowledge contributions are:

* written descriptions of individual datasets and the difficulties of working
  with them
* well-commented code snippets that show how one has worked around some of
  these difficulties
* other forms of documentation that provide context that would be useful for
  someone looking to work with this dataset

Since this knowledge is often hard-won and also often repeated, we want to
collect it in a place so everyone can benefit.

This repository is **MIT-licensed**, which means that anything contributed here
can be used very freely by others. See `LICENSE` for details.

We do not track the data files themselves in this repository.


## Contributing

We expect all contributors to follow the [PUDL Code of
Conduct](https://github.com/catalyst-cooperative/pudl/blob/main/docs/CODE_OF_CONDUCT.md).

1. [Fork this
   repository](https://github.com/catalyst-cooperative/pudl-knowledge/fork).
2. If there is a directory for your dataset in this directory already, great!
   If there isn't, feel free to create one - we prefer the directory name to be
   all-lowercase without any punctuation marks.
3. Put your human-language documentation in the appropriate directory's
   `README.md`; put any code you want to contribute in the same directory.
   Here's an example layout:
    ```
    .
    ├── eia176
    │   └── README.md
    ...
    └── ferc2
        ├── README.md
        └── scheduleABC
            ├── README.md
            └── workaround.ipynb
    ```
4. Make a [pull
   request](https://github.com/catalyst-cooperative/pudl-knowledge/pulls) and
   tag `@catalyst-cooperative/com-dev ` in the pull request. We'll get back to
   you within a few days!
