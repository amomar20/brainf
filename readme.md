# Brainf*** interpreter
A simple program for executing brainf*** scripts.

> **⚠ Warning:** Avoid running untrusted scripts when using this interpreter, as it could lead to unintended behavior or security risks.

### Usage

```
brainf path/to/script.bf
```

### Building
This project uses premake5 to build the interpreter. 

**Dependencies**
- premake5
- gmake(linux)
- Visual Studio(windows)
- Xcode(macos)

**Building**

1. Navigate to the root of the repository where the `premake5.lua` file is located.

2. Run the following command(s) based on your environment;

	**Linux**
	
	```
	premake5 gmake
	```
	
	Or 
	
	```
	premake5 gmake2
	```
	
	
	**Windows(Visual Studio)**
	
	```
	premake5 --help
	```
	
	Choose a vs version, eg `vs2019`
	
	```
	premake5 vs2019
	```
	
	**Macos**
	```
	premake5 xcode4
	```

3. Run or open the file generated by premake;
	
	**Linux:** run `make`.
	**Winodws:** open the solution(.sln) file.
	**Macos:** open the .xcodeproj file