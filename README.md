![Logo](logo.jpeg) OpenCL Programming Guide 1.2 Examples
=======================================================================

This project contains all of the source code to the example programs
from the [OpenCL Programming
Guide](http://www.heterogeneouscompute.org/?page_id=5). Instructions
on checking out the source code and building it on various platforms
can be found on the Installation page.

This book is getting old now and I'm pleased to say that we are
working on new version that will cover OpenCL 2.1; more information
soon.

Compiling in Celadon Q
---
1, clone code under Celadon Q's hardware/intel/external/opencl

	git clone git@github.com:feijiang1/opencl-book-samples.git

2, compile

	mmm hardware/intel/external/opencl/opencl-book-samples/

3, push binary and shader

	adb push out/target/product/celadon_tablet/vendor/bin/HelloWorld /vendor/bin/

	adb push hardware/intel/external/opencl/opencl-book-samples/src/Chapter_2/HelloWorld/HelloWorld.cl /vendor/bin/

4, execute

	adb shell

	/vendor/bin/HelloWorld

	You need see "Executed program succesfully" to indicate it is executed successfully.

