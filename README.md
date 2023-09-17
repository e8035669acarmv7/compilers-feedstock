About compilers-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/compilers-feedstock/blob/main/LICENSE.txt)


About compilers
---------------

Home: https://conda-forge.org

Package license: BSD-3-Clause

Summary: A metapackage to obtain compilers

This package is a generic way to obtain the compilers for your system
that conda-forge used to compile its ecosystem. These compilers are,
therefore, guaranteed to be ABI compatible with the conda packages
you have installed.

These compiler metapackages are a convenience ONLY for users.
Do NOT use these packages as a build or host dependencies in other
recipes.  Use the compiler Jinja template function instead.
For C++ for example, use compiler('cxx') as usual.


About c-compiler
----------------

Home: https://conda-forge.org

Package license: BSD

Summary: A metapackage to obtain a C compiler

This package is a generic way to obtain the C compiler for your system
that conda-forge used to compile its ecosystem.  This compiler is,
therefore, guaranteed to be ABI compatible with the conda packages
you have installed.

This compiler metapackage is a convenience ONLY for users.
Do NOT use this package as a build or host dependency in other
recipes.  Use the Jinja template function compiler('c') instead.


About cxx-compiler
------------------

Home: https://conda-forge.org

Package license: BSD

Summary: A metapackage to obtain a C++ compiler

This package is a generic way to obtain the C++ compiler for your system
that conda-forge used to compile its ecosystem.  This compiler is,
therefore, guaranteed to be ABI compatible with the conda packages
you have installed.

This compiler metapackage is a convenience ONLY for users.
Do NOT use this package as a build or host dependency in other
recipes.  Use the Jinja template function compiler('cxx') instead.


About fortran-compiler
----------------------

Home: https://conda-forge.org

Package license: BSD

Summary: A metapackage to obtain a Fortran compiler

This package is a generic way to obtain the Fortran compiler for your
system that conda-forge used to compile its ecosystem.  This compiler
is, therefore, guaranteed to be ABI compatible with the conda packages
you have installed.

This compiler metapackage is a convenience ONLY for users.
Do NOT use this package as a build or host dependency in other
recipes.  Use the Jinja template function compiler('fortran') instead.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6168&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/compilers-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_armv7l</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6168&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/compilers-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_armv7l_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-c--compiler-green.svg)](https://anaconda.org/e8035669acarmv7/c-compiler) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/c-compiler.svg)](https://anaconda.org/e8035669acarmv7/c-compiler) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/c-compiler.svg)](https://anaconda.org/e8035669acarmv7/c-compiler) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/c-compiler.svg)](https://anaconda.org/e8035669acarmv7/c-compiler) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-compilers-green.svg)](https://anaconda.org/e8035669acarmv7/compilers) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/compilers.svg)](https://anaconda.org/e8035669acarmv7/compilers) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/compilers.svg)](https://anaconda.org/e8035669acarmv7/compilers) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/compilers.svg)](https://anaconda.org/e8035669acarmv7/compilers) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cxx--compiler-green.svg)](https://anaconda.org/e8035669acarmv7/cxx-compiler) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/cxx-compiler.svg)](https://anaconda.org/e8035669acarmv7/cxx-compiler) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/cxx-compiler.svg)](https://anaconda.org/e8035669acarmv7/cxx-compiler) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/cxx-compiler.svg)](https://anaconda.org/e8035669acarmv7/cxx-compiler) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-fortran--compiler-green.svg)](https://anaconda.org/e8035669acarmv7/fortran-compiler) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/fortran-compiler.svg)](https://anaconda.org/e8035669acarmv7/fortran-compiler) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/fortran-compiler.svg)](https://anaconda.org/e8035669acarmv7/fortran-compiler) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/fortran-compiler.svg)](https://anaconda.org/e8035669acarmv7/fortran-compiler) |

Installing compilers
====================

Installing `compilers` from the `e8035669acarmv7` channel can be achieved by adding `e8035669acarmv7` to your channels with:

```
conda config --add channels e8035669acarmv7
conda config --set channel_priority strict
```

Once the `e8035669acarmv7` channel has been enabled, `c-compiler, compilers, cxx-compiler, fortran-compiler` can be installed with `conda`:

```
conda install c-compiler compilers cxx-compiler fortran-compiler
```

or with `mamba`:

```
mamba install c-compiler compilers cxx-compiler fortran-compiler
```

It is possible to list all of the versions of `c-compiler` available on your platform with `conda`:

```
conda search c-compiler --channel e8035669acarmv7
```

or with `mamba`:

```
mamba search c-compiler --channel e8035669acarmv7
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search c-compiler --channel e8035669acarmv7

# List packages depending on `c-compiler`:
mamba repoquery whoneeds c-compiler --channel e8035669acarmv7

# List dependencies of `c-compiler`:
mamba repoquery depends c-compiler --channel e8035669acarmv7
```




Updating compilers-feedstock
============================

If you would like to improve the compilers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`e8035669acarmv7` channel, whereupon the built conda packages will be available for
everybody to install and use from the `e8035669acarmv7` channel.
Note that all branches in the conda-forge/compilers-feedstock are
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

* [@chrisburr](https://github.com/chrisburr/)
* [@duncanmmacleod](https://github.com/duncanmmacleod/)
* [@isuruf](https://github.com/isuruf/)
* [@scopatz](https://github.com/scopatz/)

