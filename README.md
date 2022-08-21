```C
#include <wdm.h>

VOID DirverUnload(PDRIVER_OBJECT pDriverObject) {
    UNREFERENCED_PARAMETER(pDriverObject);
}

NTSTATUS DriverEntry(IN PDRIVER_OBJECT pDriverObject, IN PUNICODE_STRING pRegistryPath) {
    UNREFERENCED_PARAMETER(pDriverObject);
    UNREFERENCED_PARAMETER(pRegistryPath);

    KdPrint("Hello world\n");

    DriverObject->DriverUnload = DirverUnload;

    return STATUS_SUCCESS;
}
```
# Reversing engineer --- Good at C C++ ASM and scripting
**Specific skills:**  

Windows driver developing(But now I'm using linux)  

Reversing program(Already forgotten how to unpack VMP :( )  

~~Making cheat~~(CSGO)

# Things I like
Programing UI lib(I've restructured my library for N times)  

Listening music(The weeknd and Jucie WRLD)  

# People's Teacher
**My lua ffi tutorail: [https://space.bilibili.com/1659852340](https://space.bilibili.com/1659852340)**

# My lua project
**CPP project: Helper for using lua ffi [https://github.com/MOxXiE1337/CPP-Project](https://github.com/MOxXiE1337/CPP-Project)**

# 逆向工程师 擅长C C++ ASM 和脚本编写
**擅长的东西**  

Windows系统驱动开发（但是现在在用Linux捏）（有虚拟机）  

逆向程序（已经忘了怎么脱VMP壳了 :( ）  

~~制作外挂程序~~(CSGO)

# 喜欢的东西
做UI库（我已经重构N次了）  

听歌（盆栽和果汁）  

# 人民教师
**我的lua ffi教程: [https://space.bilibili.com/1659852340](https://space.bilibili.com/1659852340)**

# 我的lua项目
**CPP project: 帮助使用ffi的库 [https://github.com/MOxXiE1337/CPP-Project](https://github.com/MOxXiE1337/CPP-Project)**



