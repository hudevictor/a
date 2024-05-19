# Project Kernel Download Instructions

## 1. Download Kernel

To download the kernel for Fleet, perform the following steps:

```bash
mkdir android-kernel
cd android-kernel
repo init -u https://android.googlesource.com/kernel/manifest -b android-msm-crosshatch-4.9-android10
repo sync
cd build/
git reset --hard 20e4a3abc406aaf9a25903f8c4b7e4c467fbc09e # To use the traditional compilation method
```
## 2. Download Kernel

To download the kernel for Fleet, perform the following steps:

```bash
mkdir android-kernel
cd android-kernel
repo init -u https://android.googlesource.com/kernel/manifest -b android-msm-crosshatch-4.9-android10
repo sync
cd build/
git reset --hard 20e4a3abc406aaf9a25903f8c4b7e4c467fbc09e # To use the traditional compilation method
