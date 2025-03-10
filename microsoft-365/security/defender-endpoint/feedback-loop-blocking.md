---
title: Feedback-loop blocking
description: Feedback-loop blocking, also called rapid protection, is part of behavioral blocking and containment capabilities in Microsoft Defender for Endpoint
keywords: behavioral blocking, rapid protection, feedback blocking, Microsoft Defender for Endpoint
ms.pagetype: security
author: denisebmsft
ms.author: deniseb
manager: dansimp
ms.reviewer: shwetaj
audience: ITPro
ms.topic: article
ms.prod: m365-security
ms.localizationpriority: medium
ms.custom: 
  - next-gen
  - edr
ms.technology: mde
ms.collection: m365-security-compliance
---

# Feedback-loop blocking

[!INCLUDE [Microsoft 365 Defender rebranding](../../includes/microsoft-defender.md)]


**Applies to:**
- [Microsoft Defender for Endpoint](https://go.microsoft.com/fwlink/?linkid=2154037)

## Overview

Feedback-loop blocking, also referred to as rapid protection, is a component of [behavioral blocking and containment capabilities](/microsoft-365/security/defender-endpoint/behavioral-blocking-containment) in [Microsoft Defender for Endpoint](/windows/security/threat-protection/). With feedback-loop blocking, devices across your organization are better protected from attacks. 

## How feedback-loop blocking works

When a suspicious behavior or file is detected, such as by [Microsoft Defender Antivirus](/windows/security/threat-protection/microsoft-defender-antivirus/microsoft-defender-antivirus-in-windows-10), information about that artifact is sent to multiple classifiers. The rapid protection loop engine inspects and correlates the information with other signals to arrive at a decision as to whether to block a file. Checking and classifying artifacts happens quickly. It results in rapid blocking of confirmed malware, and drives protection across the entire ecosystem. 

With rapid protection in place, an attack can be stopped on a device, other devices in the organization, and devices in other organizations, as an attack attempts to broaden its foothold.


## Configuring feedback-loop blocking

If your organization is using Defender for Endpoint, feedback-loop blocking is enabled by default. However, rapid protection occurs through a combination of Defender for Endpoint capabilities, machine learning protection features, and signal-sharing across Microsoft security services. Make sure the following features and capabilities of Defender for Endpoint are enabled and configured:

- [Microsoft Defender for Endpoint baselines](/microsoft-365/security/defender-endpoint/configure-machines-security-baseline)

- [Devices onboarded to Microsoft Defender for Endpoint](/microsoft-365/security/defender-endpoint/onboard-configure)

- [EDR in block mode](/microsoft-365/security/defender-endpoint/edr-in-block-mode)

- [Attack surface reduction](/microsoft-365/security/defender-endpoint/attack-surface-reduction)

- [Next-generation protection](/windows/security/threat-protection/microsoft-defender-antivirus/configure-microsoft-defender-antivirus-features) (antivirus)

## Related articles

- [Behavioral blocking and containment](behavioral-blocking-containment.md)

- [(Blog) Behavioral blocking and containment: Transforming optics into protection](https://www.microsoft.com/security/blog/2020/03/09/behavioral-blocking-and-containment-transforming-optics-into-protection/)

- [Helpful Microsoft Defender for Endpoint resources](/microsoft-365/security/defender-endpoint/helpful-resources)
