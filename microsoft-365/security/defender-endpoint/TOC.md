# [Microsoft Defender for Endpoint](index.yml)

## [Overview]()
### [What is Microsoft Defender for Endpoint?](microsoft-defender-endpoint.md)
### [Compare Defender for Endpoint Plan 1 to Plan 2](defender-endpoint-plan-1-2.md)
### [Minimum requirements](minimum-requirements.md)
### [What's new in Microsoft Defender for Endpoint?](whats-new-in-microsoft-defender-atp.md)
### [Preview features](preview.md)
### [Data storage and privacy](data-storage-privacy.md)
### [Overview of Microsoft Defender Security Center](use.md)
### [Portal overview](portal-overview.md)
### [Defender for Endpoint Plan 1 (preview)]()
#### [Overview](defender-endpoint-plan-1.md)
#### [Setup and configuration](mde-p1-setup-configuration.md)
#### [Get started](mde-plan1-getting-started.md)
#### [Maintenance and operations](mde-p1-maintenance-operations.md)
### [Microsoft Defender for Endpoint for US Government customers](gov.md)
### [Microsoft Defender for Endpoint on non-Windows platforms](non-windows.md)


## [Evaluate capabilities](evaluation-lab.md)

## [Plan deployment](deployment-strategy.md)

## [Deployment guide]()
### [Deployment phases](deployment-phases.md)
### [Phase 1: Prepare](prepare-deployment.md)
### [Phase 2: Set up](production-deployment.md)
### [Phase 3: Onboard]()
#### [Onboarding overview](onboarding.md)
#### [Deployment rings](deployment-rings.md)
#### [Onboarding using Microsoft Endpoint Configuration Manager](onboarding-endpoint-configuration-manager.md)
#### [Onboarding using Microsoft Endpoint Manager](onboarding-endpoint-manager.md)

## [Migration guides](migration-guides.md)
### [Switch from non-Microsoft endpoint protection to Defender for Endpoint](switch-to-microsoft-defender-migration.md)
#### [Phase 1: Prepare](switch-to-microsoft-defender-prepare.md)
#### [Phase 2: Setup](switch-to-microsoft-defender-setup.md)
#### [Phase 3: Onboard](switch-to-microsoft-defender-onboard.md)



### [Manage Defender for Endpoint after migration](manage-atp-post-migration.md)
#### [Use Intune (recommended)](manage-atp-post-migration-intune.md)
#### [Use Configuration Manager](manage-atp-post-migration-configuration-manager.md)
#### [Use Group Policy](manage-atp-post-migration-group-policy-objects.md)
#### [Use PowerShell, WMI, or MPCmdRun.exe](manage-atp-post-migration-other-tools.md)
#### [Server migration scenarios](server-migration.md)

## [Configure and onboard devices]()
### [Onboard devices and configure Microsoft Defender for Endpoint capabilities](onboard-configure.md)


### [Microsoft Defender for Endpoint on Windows and Windows Server]()
#### [Onboarding tools and methods for Windows endpoints](configure-endpoints.md)
#### [Onboard Windows devices and Windows Servers]()

##### [Onboard previous versions of Windows](onboard-downlevel.md)


##### [Onboard Windows devices and Windows Servers]()
###### [Onboard Windows Server 2012 R2, 2016, Semi-Annual Channel, 2019, and 2022](configure-server-endpoints.md)
###### [Onboard Windows devices using a local script](configure-endpoints-script.md)
###### [Onboard Windows devices using Group Policy](configure-endpoints-gp.md)
###### [Onboard Windows devices using Microsoft Endpoint Configuration Manager](configure-endpoints-sccm.md)
###### [Onboard Windows devices using Mobile Device Management tools](configure-endpoints-mdm.md)
###### [Onboard non-persistent virtual desktop infrastructure (VDI) devices](configure-endpoints-vdi.md)
###### [Onboard Windows 10 multi-session devices in Windows Virtual Desktop](onboard-windows-multi-session-device.md)




#### [Integration with Azure Defender](azure-server-integration.md)

#### [Onboard devices without Internet access](onboard-offline-machines.md)
#### [Run a detection test on a newly onboarded device](run-detection-test.md)
#### [Run simulated attacks on devices](attack-simulations.md)
#### [Configure proxy and Internet connectivity settings](configure-proxy-internet.md)
#### [Create an onboarding or offboarding notification rule](onboarding-notification.md)

#### [Application license terms](mde-terms-windows.md)


### [Microsoft Defender for Endpoint on other Operating Systems]()
#### [Onboard non-Windows devices](configure-endpoints-non-windows.md)

#### [Microsoft Defender for Endpoint on macOS]()
##### [Overview of Microsoft Defender for Endpoint on macOS](microsoft-defender-endpoint-mac.md)
##### [What's New](mac-whatsnew.md)

