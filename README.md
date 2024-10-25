About html5lib-modern-feedstock
===============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/html5lib-modern-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/ashleysommer/html5lib-modern

Package license: MIT

Summary: Python 3 version of html5lib-python HTML parser based on the WHATWG HTML specification

Python 3 version of the standards-compliant library for parsing and serializing HTML documents and fragments in Python.
This is a fork of the html5lib project https://github.com/html5lib/html5lib-python
with the intention to make this new release available for users without the overhead of python2.7 support, or the dependency on the six library.
This release is a snapshot of the v1.2-dev codebase plus the addition of the "remove python 2.7" work and the "remove six" work. This version of html5lib works only on Python 3.8 and newer.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=23782&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/html5lib-modern-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-html5lib--modern-green.svg)](https://anaconda.org/conda-forge/html5lib-modern) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/html5lib-modern.svg)](https://anaconda.org/conda-forge/html5lib-modern) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/html5lib-modern.svg)](https://anaconda.org/conda-forge/html5lib-modern) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/html5lib-modern.svg)](https://anaconda.org/conda-forge/html5lib-modern) |

Installing html5lib-modern
==========================

Installing `html5lib-modern` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `html5lib-modern` can be installed with `conda`:

```
conda install html5lib-modern
```

or with `mamba`:

```
mamba install html5lib-modern
```

It is possible to list all of the versions of `html5lib-modern` available on your platform with `conda`:

```
conda search html5lib-modern --channel conda-forge
```

or with `mamba`:

```
mamba search html5lib-modern --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search html5lib-modern --channel conda-forge

# List packages depending on `html5lib-modern`:
mamba repoquery whoneeds html5lib-modern --channel conda-forge

# List dependencies of `html5lib-modern`:
mamba repoquery depends html5lib-modern --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating html5lib-modern-feedstock
==================================

If you would like to improve the html5lib-modern recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/html5lib-modern-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@rxm7706](https://github.com/rxm7706/)

