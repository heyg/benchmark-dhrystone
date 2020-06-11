# benchmark-dhrystone
"DHRYSTONE" Benchmark Program by  Reinhold P. Weicker


compile cmd:
/opt/gcc-linaro-6.3.1-2017.02-x86_64_arm-linux-gnueabihf/bin/arm-linux-gnueabihf-gcc -O2 -march=armv8-a -mtune=cortex-a53 -fomit-frame-pointer -DTIME -DHZ=100 -static dhry_1.c dhry_2.c  -o gcc_dry2
