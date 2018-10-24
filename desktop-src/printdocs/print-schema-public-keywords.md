---
Description: This topic is not current. For the most current information, see the Print Schema Specification.
ms.assetid: ff966475-626d-4a48-9349-e60454d47c57
title: Print Schema Public Keywords
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Print Schema Public Keywords

This topic is not current. For the most current information, see the [Print Schema Specification](http://go.microsoft.com/?linkid=7141496).

The following section specifies the public keywords which are defined for the Print Schema.

## Print Schema Public Keywords Usage for Print Capabilities

Keywords specified under PrintCapabilities Public Keywords MAY appear in a Print Capabilities document. For more information on how these keywords interact with PrintCapabilities technology, please refer to [Overview of the PrintCapabilities](overview-of-the-printcapabilities.md) section.

Public keywords specific to PrintTicket SHOULD NOT appear in a PrintCapabilities document.

## Print Schema Public Keywords Usage for PrintTicket

Keywords specified under PrintTicket Public Keywords MAY appear in a PrintTicket. PrintTicket keywords are implemented as a Property element type. For more information on how these keywords interact with PrintTicket technology, please refer to [Configuration Information Not Related to PrintCapabilities](configuration-information-not-related-to-printcapabilities.md) section.

Keywords specified under PrintCapabilities Public Keywords MAY appear in a PrintTicket depending on the implementation of the PrintTicket in an application and/or driver. This provides selections for device attributes defined in the PrintCapabilities document. For more information on the interaction between PrintCapabilities keywords and the PrintTicket, please refer to [Purpose of the PrintTicket](purpose-of-the-printticket.md) section.

## Related topics

<dl> <dt>

[Print Schema Specification](http://go.microsoft.com/?linkid=7141496)
</dt> </dl>

 

 


