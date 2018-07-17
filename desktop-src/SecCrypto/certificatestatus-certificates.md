---
Description: Sets or retrieves the collection of certificates that can be used to build the certificate chain.
ms.assetid: cdf378f9-0d71-4dd9-93cc-85f09a51c5fc
title: CertificateStatus.Certificates property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CertificateStatus.Certificates
api_type: 
- COM
api_location: 
- Capicom.dll
---

# CertificateStatus.Certificates property

\[CAPICOM is a 32-bit only component that is available for use in the following operating systems: Windows Server 2008, Windows Vista, and Windows XP. Instead, use the [**X509ChainStatus Structure**](https://www.bing.com/search?q=**X509ChainStatus+Structure**) in the [**System.Security.Cryptography.X509Certificates**](https://www.bing.com/search?q=**System.Security.Cryptography.X509Certificates**) namespace.\]

The **Certificates** property sets or retrieves the collection of certificates that can be used to build the certificate chain.

## Syntax


```VB
CertificateStatus.Certificates As Certificates
```



## Property value

A [**Certificates**](certificates.md) object that represents the collection of certificates that can be used to build the certificate chain.

## Requirements



|                                  |                                                                                        |
|----------------------------------|----------------------------------------------------------------------------------------|
| End of client support<br/> | Windows Vista<br/>                                                               |
| End of server support<br/> | Windows Server 2008<br/>                                                         |
| Redistributable<br/>       | CAPICOM 2.1 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>                   | <dl> <dt>Capicom.dll</dt> </dl> |



 

 



