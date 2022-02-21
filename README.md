# 👋 Hi there, I'm Claudio Jolowicz

I maintain these open-source projects:

<!-- [[[cog

repos = [
    "cjolowicz/cookiecutter-hypermodern-python",
]

for repo in repos:
    org, _, package = repo.partition("/")
    entry = f"""\
- [{package}](https://github.com/{repo}) &mdash;
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  ![GitHub stars](https://img.shields.io/github/stars/{repo}?style=flat-square)
"""
    cog.out(entry)

repos = [
    "theacodes/nox",
    "cjolowicz/nox-poetry",
    "cjolowicz/retrocookie",
]

for repo in repos:
    org, _, package = repo.partition("/")
    entry = f"""\
- [{package}](https://github.com/{repo}) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/{package}?style=flat-square)](https://pypi.org/project/{package})
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/{package}?style=flat-square)](https://pypistats.org/packages/{package})
"""
    cog.out(entry)

]]] -->
- [cookiecutter-hypermodern-python](https://github.com/cjolowicz/cookiecutter-hypermodern-python) &mdash;
  ![GitHub last commit](https://img.shields.io/github/last-commit/cjolowicz/cookiecutter-hypermodern-python?logo=python&style=flat-square)
  ![GitHub stars](https://img.shields.io/github/stars/cjolowicz/cookiecutter-hypermodern-python?style=flat-square)
- [nox](https://github.com/theacodes/nox) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/nox?style=flat-square)](https://pypi.org/project/nox)
  ![GitHub last commit](https://img.shields.io/github/last-commit/theacodes/nox?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/nox?style=flat-square)](https://pypistats.org/packages/nox)
- [nox-poetry](https://github.com/cjolowicz/nox-poetry) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/nox-poetry?style=flat-square)](https://pypi.org/project/nox-poetry)
  ![GitHub last commit](https://img.shields.io/github/last-commit/cjolowicz/nox-poetry?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/nox-poetry?style=flat-square)](https://pypistats.org/packages/nox-poetry)
- [retrocookie](https://github.com/cjolowicz/retrocookie) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/retrocookie?style=flat-square)](https://pypi.org/project/retrocookie)
  ![GitHub last commit](https://img.shields.io/github/last-commit/cjolowicz/retrocookie?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/retrocookie?style=flat-square)](https://pypistats.org/packages/retrocookie)
<!-- [[[end]]] -->

## Contributions

I have contributed to these open-source projects, among others:

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
- [{package}]({url}) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/{package}?style=flat-square)](https://pypi.org/project/{package})
  ![GitHub last commit](https://img.shields.io/github/last-commit/{repo}?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/{package}?style=flat-square)](https://pypistats.org/packages/{package})
"""
    cog.out(entry)

]]] -->
- [nox](https://github.com/theacodes/nox/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/nox?style=flat-square)](https://pypi.org/project/nox)
  ![GitHub last commit](https://img.shields.io/github/last-commit/theacodes/nox?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/nox?style=flat-square)](https://pypistats.org/packages/nox)
- [pyenv](https://github.com/pyenv/pyenv/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/pyenv?style=flat-square)](https://pypi.org/project/pyenv)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pyenv/pyenv?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/pyenv?style=flat-square)](https://pypistats.org/packages/pyenv)
- [virtualenv](https://github.com/pypa/virtualenv/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/virtualenv?style=flat-square)](https://pypi.org/project/virtualenv)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pypa/virtualenv?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/virtualenv?style=flat-square)](https://pypistats.org/packages/virtualenv)
- [click](https://github.com/pallets/click/pull/1582/commits/b38cb0e2b1372c933ea42975632ee5792cef08cf) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/click?style=flat-square)](https://pypi.org/project/click)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pallets/click?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/click?style=flat-square)](https://pypistats.org/packages/click)
- [cookiecutter](https://github.com/cookiecutter/cookiecutter/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/cookiecutter?style=flat-square)](https://pypi.org/project/cookiecutter)
  ![GitHub last commit](https://img.shields.io/github/last-commit/cookiecutter/cookiecutter?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/cookiecutter?style=flat-square)](https://pypistats.org/packages/cookiecutter)
- [cruft](https://github.com/cruft/cruft/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/cruft?style=flat-square)](https://pypi.org/project/cruft)
  ![GitHub last commit](https://img.shields.io/github/last-commit/cruft/cruft?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/cruft?style=flat-square)](https://pypistats.org/packages/cruft)
- [pygit2](https://github.com/libgit2/pygit2/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/pygit2?style=flat-square)](https://pypi.org/project/pygit2)
  ![GitHub last commit](https://img.shields.io/github/last-commit/libgit2/pygit2?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/pygit2?style=flat-square)](https://pypistats.org/packages/pygit2)
- [tomlkit](https://github.com/sdispater/tomlkit/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/tomlkit?style=flat-square)](https://pypi.org/project/tomlkit)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sdispater/tomlkit?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/tomlkit?style=flat-square)](https://pypistats.org/packages/tomlkit)
- [typeguard](https://github.com/agronholm/typeguard/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/typeguard?style=flat-square)](https://pypi.org/project/typeguard)
  ![GitHub last commit](https://img.shields.io/github/last-commit/agronholm/typeguard?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/typeguard?style=flat-square)](https://pypistats.org/packages/typeguard)
- [mypy](https://github.com/python/mypy/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/mypy?style=flat-square)](https://pypi.org/project/mypy)
  ![GitHub last commit](https://img.shields.io/github/last-commit/python/mypy?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/mypy?style=flat-square)](https://pypistats.org/packages/mypy)
- [hypothesis](https://github.com/HypothesisWorks/hypothesis/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/hypothesis?style=flat-square)](https://pypi.org/project/hypothesis)
  ![GitHub last commit](https://img.shields.io/github/last-commit/HypothesisWorks/hypothesis?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/hypothesis?style=flat-square)](https://pypistats.org/packages/hypothesis)
- [pluggy](https://github.com/pytest-dev/pluggy/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/pluggy?style=flat-square)](https://pypi.org/project/pluggy)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pytest-dev/pluggy?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/pluggy?style=flat-square)](https://pypistats.org/packages/pluggy)
- [mdit-py-plugins](https://github.com/executablebooks/mdit-py-plugins/commits?author=cjolowicz) &mdash;
  [![PyPI](https://img.shields.io/pypi/v/mdit-py-plugins?style=flat-square)](https://pypi.org/project/mdit-py-plugins)
  ![GitHub last commit](https://img.shields.io/github/last-commit/executablebooks/mdit-py-plugins?logo=python&style=flat-square)
  [![PyPI - Downloads](https://img.shields.io/pypi/dm/mdit-py-plugins?style=flat-square)](https://pypistats.org/packages/mdit-py-plugins)
<!-- [[[end]]] -->

*Follow the links to see the commits I authored for these projects.*

## Writing

- [Hypermodern Python](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/) 2020-01-01
- [Incremental Docker builds for monolithic codebases](https://cjolowicz.github.io/posts/incremental-docker-builds-for-monolithic-codebases/) 2019-05-23

## Contact

Reach me on [Twitter], on [LinkedIn], or at mail (at) claudiojolowicz.com.

[Twitter]: https://twitter.com/cjolowicz
[LinkedIn]: https://linkedin.com/in/cjolowicz

<img align="left" alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=cjolowicz&show_icons=true&hide_border=true" />
