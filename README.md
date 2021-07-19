# RE2AC
少女前线反和谐补丁，对应包名`com.sunborn.girlsfrontline.cn`

## 依赖
补丁依赖[Riru](https://github.com/RikkaApps/Riru/releases/latest)，使用前请先安装。

## 使用
在 [Release](https://github.com/0x0194/RE2AC/releases/latest) 中下载压缩包后解压至`/data/adb/modules/`文件夹，并使用`rootexplorer`为`/data/adb/modules/RE2AC/riru/lib/libRE2AC.so`更改SE上下文，从列表中选择为`u:object_r:system_file:s0`即可。  
附带自定义名称，下载`Name.json`放置到`/sdcard/Android/obb/com.sunborn.girlsfrontline.cn`下。其中人形ID可以在`gun.json`中查找，开头为`gun-10000xxx`