##### [Deploy]()
###### [Microsoft Intune-based deployment](mac-install-with-intune.md)
###### [JAMF Pro-based deployment]()
####### [Deploying Microsoft Defender for Endpoint on macOS using Jamf Pro](mac-install-with-jamf.md)
####### [Login to Jamf Pro](mac-install-jamfpro-login.md)
####### [Set up device groups](mac-jamfpro-device-groups.md)
####### [Set up policies](mac-jamfpro-policies.md)
####### [Enroll devices](mac-jamfpro-enroll-devices.md)

###### [Deployment with a different Mobile Device Management (MDM) system](mac-install-with-other-mdm.md)
###### [Manual deployment](mac-install-manually.md)
##### [Update](mac-updates.md)

##### [Configure]()
###### [Configure and validate exclusions](mac-exclusions.md)
###### [Set preferences](mac-preferences.md)
###### [Detect and block Potentially Unwanted Applications](mac-pua.md)
###### [Device control]()
####### [Device control overview](mac-device-control-overview.md)
####### [JAMF examples](mac-device-control-jamf.md)
####### [Intune examples](mac-device-control-intune.md)
###### [Schedule scans](mac-schedule-scan.md)

##### [Troubleshoot]()
###### [Troubleshoot installation issues](mac-support-install.md)
###### [Troubleshoot performance issues](mac-support-perf.md)
###### [Troubleshoot cloud connectivity](troubleshoot-cloud-connect-mdemac.md)
###### [Troubleshoot kernel extension issues](mac-support-kext.md)
###### [Troubleshoot license issues](mac-support-license.md)

##### [Privacy](mac-privacy.md)
##### [Resources](mac-resources.md)
##### [Application license terms](mde-terms-mac.md)

#### [Microsoft Defender for Endpoint on Linux]()
##### [Overview of Microsoft Defender for Endpoint on Linux](microsoft-defender-endpoint-linux.md)
##### [What's New](linux-whatsnew.md)
##### [Deploy]()
###### [Manual deployment](linux-install-manually.md)
###### [Puppet based deployment](linux-install-with-puppet.md)
###### [Ansible based deployment](linux-install-with-ansible.md)
###### [Deploy Defender for Endpoint on Linux with Chef](linux-deploy-defender-for-endpoint-with-chef.md)

##### [Update](linux-updates.md)

##### [Configure]()
###### [Configure and validate exclusions](linux-exclusions.md)
###### [Static proxy configuration](linux-static-proxy-configuration.md)
###### [Set preferences](linux-preferences.md)
###### [Detect and block Potentially Unwanted Applications](linux-pua.md)
###### [Schedule scans with Microsoft Defender for Endpoint on Linux](linux-schedule-scan-atp.md)
###### [Schedule an update of the Microsoft Defender for Endpoint (Linux)](linux-update-MDE-Linux.md)


##### [Troubleshoot]()
###### [Troubleshoot installation issues](linux-support-install.md)
###### [Investigate agent health issues](health-status.md)
###### [Troubleshoot cloud connectivity issues](linux-support-connectivity.md)
###### [Troubleshoot RHEL 6 installation issues](linux-support-rhel.md)
###### [Troubleshoot performance issues](linux-support-perf.md)
###### [Troubleshoot missing events issues](linux-support-events.md)

##### [Privacy](linux-privacy.md)
##### [Resources](linux-resources.md)

#### [Mobile Threat Defense]()
##### [Mobile Threat Defense Overview](mtd.md)

##### [Microsoft Defender for Endpoint on Android]()
###### [Overview of Microsoft Defender for Endpoint on Android](microsoft-defender-endpoint-android.md)
###### [What's new](android-whatsnew.md)

###### [Deploy]()
####### [Deploy Microsoft Defender for Endpoint on Android with Microsoft Intune](android-intune.md)

###### [Configure]()
####### [Configure Microsoft Defender for Endpoint on Android features](android-configure.md)
####### [Configure Microsoft Defender for Endpoint risk signals using app protection policy](android-configure-mam.md)

###### [Privacy]()
####### [Microsoft Defender for Endpoint on Android - Privacy information](android-privacy.md)

###### [Troubleshoot]()
####### [Troubleshoot issues](android-support-signin.md)

##### [Microsoft Defender for Endpoint on iOS]()
###### [Overview of Microsoft Defender for Endpoint on iOS](microsoft-defender-endpoint-ios.md)
###### [What's New](ios-whatsnew.md)

###### [Deploy]()
####### [Deploy Microsoft Defender for Endpoint on iOS via Intune](ios-install.md)
####### [Deploy Microsoft Defender for Endpoint on iOS for unenrolled devices](ios-install-unmanaged.md)

###### [Configure iOS features](ios-configure-features.md)

###### [FAQs and Troubleshooting](ios-troubleshoot.md)

###### [Privacy](ios-privacy.md)

##### [Microsoft Defender for Endpoint application license terms](mde-terms-mobile.md) 

### [Manage Microsoft Defender for Endpoint configuration settings on devices with Microsoft Endpoint Manager](security-config-management.md)

