---
Description: Applications use the methods of the IDirectXFileEnumObject interface to cycle through the data objects in the file and to retrieve a data object by its globally unique identifier (GUID) or by its name. Deprecated.
ms.assetid: 9eefda2a-5b17-4330-8245-63a38c1b1469
title: IDirectXFileEnumObject interface
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# IDirectXFileEnumObject interface

Applications use the methods of the IDirectXFileEnumObject interface to cycle through the data objects in the file and to retrieve a data object by its globally unique identifier (GUID) or by its name. Deprecated.

## Members

The **IDirectXFileEnumObject** interface inherits from the [**IUnknown**](https://msdn.microsoft.com/33f1d79a-33fc-4ce5-a372-e08bda378332) interface. **IDirectXFileEnumObject** also has these types of members:

-   [Methods](#methods)

### Methods

The **IDirectXFileEnumObject** interface has these methods.



| Method                                                                     | Description                                                                     |
|:---------------------------------------------------------------------------|:--------------------------------------------------------------------------------|
| [**GetDataObjectById**](idirectxfileenumobject--getdataobjectbyid.md)     | Retrieves the data object that has the specified GUID. Deprecated.<br/>   |
| [**GetDataObjectByName**](idirectxfileenumobject--getdataobjectbyname.md) | Retrieves the data object that has the specified name. Deprecated.<br/>   |
| [**GetNextDataObject**](idirectxfileenumobject--getnextdataobject.md)     | Retrieves the next top-level object in the DirectX file. Deprecated.<br/> |



 

## Remarks

The GUID for the IDirectXFileEnumObject interface is IID\_IDirectXFileEnumObject.

The LPDIRECTXFILEENUMOBJECT type is defined as a pointer to this interface.


```
typedef interface IDirectXFileEnumObject *LPDIRECTXFILEENUMOBJECT;
```



## Requirements



|                    |                                                                                       |
|--------------------|---------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>DXFile.h</dt> </dl>   |
| Library<br/> | <dl> <dt>D3dxof.lib</dt> </dl> |



## See also

<dl> <dt>

[X File Interfaces](dx9-graphics-reference-x-file-interfaces.md)
</dt> </dl>

 

 



