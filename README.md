# Bootlegger

**For davinci | Mi 9T / Redmi K20**

**Includes KernelSU variant**

## Install

- Download **[one of the releases](https://github.com/silvzr/kernel_milk_davinci/releases)**
- Backup your boot.img and dtbo.img
- Flash it via recovery
- Optional: If present, download the KernelSU Manager otherwise do it from the **[official repo](https://github.com/tiann/KernelSU/releases/latest)

## Build

- Fork **[this](https://github.com/silvzr/kernel_milk_davinci/)** repository
- Run Action "CI Build"

## Thanks / Credits
- **[Kenvyra](https://github.com/Kenvyra/android_kernel_xiaomi_sm6150/)**, **[LineageOS](https://github.com/LineageOS/android_kernel_xiaomi_sm6150/)**, **[PixelOS-Devices](https://github.com/PixelOS-Devices/kernel_xiaomi_sm6150/)**, **[Sleepy](https://github.com/itsshashanksp/kernel_xiaomi_sm6150)**, **[DerpFest](https://github.com/DerpFest-Devices/kernel_xiaomi_sm6150/)** and **[MiCode](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/davinci-p-oss)** for the kernel
- **[tiann](https://github.com/tiann/KernelSU/)** for KernelSU and its manager
- **[AMWolfstein](https://github.com/AMWolfstein/action_kernelsu/)** for the build script
- **[SchweGELBin](https://github.com/SchweGELBin/action_kernel_milk_davinci/)** for the improved build script
- **[osm0sis](https://github.com/osm0sis/AnyKernel3/)** for the packaging
- **[ZyCromerZ](https://github.com/ZyCromerZ/Clang/)** for the clang build
- **[llvm](https://github.com/llvm/llvm-project/)** for the compiler/toolchain
- For more credits, visit their repositories

## Add Branch
```
View branches: git branch --all
View upstream: git remote -v
In case of error "fatal: the remote end hung up unexpectedly":
    git config http.postBuffer 524288000
After adding: Add to Readme credits & Add to sync-upstream workflow
```
```
git clone https://github.com/[username]/kernel_milk_davinci.git

git remote add upstream [link].git
git fetch upstream

git checkout -b [new_branchname] upstream/[up_branchname]

git push -u origin [new_branchname]
```
