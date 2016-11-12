# radeonjet-cli

A simple AMDGPU overclocking tool for the command line.

This project aims to become the cli backend for a graphical GPU overclocking tool, while being itself perfectly functional for the cli enthusiast. 

Compatible with Tonga, Fiji and Polaris GPUs under Linux 4.8 thanks to the AMDGPU kernel module. 

Currently in development! Syntax may change unexpectedly.

#### Usage examples:

	radeonjet get core

Will return the current core clock

	radeonjet get memory 

Outputs all the memory frequencies available, and which one is being used

	radeonjet set core-oc 5

Will set the core overclock to +5%

	radeonjet get memory-oc

Gets the memory overclock percentage

