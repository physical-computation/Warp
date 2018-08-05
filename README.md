Warp
====
Repository for the hardware and firmware of the University of Cambridge Warp hardware platform.

The correct way to clone this repository to get the hardware and firmware submodules is:

	git clone --recursive git@github.com:physical-computation/Warp.git

To update all submodules

	git pull --recurse-submodules
	git submodule update --remote --recursive

If you forgot to clone with `--recursive`, and end up with empty submodule directories, you can remedy this with

	git submodule update --init
