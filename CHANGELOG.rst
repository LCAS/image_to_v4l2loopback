^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package image_to_v4l2loopback
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2020-04-02)
------------------
* new maintainer and install targets
* roslint in travis
* Update README.md
* Building 16.04
* Image transport install
* Need cv bridge
* Updating travis yml
* Changing member variable naming convention
* Now using the latest v4l2loopback source, this node is working again which resolves `#3 <https://github.com/LCAS/image_to_v4l2loopback/issues/3>`_
* Try getting format first, now it is clear where the issue is- may have to fix v4l2loopback itself
* Code style changes, put underscore after class variable
* reformatting, still not clear why all formats result in an ioctl invalid argument failure
* Got rid of compiler warnings
* Ran clang-format on unit test code, made all pass roslint_cpp
* Cleaned up package.xml and CMakeLists.txt, also ran clang-format on source files, next make them pass roslint_cpp
* remove most comments from CMakeLists.txt
* This builds but unable to test due to `#1 <https://github.com/LCAS/image_to_v4l2loopback/issues/1>`_, try rebooting and disabling secure boot or with another computer that doesn't have it on
* Merge branch 'master' of https://github.com/jgoppert/ros-virtual-cam
* Updating build instructions
* Fix build on kinetic.
* Merge pull request `#10 <https://github.com/LCAS/image_to_v4l2loopback/issues/10>`_ from lucasw/master
  `#9 <https://github.com/LCAS/image_to_v4l2loopback/issues/9>`_ use ros params instead of tclap
* `#9 <https://github.com/LCAS/image_to_v4l2loopback/issues/9>`_ use ros params instead of tclap
* ren to not conflict w/ existing pkg
* a few docs and up test coverage
* only testing w/ hydro
* doc gen coverage
* no need
* badge of shame
* /
* no --no-external in 1.10
* path hack?
* touch
* publish coverage?
* bsd-3 license
* try gen coverage
* twks
* run unit tests, rostests use v4l2loopback which cannott be loaded in travis.ci
* cannot load kermal modules in travis https://github.com/travis-ci/travis-ci/issues/2291
* try building v4l2loopback (https://github.com/rtc-io/webrtc-testing-on-travis/blob/master/setup-loopbackvideo.sh#L7)
* no v4l2loopback-utils in precise
* sudo
* no tclap
* travising, `#4 <https://github.com/LCAS/image_to_v4l2loopback/issues/4>`_
* init travis, based on https://github.com/RobotWebTools/mjpeg_server/blob/develop/.travis.yml
* docs
* fixes and tests, closes `#5 <https://github.com/LCAS/image_to_v4l2loopback/issues/5>`_
* nit
* doc
* doc
* init
* Contributors: James Goppert, Lucas Walter, Marc Hanheide, aisch
