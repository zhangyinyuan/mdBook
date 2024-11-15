# mdBook
# 支持中文操作步骤
1. `cargo install mdbook --git https://github.com/zhangyinyuan/mdBook.git --branch search-non-english --force`
2. mdbook init mybook
3. 修改mybook下的book.toml
   ```
   [book]
   language = "zh-Hans"
   ```

 参考 [mdBook 生成站点的中文搜索支持](https://rustcc.cn/article?id=e8c04111-e8f4-47d3-a73c-3759d0a9482c)
   

[![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?event=push)](https://github.com/rust-lang/mdBook/actions?workflow=CI)
[![crates.io](https://img.shields.io/crates/v/mdbook.svg)](https://crates.io/crates/mdbook)
[![LICENSE](https://img.shields.io/github/license/rust-lang/mdBook.svg)](LICENSE)

mdBook is a utility to create modern online books from Markdown files.

Check out the **[User Guide]** for a list of features and installation and usage information.
The User Guide also serves as a demonstration to showcase what a book looks like.

If you are interested in contributing to the development of mdBook, check out the [Contribution Guide].

## License

All the code in this repository is released under the ***Mozilla Public License v2.0***, for more information take a look at the [LICENSE] file.

[User Guide]: https://rust-lang.github.io/mdBook/
[contribution guide]: https://github.com/rust-lang/mdBook/blob/master/CONTRIBUTING.md
[LICENSE]: https://github.com/rust-lang/mdBook/blob/master/LICENSE
