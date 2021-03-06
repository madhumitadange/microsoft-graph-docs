﻿# iosEnterpriseWiFiConfiguration resource type

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

By providing the configurations in this profile you can instruct the iOS device to connect to desired Wi-Fi endpoint. By specifying the authentication method and security types expected by Wi-Fi endpoint you can make the Wi-Fi connection seamless for end user.

Inherits from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)

## Methods
|Method|Return Type|Description|
|---|---|---|
|[List iosEnterpriseWiFiConfigurations](../api/intune_deviceconfig_iosenterprisewificonfiguration_list.md)|[iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md) collection|List properties and relationships of the [iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md) objects.|
|[Get iosEnterpriseWiFiConfiguration](../api/intune_deviceconfig_iosenterprisewificonfiguration_get.md)|[iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md)|Read properties and relationships of the [iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md) object.|
|[Create iosEnterpriseWiFiConfiguration](../api/intune_deviceconfig_iosenterprisewificonfiguration_create.md)|[iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md)|Create a new [iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md) object.|
|[Delete iosEnterpriseWiFiConfiguration](../api/intune_deviceconfig_iosenterprisewificonfiguration_delete.md)|None|Deletes a [iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md).|
|[Update iosEnterpriseWiFiConfiguration](../api/intune_deviceconfig_iosenterprisewificonfiguration_update.md)|[iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md)|Update the properties of a [iosEnterpriseWiFiConfiguration](../resources/intune_deviceconfig_iosenterprisewificonfiguration.md) object.|
|[List deviceConfigurationGroupAssignments](../api/intune_deviceconfig_iosenterprisewificonfiguration_list_deviceconfigurationgroupassignment.md)|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|Get the deviceConfigurationGroupAssignments from the groupAssignments navigation property.|
|[List deviceConfigurationDeviceStatuses](../api/intune_deviceconfig_iosenterprisewificonfiguration_list_deviceconfigurationdevicestatus.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|Get the deviceConfigurationDeviceStatuses from the deviceStatuses navigation property.|
|[List deviceConfigurationUserStatuses](../api/intune_deviceconfig_iosenterprisewificonfiguration_list_deviceconfigurationuserstatus.md)|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|Get the deviceConfigurationUserStatuses from the userStatuses navigation property.|
|[Get deviceConfigurationDeviceOverview](../api/intune_deviceconfig_iosenterprisewificonfiguration_get_deviceconfigurationdeviceoverview.md)|[deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md)|Get the [deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md) from the deviceStatusOverview navigation property.|
|[Get deviceConfigurationUserOverview](../api/intune_deviceconfig_iosenterprisewificonfiguration_get_deviceconfigurationuseroverview.md)|[deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md)|Get the [deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md) from the userStatusOverview navigation property.|
|[List settingStateDeviceSummaries](../api/intune_deviceconfig_iosenterprisewificonfiguration_list_settingstatedevicesummary.md)|[settingStateDeviceSummary](../resources/intune_deviceconfig_settingstatedevicesummary.md) collection|Get the settingStateDeviceSummaries from the deviceSettingStateSummaries navigation property.|
|[Get deviceConfigurationDeviceStateSummary](../api/intune_deviceconfig_iosenterprisewificonfiguration_get_deviceconfigurationdevicestatesummary.md)|[deviceConfigurationDeviceStateSummary](../resources/intune_deviceconfig_deviceconfigurationdevicestatesummary.md)|Get the [deviceConfigurationDeviceStateSummary](../resources/intune_deviceconfig_deviceconfigurationdevicestatesummary.md) from the deviceConfigurationDeviceStateSummaries navigation property.|
|[List iosTrustedRootCertificates](../api/intune_deviceconfig_iosenterprisewificonfiguration_list_iostrustedrootcertificate.md)|[iosTrustedRootCertificate](../resources/intune_deviceconfig_iostrustedrootcertificate.md) collection|Get the iosTrustedRootCertificates from the rootCertificatesForServerValidation navigation property.|
|[Get iosCertificateProfileBase](../api/intune_deviceconfig_iosenterprisewificonfiguration_get_ioscertificateprofilebase.md)|[iosCertificateProfileBase](../resources/intune_deviceconfig_ioscertificateprofilebase.md)|Get the [iosCertificateProfileBase](../resources/intune_deviceconfig_ioscertificateprofilebase.md) from the identityCertificateForClientAuthentication navigation property.|

## Properties
|Property|Type|Description|
|---|---|---|
|id|String|Key of the entity. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|description|String|Admin provided description of the Device Configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|displayName|String|Admin provided name of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|version|Int32|Version of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|networkName|String|Network Name Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|ssid|String|This is the name of the Wi-Fi network that is broadcast to all devices. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|connectAutomatically|Boolean|Connect automatically when this network is in range. Setting this to true will skip the user prompt and automatically connect the device to Wi-Fi network. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|connectWhenNetworkNameIsHidden|Boolean|Connect when the network is not broadcasting its name (SSID). When set to true, this profile forces the device to connect to a network that doesn't broadcast its SSID to all devices. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|wiFiSecurityType|String|Indicates whether Wi-Fi endpoint uses an EAP based security type. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md) Possible values are: `open`, `wpaPersonal`, `wpaEnterprise`, `wep`.|
|proxySettings|String|Proxy Type for this Wi-Fi connection Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md) Possible values are: `none`, `manual`, `automatic`.|
|proxyManualAddress|String|IP Address or DNS hostname of the proxy server when manual configuration is selected. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|proxyManualPort|Int32|Port of the proxy server when manual configuration is selected. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|proxyAutomaticConfigurationUrl|String|URL of the proxy server automatic configuration script when automatic configuration is selected. This URL is typically the location of PAC (Proxy Auto Configuration) file. Inherited from [iosWiFiConfiguration](../resources/intune_deviceconfig_ioswificonfiguration.md)|
|eapType|String|Extensible Authentication Protocol (EAP). Indicates the type of EAP protocol set on the the Wi-Fi endpoint (router). Possible values are: `eapTls`, `leap`, `eapSim`, `eapTtls`, `peap`, `eapFast`.|
|eapFastConfiguration|String|EAP-FAST Configuration Option when EAP-FAST is the selected EAP Type. Possible values are: `noProtectedAccessCredential`, `useProtectedAccessCredential`, `useProtectedAccessCredentialAndProvision`, `useProtectedAccessCredentialAndProvisionAnonymously`.|
|trustedServerCertificateNames|String collection|Trusted server certificate names when EAP Type is configured to EAP-TLS/TTLS/FAST or PEAP. This is the common name used in the certificates issued by your trusted certificate authority (CA). If you provide this information, you can bypass the dynamic trust dialog that is displayed on end users' devices when they connect to this Wi-Fi network.|
|authenticationMethod|String|Authentication Method when EAP Type is configured to PEAP or EAP-TTLS. Possible values are: `certificate`, `usernameAndPassword`.|
|nonEapAuthenticationMethodForEapTtls|String|Non-EAP Method for Authentication when EAP Type is EAP-TTLS and Authenticationmethod is Username and Password. Possible values are: `unencryptedPassword`, `challengeHandshakeAuthenticationProtocol`, `microsoftChap`, `microsoftChapVersionTwo`.|
|enableOuterIdentityPrivacy|String|Enable identity privacy (Outer Identity) when EAP Type is configured to EAP - TTLS, EAP - FAST or PEAP. This property masks usernames with the text you enter. For example, if you use 'anonymous', each user that authenticates with this Wi-Fi connection using their real username is displayed as 'anonymous'.|

