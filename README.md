# android_prebuilts_gcc_linux-x86_aarch64_aarch64-linux-gnu-linaro-5.5.0
aarch64 gcc 5.5.0

[root@centos ~]# git clone https://github.com/sbwml/android_prebuilts_gcc_linux-x86_aarch64_aarch64-linux-gnu-linaro-5.5.0.git prebuilts/gcc/linux-x86/aarch64/aarch64-linux-gnu-linaro-5.5.0

BoardConfig.mk
- Del: TARGET_KERNEL_CROSS_COMPILE_PREFIX := aarch64-linux-android-
+ Add: KERNEL_TOOLCHAIN_PREFIX := aarch64-linux-gnu-
