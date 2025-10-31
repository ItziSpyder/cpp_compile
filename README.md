# C++ Compile
For begginers like me who find `CMake` or `MakeFile` more tedious than just running a single command when ur entire program is \<20 files anyway for there be a performance difference in compilation.

### Disclaimer
Using this for every single project you build in the future can be considered *bad practice*. Just stick to `Cmake` or `MakeFile`.

### Usage

#### Step 1
Download the `make.exe` file to your project's root folder.

#### Step 2
Run command in terminal (at project root):
```
make
```
^ This command iterates through every nested directory and searches for `.cpp` or `.h` files to compile.

Alternatively, you can also run:
```
make custom_name.exe
```
^ To provide a custom name for your output file

#### Step 3
Yeah you're done. It's really that simple.