### [Troubleshoot onboarding issues]()
#### [Troubleshoot issues during onboarding](troubleshoot-onboarding.md)
#### [Troubleshoot subscription and portal access issues](troubleshoot-onboarding-error-messages.md)
#### [Troubleshoot security configuration management onboarding issues](troubleshoot-security-config-mgt.md)





### [Configure portal settings]()
#### [Set up preferences](preferences-setup.md)
#### [General]()
##### [Verify data storage location and  update data retention settings](data-retention-settings.md)
##### [Configure alert notifications](configure-email-notifications.md)
##### [Configure vulnerability email notifications](configure-vulnerability-email-notifications.md)
##### [Configure advanced features](advanced-features.md)

#### [Permissions]()
##### [Use basic permissions to access the portal](basic-permissions.md)
##### [Manage portal access using RBAC](rbac.md)
###### [Create and manage roles](user-roles.md)
###### [Create and manage device groups](machine-groups.md)
###### [Create and manage device tags](machine-tags.md)

#### [Rules]()
##### [Manage suppression rules](manage-suppression-rules.md)
##### [Create indicators](manage-indicators.md)
###### [Create indicators for files](indicator-file.md)
###### [Create indicators for IPs and URLs/domains](indicator-ip-domain.md)
###### [Create indicators for certificates](indicator-certificates.md)
###### [Manage indicators](indicator-manage.md)
##### [Manage automation file uploads](manage-automation-file-uploads.md)
##### [Manage automation folder exclusions](manage-automation-folder-exclusions.md)

#### [Device management]()
##### [Onboarding devices](onboard-configure.md)
##### [Offboarding devices](offboard-machines.md)
##### [Ensure your devices are configured properly](configure-machines.md)
##### [Monitor and increase device onboarding](configure-machines-onboarding.md)

#### [Configure Microsoft Defender Security Center time zone settings](time-settings.md)

## [Detect threats and protect endpoints]()
### [Threat & vulnerability management]()
#### [Overview](next-gen-threat-and-vuln-mgt.md)
#### [Get started]()
##### [Permissions & prerequisites](tvm-prerequisites.md)
##### [Supported operating systems platforms and capabilities](tvm-supported-os.md)
##### [Assign device value](tvm-assign-device-value.md)
#### [Assess your security posture]()
##### [Dashboard insights](tvm-dashboard-insights.md)
##### [Exposure score](tvm-exposure-score.md)
##### [Microsoft Secure Score for Devices](tvm-microsoft-secure-score-devices.md)
#### [Improve your security posture & reduce risk]()
##### [Address security recommendations](tvm-security-recommendation.md)
##### [Remediate vulnerabilities](tvm-remediation.md)
##### [Exceptions for security recommendations](tvm-exception.md)
##### [Plan for end-of-support software](tvm-end-of-support-software.md)
##### [Mitigate zero-day vulnerabilities](tvm-zero-day-vulnerabilities.md)
#### [Understand vulnerabilities on your devices]()
##### [Software inventory](tvm-software-inventory.md)
##### [Vulnerabilities in my organization](tvm-weaknesses.md)
##### [Event timeline](threat-and-vuln-mgt-event-timeline.md)
##### [Vulnerable devices report](tvm-vulnerable-devices-report.md)
##### [Hunt for exposed devices](tvm-hunt-exposed-devices.md)

### [Device discovery]()
#### [Device discovery overview](device-discovery.md)
#### [Configure device discovery](configure-device-discovery.md)
#### [Device discovery FAQ](device-discovery-faq.md)

### [Network devices](network-devices.md)

### [Host firewall reporting in Microsoft Defender for Endpoint](host-firewall-reporting.md)

### [Attack surface reduction]()
#### [Overview of attack surface reduction](overview-attack-surface-reduction.md)
#### [Configure attack surface reduction capabilities](configure-attack-surface-reduction.md)
#### [Learn about attack surface reduction rules](attack-surface-reduction.md)
#### [Attack surface reduction rules](attack-surface-reduction-rules.md)
#### [Evaluate attack surface reduction rules](evaluate-attack-surface-reduction.md)
#### [Enable attack surface reduction rules](enable-attack-surface-reduction.md)
#### [Customize attack surface reduction rules](customize-attack-surface-reduction.md)
#### [Attack surface reduction FAQ](attack-surface-reduction-faq.yml)
#### [View attack surface reduction events](event-views.md)
#### [Use audit mode for attack surface reduction](audit-windows-defender.md)

