# RISC-V_SOC_TASK_0
# Day 0
The Task of Day 0 includes the Tools installation required for the RISC V SOC Programme
# Tools installed:
- Yosys
- Iverilog
- GTKWave
These are installed in *Ubuntu 24.04.3* (latest) using *Oracle Virtual Machine 7.2.2*
# Ubuntu VirtualMachine
- **Version** --> 24.04.3
- **RAM** --> 10 GB
- **HDD** --> 50 GB
- **CPU** --> 4
# Yosys
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make              
$ sudo apt-get install build-essential clang bison flex \ libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev \ libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ git submodule update --init --recursive
$ make 
$ sudo make install
```
![Yosys](Images/Yosys_done.jpg)
