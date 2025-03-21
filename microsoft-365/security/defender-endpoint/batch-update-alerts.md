---
title: Batch Update alert entities API
description: Learn how to update Microsoft Defender for Endpoint alerts in a batch by using this API. You can update the status, determination, classification, and assignedTo properties.
keywords: apis, graph api, supported apis, get, alert, information, id
search.product: eADQiWindows 10XVcnh
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: M365-security-compliance
ms.topic: article
ms.technology: mde
ms.custom: api
---

# Batch update alerts

[!INCLUDE [Microsoft 365 Defender rebranding](../../includes/microsoft-defender.md)]


**Applies to:** [Microsoft Defender for Endpoint](https://go.microsoft.com/fwlink/p/?linkid=2154037)

- Want to experience Microsoft Defender for Endpoint? [Sign up for a free trial.](https://signup.microsoft.com/create-account/signup?products=7f379fee-c4f9-4278-b0a1-e4c8c2fcdf7e&ru=https://aka.ms/MDEp2OpenTrial?ocid=docs-wdatp-exposedapis-abovefoldlink)

[!include[Microsoft Defender for Endpoint API URIs for US Government](../../includes/microsoft-defender-api-usgov.md)]

[!include[Improve request performance](../../includes/improve-request-performance.md)]


## API description

Updates properties of a batch of existing [Alerts](alerts.md).

Submission of **comment** is available with or without updating properties.

Updatable properties are: `status`, `determination`, `classification` and `assignedTo`.

## Limitations

1. You can update alerts that are available in the API. See [List Alerts](get-alerts.md) for more information.
2. Rate limitations for this API are 10 calls per minute and 500 calls per hour.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Use Microsoft Defender for Endpoint APIs](apis-intro.md)

Permission type | Permission | Permission display name
:---|:---|:---
Application | Alert.ReadWrite.All | 'Read and write all alerts'
Delegated (work or school account) | Alert.ReadWrite | 'Read and write alerts'

> [!NOTE]
> When obtaining a token using user credentials:
>
> - The user needs to have at least the following role permission: 'Alerts investigation' (See [Create and manage roles](user-roles.md) for more information)
> - The user needs to have access to the device associated with the alert, based on device group settings (See [Create and manage device groups](machine-groups.md) for more information)

## HTTP request

```http
POST /api/alerts/batchUpdate
```

## Request headers

Name|Type|Description
:---|:---|:---
Authorization | String | Bearer {token}. **Required**.
Content-Type | String | application/json. **Required**.

## Request body

In the request body, supply the IDs of the alerts to be updated and the values of the relevant fields that you wish to update for these alerts.

Existing properties that are not included in the request body will maintain their previous values or be recalculated based on changes to other property values.

For best performance you shouldn't include existing values that haven't changed.

Property | Type | Description
:---|:---|:---
alertIds | List&lt;String&gt;| A list of the IDs of the alerts to be updated. **Required**
status | String | Specifies the updated status of the specified alerts. The property values are: 'New', 'InProgress' and 'Resolved'.
assignedTo | String | Owner of the specified alerts
classification | String | Specifies the specification of the specified alerts. The property values are: 'Unknown', 'FalsePositive', 'TruePositive'. 
determination | String | Specifies the determination of the specified alerts. The property values are: 'NotAvailable', 'Apt', 'Malware', 'SecurityPersonnel', 'SecurityTesting', 'UnwantedSoftware', 'Other'
comment | String | Comment to be added to the specified alerts.

## Response

If successful, this method returns 200 OK, with an empty response body.

## Example

### Request

Here is an example of the request.

```http
POST https://api.securitycenter.microsoft.com/api/alerts/batchUpdate
```

```json
{
    "alertIds": ["da637399794050273582_760707377", "da637399989469816469_51697947354"],
    "status": "Resolved",
    "assignedTo": "secop2@contoso.com",
    "classification": "FalsePositive",
    "determination": "Malware",
    "comment": "Resolve my alert and assign to secop2"
}
```