### Next-generation protection
#### [Next-generation protection overview](next-generation-protection.md)
##### [Overview of Microsoft Defender Antivirus](microsoft-defender-antivirus-windows.md)
##### [Microsoft Defender Antivirus on Windows Server](microsoft-defender-antivirus-on-windows-server.md)
##### [Better together: Microsoft Defender Antivirus and Microsoft Defender for Endpoint](why-use-microsoft-defender-antivirus.md)
##### [Better together: Microsoft Defender Antivirus and Office 365](office-365-microsoft-defender-antivirus.md)
#### [Evaluate Microsoft Defender Antivirus](evaluate-microsoft-defender-antivirus.md)
#### [Configure Microsoft Defender Antivirus features](configure-microsoft-defender-antivirus-features.md)
#### [Cloud protection and Microsoft Defender Antivirus](cloud-protection-microsoft-defender-antivirus.md)
##### [Why cloud protection should be on](why-cloud-protection-should-be-on-mdav.md)
##### [Turn on cloud protection](enable-cloud-protection-microsoft-defender-antivirus.md)
##### [Specify the cloud protection level](specify-cloud-protection-level-microsoft-defender-antivirus.md)
##### [Cloud protection and sample submission](cloud-protection-microsoft-antivirus-sample-submission.md)
#### [Configure and validate Microsoft Defender Antivirus network connections](configure-network-connections-microsoft-defender-antivirus.md)
#### [Protect security settings with tamper protection](prevent-changes-to-security-settings-with-tamper-protection.md)
#### [Turn on block at first sight](configure-block-at-first-sight-microsoft-defender-antivirus.md)
#### [Configure the cloud block timeout period](configure-cloud-block-timeout-period-microsoft-defender-antivirus.md)
#### [Configure behavioral, heuristic, and real-time protection](configure-protection-features-microsoft-defender-antivirus.md)
#### [Detect and block potentially unwanted applications](detect-block-potentially-unwanted-apps-microsoft-defender-antivirus.md)
#### [Enable and configure Microsoft Defender Antivirus always-on protection in Group Policy](configure-real-time-protection-microsoft-defender-antivirus.md)
#### [Configure remediation for Microsoft Defender Antivirus detections](configure-remediation-microsoft-defender-antivirus.md)
#### [Configure Microsoft Defender Antivirus scans](schedule-antivirus-scans.md)
##### [Schedule scans using Group Policy](schedule-antivirus-scans-group-policy.md)
##### [Schedule scans using PowerShell](schedule-antivirus-scans-powershell.md)
##### [Schedule scans using WMI](schedule-antivirus-scans-wmi.md)
#### [Use limited periodic scanning in Microsoft Defender Antivirus](limited-periodic-scanning-microsoft-defender-antivirus.md)
#### [Tune performance of Microsoft Defender Antivirus](tune-performance-defender-antivirus.md)
#### [Compatibility with other security products](microsoft-defender-antivirus-compatibility.md)

#### [Get your antivirus and antimalware updates](manage-updates-baselines-microsoft-defender-antivirus.md)
##### [Manage the sources for Microsoft Defender Antivirus protection updates](manage-protection-updates-microsoft-defender-antivirus.md)
##### [Manage the schedule for when protection updates should be downloaded and applied](manage-protection-update-schedule-microsoft-defender-antivirus.md)
##### [Manage gradual rollout process for Microsoft Defender updates](manage-gradual-rollout.md)
##### [Configure gradual rollout process for Microsoft Defender updates](configure-updates.md)
##### [Manage Microsoft Defender Antivirus updates and scans for endpoints that are out of date](manage-outdated-endpoints-microsoft-defender-antivirus.md)
##### [Manage event-based forced updates](manage-event-based-updates-microsoft-defender-antivirus.md)
##### [Manage updates for mobile devices and virtual machines (VMs)](manage-updates-mobile-devices-vms-microsoft-defender-antivirus.md)

#### [Manage Microsoft Defender Antivirus for your organization](configuration-management-reference-microsoft-defender-antivirus.md)
##### [Use Microsoft Endpoint Manager to manage Microsoft Defender Antivirus](use-intune-config-manager-microsoft-defender-antivirus.md)
##### [Use Group Policy settings to manage Microsoft Defender Antivirus](use-group-policy-microsoft-defender-antivirus.md)
##### [Use PowerShell cmdlets to manage Microsoft Defender Antivirus](use-powershell-cmdlets-microsoft-defender-antivirus.md)
##### [Use Windows Management Instrumentation (WMI) to manage Microsoft Defender Antivirus](use-wmi-microsoft-defender-antivirus.md)
##### [Use the mpcmdrun.exe tool to manage Microsoft Defender Antivirus](command-line-arguments-microsoft-defender-antivirus.md)
##### [Configure the notifications that appear on endpoints](configure-notifications-microsoft-defender-antivirus.md)
##### [Specify whether users can locally modify Microsoft Defender Antivirus policy settings](configure-local-policy-overrides-microsoft-defender-antivirus.md)
##### [Specify whether users can see or interact with Microsoft Defender Antivirus user interface](prevent-end-user-interaction-microsoft-defender-antivirus.md)

#### [Deploy and report on Microsoft Defender Antivirus](deploy-manage-report-microsoft-defender-antivirus.md)
##### [Deploy and enable Microsoft Defender Antivirus](deploy-microsoft-defender-antivirus.md)
##### [Deployment guide for Microsoft Defender Antivirus in a virtual desktop infrastructure (VDI) environment](deployment-vdi-microsoft-defender-antivirus.md)
##### [Report on Microsoft Defender Antivirus](report-monitor-microsoft-defender-antivirus.md)

