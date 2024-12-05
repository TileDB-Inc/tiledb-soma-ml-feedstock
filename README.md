About tiledbsoma-ml-feedstock
=============================

Feedstock license: [BSD-3-Clause](https://github.com/TileDB-Inc/tiledb-soma-ml-feedstock/blob/main/LICENSE.txt)



Package license: MIT

Summary: Machine learning tools for use with tiledbsoma (SOMA PyTorch loaders)

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/TileDB-Inc/CI/_build/latest?definitionId=55&branchName=main">
        <img src="https://dev.azure.com/TileDB-Inc/CI/_apis/build/status/tiledb-soma-ml-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tiledbsoma--ml-green.svg)](https://anaconda.org/tiledb/tiledbsoma-ml) | [![Conda Downloads](https://img.shields.io/conda/dn/tiledb/tiledbsoma-ml.svg)](https://anaconda.org/tiledb/tiledbsoma-ml) | [![Conda Version](https://img.shields.io/conda/vn/tiledb/tiledbsoma-ml.svg)](https://anaconda.org/tiledb/tiledbsoma-ml) | [![Conda Platforms](https://img.shields.io/conda/pn/tiledb/tiledbsoma-ml.svg)](https://anaconda.org/tiledb/tiledbsoma-ml) |

Installing tiledbsoma-ml
========================

Installing `tiledbsoma-ml` from the `tiledb` channel can be achieved by adding `tiledb` to your channels with:

```
conda config --add channels tiledb
conda config --set channel_priority strict
```

Once the `tiledb` channel has been enabled, `tiledbsoma-ml` can be installed with `conda`:

```
conda install tiledbsoma-ml
```

or with `mamba`:

```
mamba install tiledbsoma-ml
```

It is possible to list all of the versions of `tiledbsoma-ml` available on your platform with `conda`:

```
conda search tiledbsoma-ml --channel tiledb
```

or with `mamba`:

```
mamba search tiledbsoma-ml --channel tiledb
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search tiledbsoma-ml --channel tiledb

# List packages depending on `tiledbsoma-ml`:
mamba repoquery whoneeds tiledbsoma-ml --channel tiledb

# List dependencies of `tiledbsoma-ml`:
mamba repoquery depends tiledbsoma-ml --channel tiledb
```




Updating tiledbsoma-ml-feedstock
================================

If you would like to improve the tiledbsoma-ml recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tiledb` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tiledb` channel.
Note that all branches in the TileDB-Inc/tiledbsoma-ml-feedstock are
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

* [@Shelnutt2](https://github.com/Shelnutt2/)
* [@aaronwolen](https://github.com/aaronwolen/)
* [@jdblischak](https://github.com/jdblischak/)
* [@johnkerl](https://github.com/johnkerl/)
* [@ryan-williams](https://github.com/ryan-williams/)

