This repository uses cxxtest. While cxxtest is included here, you may run into some issues. If you are, first try making the cxxtestgen file executable by running `chmod +x cxxtest/bin/cxxtestgen` in a terminal. If you continue having problems, delete the `cxxtest` folder and try redownloading it:

* Visit the [CxxTest repo](https://github.com/CxxTest/cxxtest/), download, and extract revision a19f85fdf9 into a folder called `cxxtest`.
  * This can be done in a terminal using:
    * `curl -o cxxtest.zip -L https://github.com/CxxTest/cxxtest/archive/a19f85fdf90f97e16d6e3e7e3d2d68c31cd89e3c.zip`
    * `unzip cxxtest.zip`
    * `mv cxxtest-a19f85fdf90f97e16d6e3e7e3d2d68c31cd89e3c cxxtest`
    * `rm cxxtest.zip`
* Move the `cxxtest` folder into your project folder.
