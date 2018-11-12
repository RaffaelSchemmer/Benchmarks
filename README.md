# Benchmarks

In all machines, execute:
```
sudo apt update
sudo apt install git -y
git clone https://github.com/RaffaelSchemmer/Benchmarks.git
chmod 777 -Rf Benchmarks
cd Benchmarks
sudo script
./script
```

O script irá executar os seguintes benchmarks:

[1] Maximum CPU Speeds

The programs were written with a view towards demonstrating maximum CPU performance executing all types of arithmetic instructions. The benchmark programs use assembler level instructions, including full SIMD operations where appropriate, to simply add values via 1, 2, 3 and 4 registers of 64 bits. Results are in MIPS and MFLOPS.

The Classic Benchmarks possui 4 clássicos programas de benchmark para CPU sendo eles:
-----------
```
Livermore Kernels:

Whetstone Benchmark: 

Dhrystone Benchmarks: Dhrystone é um programa clássico utilizado para mensurar a performance de pico de instruções inteiras (INT), desde o primeiro computador VAX 11/780 construído pela Digital Equipment (DEC). Nesta época, o VAX 11/780 era capaz de obter 1 MIPS (1 milhão de operações inteiras por segundo). Desde então, este benchmark tem sido utilizado como referência pela industria. 

Linpack Benchmark: Linpack é um pacote de software que realiza cálculos de álgebra linear (matricial), sendo muito utilizado desde os anos de 1980 para mensurar o desempenho médio e de pico de computadores paralelos (supercomputadores).
```

This repo was developed to learn basic concepts about computer benchmark and performance evaluation,

All the benchmarks are obtained by roylongbottom.org.uk site's,
