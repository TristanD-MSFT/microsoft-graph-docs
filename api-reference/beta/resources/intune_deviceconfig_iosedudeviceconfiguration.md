﻿#  resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

iOS Education device configuration

Inherits from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)

## Methods
|Method|Return Type|Description|
|---|---|---|
|[List iosEduDeviceConfigurations](../api/intune_deviceconfig_iosedudeviceconfiguration_list.md)|[iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md) collection|List properties and relationships of the [iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md) objects.|
|[Get iosEduDeviceConfiguration](../api/intune_deviceconfig_iosedudeviceconfiguration_get.md)|[iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md)|Read properties and relationships of the [iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md) object.|
|[Create iosEduDeviceConfiguration](../api/intune_deviceconfig_iosedudeviceconfiguration_create.md)|[iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md)|Create a new [iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md) object.|
|[Delete iosEduDeviceConfiguration](../api/intune_deviceconfig_iosedudeviceconfiguration_delete.md)|None|Deletes a [iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md).|
|[Update iosEduDeviceConfiguration](../api/intune_deviceconfig_iosedudeviceconfiguration_update.md)|[iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md)|Update the properties of a [iosEduDeviceConfiguration](../resources/intune_deviceconfig_iosedudeviceconfiguration.md) object.|
|[List deviceConfigurationGroupAssignments](../api/intune_deviceconfig_deviceconfigurationgroupassignment_list.md)|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|List properties and relationships of the [deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) objects.|
|[List deviceConfigurationDeviceStatuses](../api/intune_deviceconfig_deviceconfigurationdevicestatus_list.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|List properties and relationships of the [deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) objects.|
|[List deviceConfigurationUserStatuses](../api/intune_deviceconfig_deviceconfigurationuserstatus_list.md)|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|List properties and relationships of the [deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) objects.|
|[Get deviceConfigurationDeviceOverview](../api/intune_deviceconfig_deviceconfigurationdeviceoverview_get.md)|[deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md)|Read properties and relationships of the [deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md) object.|
|[Get deviceConfigurationUserOverview](../api/intune_deviceconfig_deviceconfigurationuseroverview_get.md)|[deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md)|Read properties and relationships of the [deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md) object.|
|[List settingStateDeviceSummaries](../api/intune_deviceconfig_settingstatedevicesummary_list.md)|[settingStateDeviceSummary](../resources/intune_deviceconfig_settingstatedevicesummary.md) collection|List properties and relationships of the [settingStateDeviceSummary](../resources/intune_deviceconfig_settingstatedevicesummary.md) objects.|

## Properties
|Property|Type|Description|
|---|---|---|
|id|String|Key of the entity. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|assignmentStatus|String|Read-only. DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|assignmentProgress|String|Read-only. DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|assignmentErrorMessage|String|Read-only. DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|description|String|Admin provided description of the Device Configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|displayName|String|Admin provided name of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|version|Int32|Version of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|teacherCertificateSettings|[iosEduCertificateSettings](../resources/intune_deviceconfig_ioseducertificatesettings.md)|The Trusted Root and PFX certificates for Teacher|
|studentCertificateSettings|[iosEduCertificateSettings](../resources/intune_deviceconfig_ioseducertificatesettings.md)|The Trusted Root and PFX certificates for Student|
|deviceCertificateSettings|[iosEduCertificateSettings](../resources/intune_deviceconfig_ioseducertificatesettings.md)|The Trusted Root and PFX certificates for Device|

## Relationships
|Relationship|Type|Description|
|---|---|---|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|The list of group assignments for the device configuration profile. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|Device configuration installation stauts by device. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|Device configuration installation stauts by user. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceStatusOverview|[deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md)|Device Configuration devices status overview Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|userStatusOverview|[deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md)|Device Configuration users status overview Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune_deviceconfig_settingstatedevicesummary.md) collection|Device Configuration Setting State Device Summary Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.iosEduDeviceConfiguration"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.iosEduDeviceConfiguration",
  "id": "String (identifier)",
  "lastModifiedDateTime": "String (timestamp)",
  "assignmentStatus": "String",
  "assignmentProgress": "String",
  "assignmentErrorMessage": "String",
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "version": 1024,
  "teacherCertificateSettings": {
    "@odata.type": "microsoft.graph.iosEduCertificateSettings",
    "trustedRootCertificate": "binary",
    "certFileName": "String",
    "certificationAuthority": "String",
    "certificationAuthorityName": "String",
    "certificateTemplateName": "String",
    "renewalThresholdPercentage": 1024,
    "certificateValidityPeriodValue": 1024,
    "certificateValidityPeriodScale": "String"
  },
  "studentCertificateSettings": {
    "@odata.type": "microsoft.graph.iosEduCertificateSettings",
    "trustedRootCertificate": "binary",
    "certFileName": "String",
    "certificationAuthority": "String",
    "certificationAuthorityName": "String",
    "certificateTemplateName": "String",
    "renewalThresholdPercentage": 1024,
    "certificateValidityPeriodValue": 1024,
    "certificateValidityPeriodScale": "String"
  },
  "deviceCertificateSettings": {
    "@odata.type": "microsoft.graph.iosEduCertificateSettings",
    "trustedRootCertificate": "binary",
    "certFileName": "String",
    "certificationAuthority": "String",
    "certificationAuthorityName": "String",
    "certificateTemplateName": "String",
    "renewalThresholdPercentage": 1024,
    "certificateValidityPeriodValue": 1024,
    "certificateValidityPeriodScale": "String"
  }
}
```



