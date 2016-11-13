# radeonjet

A simple AMDGPU overclocking tool for the command line.

This project aims to become the cli backend for a graphical GPU overclocking tool, while being itself perfectly functional for the cli enthusiast.

Compatible with Tonga, Fiji and Polaris GPUs under Linux 4.8 thanks to the AMDGPU kernel module.

Currently in development! Syntax may change unexpectedly.

![1](https://i.imgur.com/jsL8uc1.png)

#### Usage examples:

	radeonjet get core

Will return the current core clock


	radeonjet get memory table

Outputs all the memory frequencies available, and which one is being used


	radeonjet set core-oc 5

Will set the core overclock to +5%


	radeonjet get memory-oc

Gets the memory overclock percentage

	
	watch -n 0.5 radeonjet get core table

Combine with the `watch` command to get *almost* realtime statistics
