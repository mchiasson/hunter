<!--- Please check that your pull request satisfy all requirements -->

* I have checked that this pull request contains only
  `.travis.yml`/`appveyor.yml` changes. All other changes send
  to https://github.com/ruslo/hunter. **[Yes|No]**

* I have checked that no toolchains removed from CI configs, they are commented
  out instead so other developers can enable them back easily and to simplify
  merge conflict resolution. **[Yes|No]**

* I have checked that for every commented out toolchain there is a link to the
  broken CI build page or to the minimum compiler requirements documentation
  so other developers can figure out what was the problem exactly. **[Yes|No]**

* I have submitted CI configs to https://github.com/cpp-pm/hunter-testing targeting `pkg.template` branch,
  see this merged pull request https://github.com/cpp-pm/hunter-testing/pull/<number>

<!--- Remove next line if there is no corresponding "New package" issue. -->
* My change will resolve this "New package" request: https://github.com/cpp-pm/hunter/issues/<number>

---
<!--- END -->

<!--- Use this part of template if you're updating existing package. Remove the rest. -->
<!--- BEGIN -->

* I've followed [this guide](https://docs.hunter.sh/en/latest/creating-new/update.html)
  step by step carefully. **[Yes|No]**

* I've tested this package remotely and have excluded all broken builds.
  Here is the links to the Travis/AppVeyor with status "All passed":

  * https://ci.appveyor.com/project/<username>/hunter/build/<build-number>
  * https://travis-ci.org/<username>/hunter/builds/<build-number>

<!--- Remove next line if this update doesn't break old toolchains -->
* This update will break few old toolchains.
  They are excluded in this pull request: https://github.com/cpp-pm/hunter-testing/pull/<number>

---
<!--- END -->

<!--- Use this part of template for other type of changes. Remove the rest. -->
<!--- BEGIN -->

* I've checked this [Git style guide](https://0.readthedocs.io/en/latest/git.html). **[Yes|No]**
* I've checked this [CMake style guide](https://0.readthedocs.io/en/latest/cmake.html). **[Yes|No]**
* My change will work with CMake 3.2 (minimum requirement for Hunter). **[Yes|No]**
* I will try to keep this pull request as small as possible and will try not to mix unrelated features. **[Yes|No]**

---
<!--- END -->
