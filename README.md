```C
#include <wdm.h>

VOID DirverUnload(PDRIVER_OBJECT pDriverObject) {
    UNREFERENCED_PARAMETER(pDriverObject);
}

NTSTATUS DriverEntry(IN PDRIVER_OBJECT pDriverObject, IN PUNICODE_STRING pRegistryPath) {
    UNREFERENCED_PARAMETER(pDriverObject);
    UNREFERENCED_PARAMETER(pRegistryPath);

    DbgPrint("Hello World\n");

    pDriverObject->DriverUnload = DirverUnload;

    return STATUS_SUCCESS;
}
```



