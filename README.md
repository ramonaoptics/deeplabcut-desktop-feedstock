About deeplabcut-desktop
========================

Home: https://github.com/ramonaoptics/deeplabcut-desktop-feedstock

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/ramonaoptics/deeplabcut-desktop-feedstock/blob/master/LICENSE.txt)

Summary: Desktop launchers for DeepLabCut when installed in linux

This will create a desktop launcher for DeepLabCut. The launcher will override
other installed DeepLabCut launchers.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/deeplabcut-desktop-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/deeplabcut-desktop-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-deeplabcut--desktop-green.svg)](https://anaconda.org/ramonaoptics/deeplabcut-desktop) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/deeplabcut-desktop.svg)](https://anaconda.org/ramonaoptics/deeplabcut-desktop) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/deeplabcut-desktop.svg)](https://anaconda.org/ramonaoptics/deeplabcut-desktop) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/deeplabcut-desktop.svg)](https://anaconda.org/ramonaoptics/deeplabcut-desktop) |

Installing deeplabcut-desktop
=============================

Installing `deeplabcut-desktop` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
conda config --set channel_priority strict
```

Once the `ramonaoptics` channel has been enabled, `deeplabcut-desktop` can be installed with:

```
conda install deeplabcut-desktop
```

It is possible to list all of the versions of `deeplabcut-desktop` available on your platform with:

```
conda search deeplabcut-desktop --channel ramonaoptics
```




Updating deeplabcut-desktop-feedstock
=====================================

If you would like to improve the deeplabcut-desktop recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/deeplabcut-desktop-feedstock are
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

* [@hmaarrfk](https://github.com/hmaarrfk/)

