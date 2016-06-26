# github-unmaintained-templates

> GitHub templates to indicate a project is unmaintained

You can use these [issue][] and [pull request][] templates to indicate that
your project is unmaintained.

[issue]: https://help.github.com/articles/creating-an-issue-template-for-your-repository/
[pull request]: https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/

## Usage

```shell
mkdir .github
cp {ISSUE,PULL_REQUEST}_TEMPLATE.md .github
```

## Pro tip

![Project unmaintained][unmaintained-image]

Add a fancy badge to your readme like the above via:

```
[![Project unmaintained][unmaintained-image]][unmaintained-url]

[unmaintained-url]: .github/ISSUE_TEMPLATE.md
[unmaintained-image]: https://img.shields.io/badge/project-unmaintained-red.svg
```

[unmaintained-image]: https://img.shields.io/badge/project-unmaintained-red.svg

## Author

© 2016 Tom Vincent <https://tlvince.com/contact>

## License

Released under the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/) (public domain).
