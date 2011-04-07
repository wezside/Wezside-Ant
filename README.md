Wezside Ant Scripts
====================

This project is intended to be used as a submodule to compile the Wezside Toolkit however 
the individual ant files can be used as standalone. Simply use subant to call the build files with the correct parameters.  

	git submodule init 
	git submodule add git@github.com:wezside/Wezside-Ant.git ./
	git submodule update 
	

The root build script will do the following:

1. Increment version numbers 
2. Compile [Toolkit](https://github.com/wezside/Toolkit) SWC
3. Git Add, Commit, Push to remote repo
4. Copy Compiled SWC to [Toolkit-Components](https://github.com/wezside/Toolkit-Components)
5. Compile Toolkit-Components SWC
6. Git Add, Commit, Push to remote repo
