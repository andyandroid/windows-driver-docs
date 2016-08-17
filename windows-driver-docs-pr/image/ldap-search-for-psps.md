---
title: LDAP Search for PSPs
description: LDAP Search for PSPs
MS-HAID:
- 'dsm\_des\_tut\_558584a7-98bc-4528-9718-9efa0a110fb1.xml'
- 'image.ldap\_search\_for\_psps'
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: c93b0c0f-eb46-4740-a5af-6a1ccaa6ccf9
---

# LDAP Search for PSPs


Use LDAP Search to complete the search for PSPs.

The following shows a typical LDAP Search:

```
     LDAP Search Request
     Scope : SingleLevel
     baseObject : CN=PSPs,CN=System,[defaultNamingContext]
     filter: (objectClass = msImagingPostScanProcess)
     attributes:
          Item: displayName 
          Etc....
```

For more information about LDAP Search, see [ldap\_search Function](http://go.microsoft.com/fwlink/p/?linkid=154081).

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20LDAP%20Search%20for%20PSPs%20%20RELEASE:%20%288/17/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



