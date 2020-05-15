# yk-k1
youku TVbox

## dts for Linux/arm 4.4.55 kernel

export ARCH=arm

export CROSS_COMPILE=../arm-eabi-4.8/bin/arm-eabi- dtbs

make rockchip_linux_defconfig

make 0neo-rk3288.img

## This manual is for the development of linux on RK3288 board.
http://developer.t-firefly.com/thread-12393-1-1.html


