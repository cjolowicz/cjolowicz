# 👋 Hi I'm Claudio Jolowicz

I maintain the following open-source projects:

<!-- [[[cog

repos = [
    "cjolowicz/cookiecutter-hypermodern-python",
    "cjolowicz/hypermodern-python",
]

for repo in repos:
    org, _, package = repo.partition("/")
    entry = f"""\
- [{package}](https://github.com/{repo})
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  ![GitHub stars](https://img.shields.io/github/stars/{repo}?style=social&style=flat-square)
"""
    cog.out(entry)

repos = [
    "theacodes/nox"
    "cjolowicz/nox-poetry",
    "cjolowicz/retrocookie",
]

for repo in repos:
    org, _, package = repo.partition("/")
    entry = f"""\
- [{package}](https://github.com/{repo}) --
  [![PyPI](https://img.shields.io/pypi/v/{package}?style=flat-square)](https://pypi.org/project/{package})
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/{package}?style=flat-square)](https://pypistats.org/packages/{package})
"""
    cog.out(entry)

]]] -->
<!-- [[[end]]] -->

## Contributions

I have contributed to the following open-source projects, among others:

<!-- [[[cog

repos = [
    "theacodes/nox",
    "pyenv/pyenv",
    "pypa/virtualenv",
    "pallets/click",
    "cookiecutter/cookiecutter",
    "cruft/cruft",
    "libgit2/pygit2",
    "sdispater/tomlkit",
    "agronholm/typeguard",
    "python/mypy",
    "HypothesisWorks/hypothesis",
    "pytest-dev/pluggy",
    "executablebooks/mdit-py-plugins",
]

for repo in repos:
    org, _, package = repo.partition("/")

    if package == "click":
        url = "https://github.com/pallets/click/pull/1582/commits/b38cb0e2b1372c933ea42975632ee5792cef08cf"
    else:
        url = f"https://github.com/{org}/{package}/commits?author=cjolowicz"

    entry = f"""\
- [{package}]({url}) --
  [![PyPI](https://img.shields.io/pypi/v/{package}?style=flat-square)](https://pypi.org/project/{package})
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/{package}?style=flat-square)](https://pypistats.org/packages/{package})
"""
    cog.out(entry)

]]] -->
<!-- [[[end]]] -->

*In the list above, package names link to commits I authored.*

## Writing

- [Hypermodern Python](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/) 2020-01-01
- [Incremental Docker builds for monolithic codebases](https://cjolowicz.github.io/posts/incremental-docker-builds-for-monolithic-codebases/) 2019-05-23

## Contact

Reach me on [Twitter], on [LinkedIn], or at mail (at) claudiojolowicz.com.

[Twitter]: https://twitter.com/cjolowicz
[LinkedIn]: https://linkedin.com/in/cjolowicz
