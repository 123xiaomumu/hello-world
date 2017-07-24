# hello-world
just another respository
admin@admin-PC ~/vlc-2.2.1/win32
$ make
。。。。。。
fatal: Not a git repository: '../../extras/package/win32/../../../.git/'
make  all-am
make[3]: 进入目录“/home/admin/vlc-2.2.1/win32/src”
  CCLD     libvlccore.la
/usr/lib/gcc/i686-w64-mingw32/5.4.0/../../../../i686-w64-mingw32/bin/ld: cannot find -lidn
/usr/lib/gcc/i686-w64-mingw32/5.4.0/../../../../i686-w64-mingw32/bin/ld: cannot find -ldbus-1
collect2: error: ld returned 1 exit status
make[3]: *** [Makefile:2264：libvlccore.la] 错误 1
make[3]: 离开目录“/home/admin/vlc-2.2.1/win32/src”
make[2]: *** [Makefile:1838：all] 错误 2
make[2]: 离开目录“/home/admin/vlc-2.2.1/win32/src”
make[1]: *** [Makefile:2262：all-recursive] 错误 1
make[1]: 离开目录“/home/admin/vlc-2.2.1/win32”
make: *** [Makefile:2147：all] 错误 2
