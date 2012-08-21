cd kernel_dir
export CCOMPILER=~/cm_repo/kernel/samsung/msm7x30/bin/arm-2012.03//bin/arm-none-eabi-
make ARCH=arm CROSS_COMPILE=$CCOMPILER mrproper
cp arch/arm/configs/cyanogenmod_rugby_defconfig .config
make ARCH=arm CROSS_COMPILE=$CCOMPILER
cp .config arch/arm/configs/cyanogenmod_rugby_defconfig
git commit -m "ASDFASDF" .
git push

