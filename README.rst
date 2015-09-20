64 bit gvim built on AppVeyor
-----------------------------

.. image::
   https://ci.appveyor.com/api/projects/status/t0scst2ne8uwnnlo?svg=true
   :width: 300
   :target: https://ci.appveyor.com/project/maxwell-k/libintl-appveyor
   :alt: Appveyor build status


`Latest download
<https://github.com/maxwell-k/gvim-appveyor/releases/latest>`__

A version of ``gvim`` compiled using 64 bit Windows provided by AppVeyor.

This was originally based on a deprecated `continuous integration`__
deployment for vim. Build logs are available from the `AppVeyor
project`__.

__ https://github.com/vim-jp/vim-ci
__ https://ci.appveyor.com/project/maxwell-k/gvim-appveyor

References
----------

-   `appveyor.yml reference
    <http://www.appveyor.com/docs/appveyor-yml>`__
-   `MSYS2 introduction
    <http://sourceforge.net/p/msys2/wiki/MSYS2%20introduction/>`__
-   `pacman man page
    <https://www.archlinux.org/pacman/pacman.8.html>`__
-   `Support request for MSYS2
    <http://help.appveyor.com/discussions/suggestions/
    615-support-for-msys2>`__
-   `Appveyor issue to add MSYS2
    <https://github.com/appveyor/ci/issues/352>`__
-   `AppVeyor list of installed software
    <http://www.appveyor.com/docs/installed-software#mingw-msys-cygwin>`__
-   `New mirrors for msys2
    <https://github.com/Alexpux/MINGW-packages/issues/702
    #issuecomment-125041746>`__
-   `msys2_shell.bat, profile and other relevant files
    <https://github.com/Alexpux/MSYS2-packages/blob/master/filesystem/>`__
-   `YAML specification <http://yaml.org/spec/1.1/>`__
-   `Workaround for bad file descriptor configure / make problem
    <http://help.appveyor.com/discussions/problems/
    912-problem-building-mono-with-cygwin-inputoutput-redirection
    #comment_34994866>`__
-   `Default value of PATH
    <http://superuser.com/questions/124239/
    what-is-the-default-path-environment-variable-setting-on-fresh-install-of-
    window/335386#335386>`__
-   `make include directive
    <https://www.gnu.org/software/make/manual/html_node/Include.html>`__
-   `Makefile adds itself as a target
    <http://stackoverflow.com/questions/4266281/
    makefile-adds-itself-as-target/4270649#4270649>`__

Git attributes
--------------

The file .git/modules/vim/info/attributes contains::

    *.diff -text
    *.in -text
    *.ok -text