#### [Scans and remediation](review-scan-results-microsoft-defender-antivirus.md)
##### [Configure and run on-demand Microsoft Defender Antivirus scans](run-scan-microsoft-defender-antivirus.md)
##### [Run and review the results of a Microsoft Defender Offline scan](microsoft-defender-offline.md)
##### [Configure Microsoft Defender Antivirus scanning options](configure-advanced-scan-types-microsoft-defender-antivirus.md)
##### [Restore quarantined files in Microsoft Defender Antivirus](restore-quarantined-files-microsoft-defender-antivirus.md)

#### [Microsoft Defender Antivirus exclusions](configure-exclusions-microsoft-defender-antivirus.md)
##### [Exclusions based on file extension and folder location](configure-extension-file-exclusions-microsoft-defender-antivirus.md)
##### [Exclusions for files opened by processes](configure-process-opened-file-exclusions-microsoft-defender-antivirus.md)
##### [Exclusions for Windows Server](configure-server-exclusions-microsoft-defender-antivirus.md)
##### [Common mistakes to avoid](common-exclusion-mistakes-microsoft-defender-antivirus.md)

#### Troubleshooting Microsoft Defender Antivirus
##### [Troubleshoot Microsoft Defender Antivirus reporting in Update Compliance](troubleshoot-reporting.md)
##### [Troubleshoot performance issues](troubleshoot-performance-issues.md)
##### [Review event logs and error codes to troubleshoot issues with Microsoft Defender Antivirus](troubleshoot-microsoft-defender-antivirus.md)
##### [Troubleshoot Microsoft Defender Antivirus while migrating from a third-party solution](troubleshoot-microsoft-defender-antivirus-when-migrating.md)

#### [Exploit protection]()
##### [Protect devices from exploits](exploit-protection.md)
##### [Exploit protection evaluation](evaluate-exploit-protection.md)
##### [Enable exploit protection](enable-exploit-protection.md)
##### [Customize exploit protection](customize-exploit-protection.md)
##### [Import, export, and deploy exploit protection configurations](import-export-exploit-protection-emet-xml.md)
##### [Exploit protection reference](exploit-protection-reference.md)

#### [Network protection]()
##### [Protect your network](network-protection.md)
##### [Evaluate network protection](evaluate-network-protection.md)
##### [Turn on network protection](enable-network-protection.md)

#### [Web protection]()
##### [Web protection overview](web-protection-overview.md)
##### [Web threat protection]()
###### [Web threat protection overview](web-threat-protection.md)
###### [Monitor web security](web-protection-monitoring.md)
###### [Respond to web threats](web-protection-response.md)
##### [Web content filtering](web-content-filtering.md)

#### [Controlled folder access]()
##### [Protect folders](controlled-folders.md)
##### [Evaluate controlled folder access](evaluate-controlled-folder-access.md)
##### [Enable controlled folder access](enable-controlled-folders.md)
##### [Customize controlled folder access](customize-controlled-folders.md)

#### [Device Control]()
##### [Removable Storage Protection](device-control-removable-storage-protection.md)
##### [Removable Storage Access Control](device-control-removable-storage-access-control.md)
##### [Device Installation](mde-device-control-device-installation.md)
##### [Device Control Printer Protection](printer-protection.md)
##### [Device Control Reports](device-control-report.md)

#### [Behavioral blocking and containment]()
##### [Behavioral blocking and containment](behavioral-blocking-containment.md)
##### [Client behavioral blocking](client-behavioral-blocking.md)
##### [Feedback-loop blocking](feedback-loop-blocking.md)


### [Address false positives/negatives in Microsoft Defender for Endpoint](defender-endpoint-false-positives-negatives.md)


### [Manage device configuration]()

#### [Increase compliance to the security baseline](configure-machines-security-baseline.md)
#### [Optimize attack surface reduction rule deployment and detections](configure-machines-asr.md)

## [Investigate and respond to threats]()
### [Endpoint detection and response]()
#### [Endpoint detection and response overview](overview-endpoint-detection-response.md)
#### [Security operations dashboard](security-operations-dashboard.md)
#### [Incidents queue]()
##### [View and organize the Incidents queue](view-incidents-queue.md)
##### [Manage incidents](manage-incidents.md)
##### [Investigate incidents](investigate-incidents.md)

#### [Alerts queue]()
##### [Alerts queue in Microsoft 365 Defender](alerts-queue-endpoint-detection-response.md)
##### [View and organize the Alerts queue](alerts-queue.md)
##### [Review alerts](review-alerts.md)
##### [Manage alerts](manage-alerts.md)
##### [Investigate alerts](investigate-alerts.md)
##### [Investigate files](investigate-files.md)
##### [Investigate devices](investigate-machines.md)
##### [Investigate an IP address](investigate-ip.md)
##### [Investigate a domain](investigate-domain.md)
###### [Investigate connection events that occur behind forward proxies](investigate-behind-proxy.md)
##### [Investigate a user account](investigate-user.md)

