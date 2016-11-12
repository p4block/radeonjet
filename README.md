# radeonjet-cli
A simple AMDGPU overclocking tool for the command line.

Compatible with Tonga, Fiji and Polaris GPUs under Linux 4.8.

Currently in development!

This project aims to become the cli backend for a graphical GPU overclocking tool.

## Usage examples:

radeonjet get core
	Will return the current core clock

radeonjet get memory table
	Outputs all the memory frequencies available, and which one is being used

radeonjet set core-oc 5
	Will set the core overclock to +5%

radeonjet get pcie
	Gets the current PCIe bandwidth

