
<img src="https://raw.githubusercontent.com/vyperlang/vyper/master/logo/vyper-logo-transparent.svg?sanitize=true" alt="" width="110">

[![Build Status](https://github.com/vyperlang/vyper/workflows/Test/badge.svg)](https://github.com/vyperlang/vyper/actions)
[![Documentation Status](https://readthedocs.org/projects/vyper/badge/?version=latest)](http://vyper.readthedocs.io/en/latest/?badge=latest "ReadTheDocs")
[![Discord](https://img.shields.io/discord/591914197219016707.svg?label=%23vyper)](https://discord.gg/abJEARdx3Q)

[![PyPI](https://badge.fury.io/py/vyper.svg)](https://pypi.org/project/vyper "PyPI")
[![Docker](https://images.microbadger.com/badges/version/vyperlang/vyper.svg)](https://hub.docker.com/r/vyperlang/vyper "DockerHub")

[![Coverage Status](https://codecov.io/gh/vyperlang/vyper/branch/master/graph/badge.svg)](https://codecov.io/gh/vyperlang/vyper "Codecov")
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/vyperlang/vyper.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/vyperlang/vyper/context:python)

# Getting Started
See [Installing Vyper](http://vyper.readthedocs.io/en/latest/installing-vyper.html) to install vyper.
See [Tools and Resources](https://github.com/vyperlang/vyper/wiki/Vyper-tools-and-resources) for an additional list of framework and tools with vyper support.
See [Documentation](http://vyper.readthedocs.io/en/latest/index.html) for the documentation and overall design goals of the Vyper language.

See [Learn.Vyperlang.org](https://learn.vyperlang.org/) for **learning Vyper by building a Pokémon game**. 

**Note: Vyper is beta software, use with care**

# Installation
See the [Vyper documentation](https://vyper.readthedocs.io/en/latest/installing-vyper.html)
for build instructions.

# Compiling a contract
To compile a contract, use:
```bash
vyper your_file_name.vy
```

There is also an [online compiler](https://vyper.online/) available you can use to experiment with
the language and compile to ``bytecode`` and/or ``IR``.

**Note: While the vyper version of the online compiler is updated on a regular basis it might
be a bit behind the latest version found in the master branch of this repository.**

## Testing (using pytest)

(Complete [installation steps](https://vyper.readthedocs.io/en/latest/installing-vyper.html) first.)

```bash
python setup.py test
```

# Contributing
* See Issues tab, and feel free to submit your own issues
* Add PRs if you discover a solution to an existing issue
* For further discussions and questions, post in [Discussions](https://github.com/vyperlang/vyper/discussions) or talk to us on [Discord](https://discord.gg/abJEARdx3Q)
* For more information, see [Contributing](http://vyper.readthedocs.io/en/latest/contributing.html)