#### [Devices list]()
##### [View and organize the Devices list](machines-view-overview.md)
##### [Device timeline event flags](device-timeline-event-flag.md)
##### [Manage device group and tags](machine-tags.md)

#### [Take response actions]()
##### [Take response actions on a device]()
###### [Response actions on devices](respond-machine-alerts.md)
###### [Manage tags](respond-machine-alerts.md#manage-tags)
###### [Start an automated investigation](respond-machine-alerts.md#initiate-automated-investigation)
###### [Start a Live Response session](respond-machine-alerts.md#initiate-live-response-session)
###### [Collect investigation package](respond-machine-alerts.md#collect-investigation-package-from-devices)
###### [Run antivirus scan](respond-machine-alerts.md#run-microsoft-defender-antivirus-scan-on-devices)
###### [Restrict app execution](respond-machine-alerts.md#restrict-app-execution)
###### [Isolate devices from the network](respond-machine-alerts.md#isolate-devices-from-the-network)
###### [Consult a threat expert](respond-machine-alerts.md#consult-a-threat-expert)
###### [Check activity details in Action center](respond-machine-alerts.md#check-activity-details-in-action-center)

##### [Take response actions on a file]()
###### [Response actions on files](respond-file-alerts.md)
###### [Stop and quarantine files in your network](respond-file-alerts.md#stop-and-quarantine-files-in-your-network)
###### [Restore file from quarantine](respond-file-alerts.md#restore-file-from-quarantine)
###### [Add indicators to block or allow a file](respond-file-alerts.md#add-indicator-to-block-or-allow-a-file)
###### [Consult a threat expert](respond-file-alerts.md#consult-a-threat-expert)
###### [Check activity details in Action center](respond-file-alerts.md#check-activity-details-in-action-center)
###### [Download or collect file](respond-file-alerts.md#download-or-collect-file)
###### [Deep analysis](respond-file-alerts.md#deep-analysis)

#### [View and approve remediation actions](manage-auto-investigation.md)
##### [View details and results of automated investigations](auto-investigation-action-center.md)

#### [Investigate entities using Live response]()
##### [Investigate entities on devices](live-response.md)
##### [Live response command examples](live-response-command-examples.md)

#### [Use sensitivity labels to prioritize incident response](information-protection-investigation.md)

#### [Reporting]()
##### [Power BI - How to use API - Samples](api-power-bi.md)
##### [Threat protection reports](threat-protection-reports.md)
#### [Device health and compliance reports](machine-reports.md)

### [Advanced hunting]()
#### [Advanced hunting overview](advanced-hunting-overview.md)
#### [Understand the schema](advanced-hunting-schema-reference.md)
#### [DeviceAlertEvents](advanced-hunting-devicealertevents-table.md)

### [Threat analytics overview](threat-analytics.md)
#### [Read the analyst report](threat-analytics-analyst-reports.md)

### [EDR in block mode](edr-in-block-mode.md)

### [Automated investigation and response (AIR)]()
#### [Overview of AIR](automated-investigations.md)
#### [Automation levels in AIR](automation-levels.md)
#### [Configure AIR capabilities](configure-automated-investigations-remediation.md)

### [Microsoft Threat Experts]()
#### [Microsoft Threat Experts overview](microsoft-threat-experts.md)
#### [Configure and manage Microsoft Threat Experts capabilities](configure-microsoft-threat-experts.md)



## Reference
### [Understand threat intelligence concepts](threat-indicator-concepts.md)
### [Configure integration with other Microsoft solutions]()
#### [Configure conditional access](configure-conditional-access.md)
#### [Configure Microsoft Cloud App Security integration](microsoft-cloud-app-security-config.md)
### [Management and APIs]()
#### [Overview of management and APIs](management-apis.md)
#### [API release notes](api-release-notes.md)
#### [Microsoft Defender for Endpoint API]()
##### [Get started]()
###### [Microsoft Defender for Endpoint API license and terms](api-terms-of-use.md)
###### [Access the Microsoft Defender for Endpoint APIs](apis-intro.md)
###### [Hello World](api-hello-world.md)
###### [Get access with application context](exposed-apis-create-app-webapp.md)
###### [Get access with user context](exposed-apis-create-app-nativeapp.md)



##### [Microsoft Defender for Endpoint APIs Schema]()
###### [Supported Microsoft Defender for Endpoint APIs](exposed-apis-list.md)
###### [Common REST API error codes](common-errors.md)
###### [Advanced Hunting](run-advanced-query-api.md)

###### [Alert]()
####### [Alert methods and properties](alerts.md)
####### [List alerts](get-alerts.md)
####### [Create alert](create-alert-by-reference.md)
####### [Batch update alerts](batch-update-alerts.md)
####### [Update Alert](update-alert.md)
####### [Get alert information by ID](get-alert-info-by-id.md)
####### [Get alert related domains information](get-alert-related-domain-info.md)
####### [Get alert related file information](get-alert-related-files-info.md)
####### [Get alert related IPs information](get-alert-related-ip-info.md)
####### [Get alert related device information](get-alert-related-machine-info.md)
####### [Get alert related user information](get-alert-related-user-info.md)


