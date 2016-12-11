# android_img
`*.img` files of my Android phone. 


My phone is `Philips S616` running `Android 5.1` (`arm64-v8a`). 

```
$ adb shell 'cat /proc/version'
Linux version 3.10.65 (builder2004@server) (gcc version 4.9.x-google 20140827 (mtk-20150409) (GCC) ) #1 SMP PREEMPT Wed Oct 21 14:09:41 CST 2015
$ 
```


I get `boot.img` and `recovery.img` files from my phone with `dirtycow`: 

+ <https://github.com/timwr/CVE-2016-5195>
+ <https://github.com/jcadduono/android_external_dirtycow>
+ <https://github.com/jcadduono/android_external_dirtycow/issues/2>