## Relationships
|Relationship|Type|Description|
|---|---|---|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|The list of group assignments for the device configuration profile. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|Device configuration installation stauts by device. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|Device configuration installation stauts by user. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceStatusOverview|[deviceConfigurationDeviceOverview](../resources/intune_deviceconfig_deviceconfigurationdeviceoverview.md)|Device Configuration devices status overview Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|userStatusOverview|[deviceConfigurationUserOverview](../resources/intune_deviceconfig_deviceconfigurationuseroverview.md)|Device Configuration users status overview Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune_deviceconfig_settingstatedevicesummary.md) collection|Device Configuration Setting State Device Summary Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceConfigurationDeviceStateSummaries|[deviceConfigurationDeviceStateSummary](../resources/intune_deviceconfig_deviceconfigurationdevicestatesummary.md)|The device compliance state summary for this account. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|rootCertificatesForServerValidation|[iosTrustedRootCertificate](../resources/intune_deviceconfig_iostrustedrootcertificate.md) collection|Trusted Root Certificates for Server Validation when EAP Type is configured to EAP-TLS/TTLS/FAST or PEAP. If you provide this value you do not need to provide trustedServerCertificateNames, and vice versa.|
|identityCertificateForClientAuthentication|[iosCertificateProfileBase](../resources/intune_deviceconfig_ioscertificateprofilebase.md)|Identity Certificate for client authentication when EAP Type is configured to EAP-TLS, EAP-TTLS (with Certificate Authentication), or PEAP (with Certificate Authentication).|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.iosEnterpriseWiFiConfiguration"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.iosEnterpriseWiFiConfiguration",
  "id": "String (identifier)",
  "lastModifiedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "version": 1024,
  "networkName": "String",
  "ssid": "String",
  "connectAutomatically": true,
  "connectWhenNetworkNameIsHidden": true,
  "wiFiSecurityType": "String",
  "proxySettings": "String",
  "proxyManualAddress": "String",
  "proxyManualPort": 1024,
  "proxyAutomaticConfigurationUrl": "String",
  "eapType": "String",
  "eapFastConfiguration": "String",
  "trustedServerCertificateNames": [
    "String"
  ],
  "authenticationMethod": "String",
  "nonEapAuthenticationMethodForEapTtls": "String",
  "enableOuterIdentityPrivacy": "String"
}
```