###### [Assessments of vulnerabilities and secure configurations]()
####### [Export assessment methods and properties](get-assessment-methods-properties.md)
####### [Export secure configuration assessment](get-assessment-secure-config.md)
####### [Export software inventory assessment](get-assessment-software-inventory.md)
####### [Export software vulnerabilities assessment](get-assessment-software-vulnerabilities.md)

###### [Automated Investigation]()
####### [Investigation methods and properties](investigation.md)
####### [List Investigation](get-investigation-collection.md)
####### [Get Investigation](get-investigation-object.md)
####### [Start Investigation](initiate-autoir-investigation.md)

###### [Domain]()
####### [Get domain related alerts](get-domain-related-alerts.md)
####### [Get domain related machines](get-domain-related-machines.md)
####### [Get domain statistics](get-domain-statistics.md)

###### [File]()
####### [File methods and properties](files.md)
####### [Get file information](get-file-information.md)
####### [Get file related alerts](get-file-related-alerts.md)
####### [Get file related machines](get-file-related-machines.md)
####### [Get file statistics](get-file-statistics.md)

###### [Indicators]()
####### [Indicators methods and properties](ti-indicator.md)
####### [List Indicators](get-ti-indicators-collection.md)
####### [Submit Indicator](post-ti-indicator.md)
####### [Import Indicator](import-ti-indicators.md)
####### [Delete Indicator](delete-ti-indicator-by-id.md)

###### [IP]()
####### [Get IP related alerts](get-ip-related-alerts.md)
####### [Get IP statistics](get-ip-statistics.md)


###### [Machine]()
####### [Machine methods and properties](machine.md)
####### [List machines](get-machines.md)
####### [Get machine by ID](get-machine-by-id.md)
####### [Get machine log on users](get-machine-log-on-users.md)
####### [Get machine related alerts](get-machine-related-alerts.md)
####### [Get installed software](get-installed-software.md)
####### [Get discovered vulnerabilities](get-discovered-vulnerabilities.md)
####### [Get security recommendations](get-security-recommendations.md)
####### [Add or Remove machine tags](add-or-remove-machine-tags.md)
####### [Find machines by IP](find-machines-by-ip.md)
####### [Find machines by tag](find-machines-by-tag.md)
####### [Get missing KBs](get-missing-kbs-machine.md)
####### [Set device value](set-device-value.md)
####### [Update machine](update-machine-method.md)



###### [Machine Action]()
####### [Machine Action methods and properties](machineaction.md)
####### [List Machine Actions](get-machineactions-collection.md)
####### [Get Machine Action](get-machineaction-object.md)
####### [Collect investigation package](collect-investigation-package.md)
####### [Get investigation package SAS URI](get-package-sas-uri.md)
####### [Get live response result](get-live-response-result.md)
####### [Isolate machine](isolate-machine.md)
####### [Release machine from isolation](unisolate-machine.md)
####### [Restrict app execution](restrict-code-execution.md)
####### [Remove app restriction](unrestrict-code-execution.md)
####### [Run antivirus scan](run-av-scan.md)
####### [Run live response](run-live-response.md)
####### [Offboard machine](offboard-machine-api.md)
####### [Stop and quarantine file](stop-and-quarantine-file.md)
####### [Cancel machine action](cancel-machine-action.md)

###### [Recommendation]()
####### [Recommendation methods and properties](recommendation.md)
####### [List all recommendations](get-all-recommendations.md)
####### [Get recommendation by ID](get-recommendation-by-id.md)
####### [Get recommendation by software](list-recommendation-software.md)
####### [List machines by recommendation](get-recommendation-machines.md)
####### [List vulnerabilities by recommendation](get-recommendation-vulnerabilities.md)

###### [Remediation activity]()
####### [Remediation activity methods and properties](get-remediation-methods-properties.md)
####### [Get one remediation activity by ID](get-remediation-one-activity.md)
####### [List all remediation activities](get-remediation-all-activities.md)
####### [List exposed devices of one remediation activity](get-remediation-exposed-devices-activities.md)

###### [Score]()
####### [Score methods and properties](score.md)
####### [List exposure score by machine group](get-machine-group-exposure-score.md)
####### [Get exposure score](get-exposure-score.md)
####### [Get device secure score](get-device-secure-score.md)

###### [Software]()
####### [Software methods and properties](software.md)
####### [List software](get-software.md)
####### [Get software by ID](get-software-by-id.md)
####### [List software version distribution](get-software-ver-distribution.md)
####### [List machines by software](get-machines-by-software.md)
####### [List vulnerabilities by software](get-vuln-by-software.md)
####### [Get missing KBs](get-missing-kbs-software.md)

###### [User]()
####### [User methods](user.md)
####### [Get user related alerts](get-user-related-alerts.md)
####### [Get user related machines](get-user-related-machines.md)

