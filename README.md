# RISCV_SoC_TapeOut_Week0
## Tools Installation
### Yosys
```bash
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ cd sudo apt install make
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git\
    graphviz xdot pkg-config python3 libboost-system-dev \
     libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ git submodule update --init
$ make
$ sudo make install
```
![yosys](Images/yosys.png)
### Iverilog
```bash
$ sudo apt-get install iverilog
```
![iverilog](Images/iverilog.png)
### GTKWave
```bash
$ sudo apt install gtkwave
```
![gtkwave](Images/gtkwave_command.png)
![gtkwave](Images/gtkwave_window.png)
