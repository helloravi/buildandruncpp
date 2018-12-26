# Building and running a program in four different ways
1. Using X-Code
2. Using commandline commands
3. Using VS Code
4. Using auto tools

## Details of the four ways:
1. [How to use xcode to run a C/C++ program](https://apple.stackexchange.com/questions/112915/how-can-i-compile-and-run-c-in-xcode)
2. `cc main.c` gives a.out
    Run a.out using `./a.out`
3. [Using autotools](https://robots.thoughtbot.com/the-magic-behind-configure-make-make-install)
    `brew install autoconf automake libtool`

    Commands for creating executable:
    
        aclocal # Set up an m4 environment
        autoconf # Generate configure from configure.ac
        automake --add-missing # Generate Makefile.in from Makefile.am
        ./configure # Generate Makefile from Makefile.in
        make distcheck # Use Makefile to build and test a tarball to distribute
        ./helloworld
4. VSCODE