###### [Vulnerability]()
####### [Vulnerability methods and properties](vulnerability.md)
####### [List vulnerabilities](get-all-vulnerabilities.md)
####### [List vulnerabilities by machine and software](get-all-vulnerabilities-by-machines.md)
####### [Get vulnerability by ID](get-vulnerability-by-id.md)
####### [List machines by vulnerability](get-machines-by-vulnerability.md)

##### [How to use APIs - Samples]()
###### [Power Automate](api-microsoft-flow.md)
###### [Power BI](api-power-bi.md)
###### [Advanced Hunting using Python](run-advanced-query-sample-python.md)
###### [Advanced Hunting using PowerShell](run-advanced-query-sample-powershell.md)
###### [Using OData Queries](exposed-apis-odata-samples.md)


#### [Raw data streaming API]()
##### [Raw data streaming](raw-data-export.md)
##### [Stream advanced hunting events to Azure Events hub](raw-data-export-event-hub.md)
##### [Stream advanced hunting events to your storage account](raw-data-export-storage.md)


#### [SIEM integration]()
##### [Integrate SIEM tools with Microsoft Defender for Endpoint](configure-siem.md)
##### [Microsoft Defender for Endpoint detection fields](api-portal-mapping.md)
##### [Pull detections using SIEM REST API](pull-alerts-using-rest-api.md)
##### [Troubleshoot SIEM tool integration issues](troubleshoot-siem.md)

#### [Partners & APIs]()
##### [Partner applications](partner-applications.md)
##### [Connected applications](connected-applications.md)
##### [API explorer](api-explorer.md)

#### [Role-based access control]()
##### [Manage portal access using RBAC](rbac.md)
##### [Create and manage roles](user-roles.md)
##### [Create and manage device groups]()
###### [Using device groups](machine-groups.md)
###### [Create and manage device tags](machine-tags.md)







### [Managed security service provider (MSSP) integration]()
#### [Configure managed security service provider integration](configure-mssp-support.md)
#### [Supported managed security service providers](mssp-list.md)
#### [Grant MSSP access to the portal](grant-mssp-access.md)
#### [Access the MSSP customer portal](access-mssp-portal.md)
#### [Configure alert notifications](configure-mssp-notifications.md)
#### [Get partner application access](exposed-apis-create-app-partners.md)
#### [Fetch alerts from customer tenant](fetch-alerts-mssp.md)
#### [Managed security service provider opportunity](mssp-support.md)
### [Partner integration scenarios]()
#### [Technical partner opportunities](partner-integration.md)
#### [Become a Microsoft Defender for Endpoint partner](get-started-partner-integration.md)
### [Integrations]()
#### [Microsoft Defender for Endpoint integrations](threat-protection-integration.md)
#### [Protect users, data, and devices with conditional access](conditional-access.md)
#### [Microsoft Cloud App Security integration overview](microsoft-cloud-app-security-integration.md)

### [Information protection in Windows overview]()
#### [Windows integration](information-protection-in-windows-overview.md)

### [Access the Microsoft Defender for Endpoint Community Center](community.md)

### [Helpful resources](helpful-resources.md)

## [Troubleshoot]()
### [Troubleshoot sensor state]()
#### [Check sensor state](check-sensor-status.md)
#### [Fix unhealthy sensors](fix-unhealthy-sensors.md)
#### [Inactive devices](fix-unhealthy-sensors.md#inactive-devices)
#### [Misconfigured devices](fix-unhealthy-sensors.md#misconfigured-devices)
#### [Review sensor events and errors on machines with Event Viewer](event-error-codes.md)

### [Troubleshoot sensor health issues using Client Analyzer]()
#### [Client analyzer overview](overview-client-analyzer.md)
#### [Download and run the client analyzer](download-client-analyzer.md)
#### [Run the client analyzer on Windows](run-analyzer-windows.md)
#### [Run the client analyzer on macOS or Linux](run-analyzer-macos-linux.md)
#### [Data collection for advanced troubleshooting on Windows](data-collection-analyzer.md)
#### [Understand the analyzer HTML report](analyzer-report.md)
#### [Provide feedback on the client analyzer tool](analyzer-feedback.md)

 

### [Troubleshoot Microsoft Defender for Endpoint service issues]()
#### [Troubleshoot service issues](troubleshoot-mdatp.md)
#### [Check service health](service-status.md)
#### [Contact Microsoft Defender for Endpoint support](contact-support.md)

### [Troubleshoot live response issues](troubleshoot-live-response.md)

### [Collect support logs using LiveAnalyzer](troubleshoot-collect-support-log.md)

### [Troubleshoot attack surface reduction issues]()
#### [Network protection](troubleshoot-np.md)
#### [Attack surface reduction rules](troubleshoot-asr.md)
#### [Migrate to Attack surface reduction rules](migrating-asr-rules.md)

# [Microsoft 365 Defender](../defender/index.yml)
# [Defender for Office 365](../office-365-security/index.yml)
# [Defender for Identity](/defender-for-identity/)
