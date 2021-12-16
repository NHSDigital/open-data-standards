# Contributing

We love contributions! We've compiled this documentation to help you understand our
contributing guidelines. [If you still have questions, please contact us][email] and
we'd be happy to help!

## Code of Conduct

[Please read `CODE_OF_CONDUCT.md` before contributing][code-of-conduct].

### Git and GitHub

We use Git to version control the source code. [Please read the GDS Way for details on
Git best practice][gds-way-git]. This includes how to write good commit messages, use
`git rebase` for local branches and `git merge --no-ff` for merges, as well as using
`git push --force-with-lease` instead of `git push -f`.

Our source code is stored on GitHub at
[https://github.com/NHSDigital/open-data-standards][open-data-standards]. Pull
requests into `main` require at least one approved review.

### Markdown

Local links can be written as normal, but external links should be referenced at the
bottom of the Markdown file for clarity. For example:

```md
Use a local link to reference the [`README.md`](./README.md) file, but an external link
for [GOV.UK][gov-uk].

[gov-uk]: https://www.gov.uk/
```


[code-of-conduct]: ./CODE_OF_CONDUCT.md
[email]: mailto:datascience@nhs.net
[gds-way-git]: https://gds-way.cloudapps.digital/standards/source-code.html
[open-data-standards]: [https://github.com/NHSDigital/open-data-standards
