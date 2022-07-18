# Clone + build command
```
git clone https://github.com/aryankaran/kernel_xiaomi_onclite -b orangefox kernel/xiaomi/onclite --depth 1 ;\
git clone https://github.com/aryan-karan/orangefox-dt-onclite -b twrp-12.1 device/xiaomi/onclite ;\
export USE_CCACHE=1 ;\
export CCACHE_EXEC=`which ccache` ;\
. build/envsetup.sh ;\
lunch twrp_onclite-eng ;\
mka recoveryimage

```

##### It's use kernel with compiled directly from source

```
https://github.com/aryankaran/kernel_xiaomi_onclite/tree/orangefox
```
