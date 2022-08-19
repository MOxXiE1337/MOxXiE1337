```C
#include <ntddk.h>

VOID DirverUnload(PDRIVER_OBJECT pDriverObject) {
    UNREFERENCED_PARAMETER(pDriverObject);
}

NTSTATUS DriverEntry(IN PDRIVER_OBJECT pDriverObject, IN PUNICODE_STRING pRegistryPath) {
    UNREFERENCED_PARAMETER(pDriverObject);
    UNREFERENCED_PARAMETER(pRegistryPath);

    KdPrint(("Hello world\n"));

    DriverObject->DriverUnload = DirverUnload;

    return STATUS_SUCCESS;
}
```
#Reversing engineer
##Good at C C++ and ASM



