About pykafka
=============

Home: http://github.com/parsely/pykafka

Package license: Apache-2.0

Feedstock license: BSD 3-Clause

Summary: Apache Kafka client for Python; high-level & low-level consumer/producer, with great performance

PyKafka is a cluster-aware Kafka>=0.8.2 client for Python. It includes
Python implementations of Kafka producers and consumers, which are
optionally backed by a C extension built on librdkafka, and runs under
Python 2.7+, Python 3.4+, and PyPy.

PyKafka’s primary goal is to provide a similar level of abstraction to
the JVM Kafka client using idioms familiar to Python programmers and
exposing the most Pythonic API possible.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=linux&configuration=linux_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=osx&configuration=osx_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_c_compilervs2015python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=win&configuration=win_c_compilervs2015python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_c_compilervs2015python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=59&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pykafka-feedstock?branchName=master&jobName=win&configuration=win_c_compilervs2015python3.7" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pykafka-green.svg)](https://anaconda.org/nsls2forge/pykafka) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/pykafka.svg)](https://anaconda.org/nsls2forge/pykafka) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/pykafka.svg)](https://anaconda.org/nsls2forge/pykafka) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/pykafka.svg)](https://anaconda.org/nsls2forge/pykafka) |

Installing pykafka
==================

Installing `pykafka` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `pykafka` can be installed with:

```
conda install pykafka
```

It is possible to list all of the versions of `pykafka` available on your platform with:

```
conda search pykafka --channel nsls2forge
```




Updating pykafka-feedstock
==========================

If you would like to improve the pykafka recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/pykafka-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@emmett9001](https://github.com/emmett9001/)
* [@mrocklin](https://github.com/mrocklin/)

