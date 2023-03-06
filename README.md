#暫時無法使用

# 使用
1. Fork這個倉庫
2. 進入`Actions`的畫面
3. 找到`Build Android Kernel`並點下去
4. 找到`Run workflow`
5. 修改內容後點底下的`Run workflow`  
> 只支援64Bit，32Bit該消失了

# 說明
### Repository URL  
填入內核的倉庫網址  

### Branch  
填入內核所使用的分支  

### Device defconfig  
填入要使用的配置文件檔名，如果在vendor底下，需加入`vendor/`，例如：`vendor/sm8150-perf_defconfig`  

### Clang version  
填入編譯時使用的Clang版本  
參考：https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+/refs/heads/master

# 其他
本人是新手兼學生，不會任何的程式語言，也不會英文，不然這篇其實想用英文打出來。這個項目完全出於興趣，翻了GitHub的文檔，花了好幾天才搞出來的，之後再看看還有什麼可以改。

# 感謝
- [KernelSU_Action](https://github.com/xiaoleGun/KernelSU_Action)
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3)
