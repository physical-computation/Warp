Warp
====
This is the top-level repository for the hardware and firmware of the University of Cambridge Warp hardware platform. Two other repositories, [`Warp-hardware`](https://github.com/physical-computation/Warp-hardware) and [`Warp-firmware`](https://github.com/physical-computation/Warp-firmware), contain the hardware design and software/firmware respectively. These repositories are included here as git submodules.

## Cloning the Repository 
The correct way to clone this repository to get the hardware and firmware submodules is:

	git clone --recursive git@github.com:physical-computation/Warp.git

To update all submodules

	git pull --recurse-submodules
	git submodule update --remote --recursive

If you forgot to clone with `--recursive`, and end up with empty submodule directories, you can remedy this with

	git submodule update --init

## Acknowledgements
This research is supported by an Alan Turing Institute award TU/B/000096 under EPSRC grant EP/N510129/1, by Royal Society grant RG170136, and by EPSRC grants EP/P001246/1 and EP/R022534/1.
