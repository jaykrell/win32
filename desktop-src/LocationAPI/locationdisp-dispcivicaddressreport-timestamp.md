---
Description: The date and time when the report was generated.
ms.assetid: b9435384-72e0-42c4-a948-df52621a5ec2
title: LocationDisp.DispCivicAddressReport.Timestamp property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# LocationDisp.DispCivicAddressReport.Timestamp property

\[The Location API object model is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. Instead, to access location from a website, use the [W3C Geolocation API](https://msdn.microsoft.com/library/gg589513). To access location from a desktop application, use the [**Windows.Devices.Geolocation**](https://msdn.microsoft.com/library/windows/apps/br225603) API.\]

The date and time when the report was generated.

This property is read-only.

## Syntax


```JScript
Timestamp = LocationDisp.DispCivicAddressReport.Timestamp
```



## Property value

This property is a read-only **Date**. Time stamps are provided as Coordinated Universal Time (UTC).

## Remarks

Note that scripting languages, such as Microsoft JScript, might require you to perform conversions to other time formats when you display time stamps as strings.

## Examples

For an example of how to use this property, see [A Simple Civic Address Report Example](https://msdn.microsoft.com/library/windows/apps/br225603).

## Requirements



|                                     |                                            |
|-------------------------------------|--------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/> |
| Minimum supported server<br/> | None supported<br/>                  |



 

 



