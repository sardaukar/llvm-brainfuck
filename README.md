# llvm-brainfuck
A ruby Brainfuck compiler that uses llvm to generate a native binary and to execute the brainfuck program in a JIT VM

# Instalation

1. Install llvm35 (`brew install llvm35`)
2. place a symlink on `/usr/local/lib` with `ln -s /usr/local/Cellar/llvm35/3.5.1/lib/llvm-3.5/lib/libLLVM-3.5.1.dylib /usr/local/lib/libLLVM-3.5.1.dylib`
3. you're done!
