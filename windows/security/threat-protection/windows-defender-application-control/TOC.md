# [Application Control for Windows](windows-defender-application-control.md)
## [WDAC and AppLocker Overview](wdac-and-applocker-overview.md)
### [WDAC and AppLocker Feature Availability](feature-availability.md)


## [WDAC design guide](windows-defender-application-control-design-guide.md)
### [Plan for WDAC policy lifecycle management](plan-windows-defender-application-control-management.md)
### Design your initial WDAC policy
#### [Understand WDAC policy design decisions](understand-windows-defender-application-control-policy-design-decisions.md)
#### [Understand WDAC policy rules and file rules](select-types-of-rules-to-create.md)
#### [Authorize apps deployed with a WDAC managed installer](use-windows-defender-application-control-with-managed-installer.md)
##### [Configure a WDAC managed installer](configure-wdac-managed-installer.md)
#### [Authorize reputable apps with Intelligent Security Graph (ISG)](use-windows-defender-application-control-with-intelligent-security-graph.md)
#### [Use multiple WDAC policies](deploy-multiple-windows-defender-application-control-policies.md)
#### [Microsoft recommended block rules](microsoft-recommended-block-rules.md)
### Create your initial WDAC policy
#### [Example WDAC base policies](example-wdac-base-policies.md)
#### [Policy creation for common WDAC usage scenarios](types-of-devices.md)
##### [Create a WDAC policy for lightly-managed devices](create-wdac-policy-for-lightly-managed-devices.md)
##### [Create a WDAC policy for fully-managed devices](create-wdac-policy-for-fully-managed-devices.md)
##### [Create a WDAC policy for fixed-workload devices](create-initial-default-policy.md)


## [Windows Defender Application Control deployment guide](windows-defender-application-control-deployment-guide.md)
### [Audit WDAC policies](audit-windows-defender-application-control-policies.md)
### [Merge WDAC policies](merge-windows-defender-application-control-policies.md)
### [Enforce WDAC policies](enforce-windows-defender-application-control-policies.md)
### [Deploy WDAC policies using Group Policy](deploy-windows-defender-application-control-policies-using-group-policy.md)
### [Deploy WDAC policies using Intune](deploy-windows-defender-application-control-policies-using-intune.md)
### [Allow COM object registration](allow-com-object-registration-in-windows-defender-application-control-policy.md)
### [Use WDAC with .NET hardening](use-windows-defender-application-control-with-dynamic-code-security.md)
### [Manage packaged apps with WDAC](manage-packaged-apps-with-windows-defender-application-control.md)
### [Use a Windows Defender Application Control policy to control specific plug-ins, add-ins, and modules](use-windows-defender-application-control-policy-to-control-specific-plug-ins-add-ins-and-modules.md)
### [Use code signing to simplify application control for classic Windows applications](use-code-signing-to-simplify-application-control-for-classic-windows-applications.md)
#### [Optional: Use the WDAC Signing Portal in the Microsoft Store for Business](use-device-guard-signing-portal-in-microsoft-store-for-business.md)
#### [Optional: Create a code signing cert for WDAC](create-code-signing-cert-for-windows-defender-application-control.md)
#### [Deploy catalog files to support WDAC](deploy-catalog-files-to-support-windows-defender-application-control.md)
### [Use signed policies to protect Windows Defender Application Control against tampering](use-signed-policies-to-protect-windows-defender-application-control-against-tampering.md)
### [Disable WDAC policies](disable-windows-defender-application-control-policies.md)
### [LOB Win32 Apps on S Mode](LOB-win32-apps-on-s.md)


## [Windows Defender Application Control operational guide](windows-defender-application-control-operational-guide.md)
### [Understanding Application Control events](event-id-explanations.md)
### [Query WDAC events with Advanced hunting](querying-application-control-events-centrally-using-advanced-hunting.md)

## [AppLocker](applocker\applocker-overview.md) 
### [Administer AppLocker](applocker\administer-applocker.md)
#### [Maintain AppLocker policies](applocker\maintain-applocker-policies.md)
#### [Edit an AppLocker policy](applocker\edit-an-applocker-policy.md)
#### [Test and update an AppLocker policy](applocker\test-and-update-an-applocker-policy.md)
#### [Deploy AppLocker policies by using the enforce rules setting](applocker\deploy-applocker-policies-by-using-the-enforce-rules-setting.md)
#### [Use the AppLocker Windows PowerShell cmdlets](applocker\use-the-applocker-windows-powershell-cmdlets.md)
#### [Use AppLocker and Software Restriction Policies in the same domain](applocker\use-applocker-and-software-restriction-policies-in-the-same-domain.md)
#### [Optimize AppLocker performance](applocker\optimize-applocker-performance.md)
#### [Monitor app usage with AppLocker](applocker\monitor-application-usage-with-applocker.md)
#### [Manage packaged apps with AppLocker](applocker\manage-packaged-apps-with-applocker.md)
#### [Working with AppLocker rules](applocker\working-with-applocker-rules.md)
##### [Create a rule that uses a file hash condition](applocker\create-a-rule-that-uses-a-file-hash-condition.md)
##### [Create a rule that uses a path condition](applocker\create-a-rule-that-uses-a-path-condition.md)
##### [Create a rule that uses a publisher condition](applocker\create-a-rule-that-uses-a-publisher-condition.md)
##### [Create AppLocker default rules](applocker\create-applocker-default-rules.md)
##### [Add exceptions for an AppLocker rule](applocker\configure-exceptions-for-an-applocker-rule.md)
##### [Create a rule for packaged apps](applocker\create-a-rule-for-packaged-apps.md)
##### [Delete an AppLocker rule](applocker\delete-an-applocker-rule.md)
##### [Edit AppLocker rules](applocker\edit-applocker-rules.md)
##### [Enable the DLL rule collection](applocker\enable-the-dll-rule-collection.md)
##### [Enforce AppLocker rules](applocker\enforce-applocker-rules.md)
##### [Run the Automatically Generate Rules wizard](applocker\run-the-automatically-generate-rules-wizard.md)
#### [Working with AppLocker policies](applocker\working-with-applocker-policies.md)
##### [Configure the Application Identity service](applocker\configure-the-application-identity-service.md)
##### [Configure an AppLocker policy for audit only](applocker\configure-an-applocker-policy-for-audit-only.md)
##### [Configure an AppLocker policy for enforce rules](applocker\configure-an-applocker-policy-for-enforce-rules.md)
##### [Display a custom URL message when users try to run a blocked app](applocker\display-a-custom-url-message-when-users-try-to-run-a-blocked-application.md)
##### [Export an AppLocker policy from a GPO](applocker\export-an-applocker-policy-from-a-gpo.md)
##### [Export an AppLocker policy to an XML file](applocker\export-an-applocker-policy-to-an-xml-file.md)
##### [Import an AppLocker policy from another computer](applocker\import-an-applocker-policy-from-another-computer.md)
##### [Import an AppLocker policy into a GPO](applocker\import-an-applocker-policy-into-a-gpo.md)
##### [Add rules for packaged apps to existing AppLocker rule-set](applocker\add-rules-for-packaged-apps-to-existing-applocker-rule-set.md)
##### [Merge AppLocker policies by using Set-ApplockerPolicy](applocker\merge-applocker-policies-by-using-set-applockerpolicy.md)
##### [Merge AppLocker policies manually](applocker\merge-applocker-policies-manually.md)
##### [Refresh an AppLocker policy](applocker\refresh-an-applocker-policy.md)
##### [Test an AppLocker policy by using Test-AppLockerPolicy](applocker\test-an-applocker-policy-by-using-test-applockerpolicy.md)
### [AppLocker design guide](applocker\applocker-policies-design-guide.md)
#### [Understand AppLocker policy design decisions](applocker\understand-applocker-policy-design-decisions.md)
#### [Determine your application control objectives](applocker\determine-your-application-control-objectives.md)
#### [Create a list of apps deployed to each business group](applocker\create-list-of-applications-deployed-to-each-business-group.md)
##### [Document your app list](applocker\document-your-application-list.md)
#### [Select the types of rules to create](applocker\select-types-of-rules-to-create.md)
##### [Document your AppLocker rules](applocker\document-your-applocker-rules.md)
#### [Determine the Group Policy structure and rule enforcement](applocker\determine-group-policy-structure-and-rule-enforcement.md)
##### [Understand AppLocker enforcement settings](applocker\understand-applocker-enforcement-settings.md)
##### [Understand AppLocker rules and enforcement setting inheritance in Group Policy](applocker\understand-applocker-rules-and-enforcement-setting-inheritance-in-group-policy.md)
##### [Document the Group Policy structure and AppLocker rule enforcement](applocker\document-group-policy-structure-and-applocker-rule-enforcement.md)
#### [Plan for AppLocker policy management](applocker\plan-for-applocker-policy-management.md)
### [AppLocker deployment guide](applocker\applocker-policies-deployment-guide.md)
#### [Understand the AppLocker policy deployment process](applocker\understand-the-applocker-policy-deployment-process.md)
#### [Requirements for Deploying AppLocker Policies](applocker\requirements-for-deploying-applocker-policies.md)
#### [Use Software Restriction Policies and AppLocker policies](applocker\using-software-restriction-policies-and-applocker-policies.md)
#### [Create Your AppLocker policies](applocker\create-your-applocker-policies.md)
##### [Create Your AppLocker rules](applocker\create-your-applocker-rules.md)
#### [Deploy the AppLocker policy into production](applocker\deploy-the-applocker-policy-into-production.md)
##### [Use a reference device to create and maintain AppLocker policies](applocker\use-a-reference-computer-to-create-and-maintain-applocker-policies.md)
###### [Determine which apps are digitally signed on a reference device](applocker\determine-which-applications-are-digitally-signed-on-a-reference-computer.md)
###### [Configure the AppLocker reference device](applocker\configure-the-appLocker-reference-device.md)
### [AppLocker technical reference](applocker\applocker-technical-reference.md)
#### [What Is AppLocker?](applocker\what-is-applocker.md)
#### [Requirements to use AppLocker](applocker\requirements-to-use-applocker.md)
#### [AppLocker policy use scenarios](applocker\applocker-policy-use-scenarios.md)
#### [How AppLocker works](applocker\how-applocker-works-techref.md)
##### [Understanding AppLocker rule behavior](applocker\understanding-applocker-rule-behavior.md)
##### [Understanding AppLocker rule exceptions](applocker\understanding-applocker-rule-exceptions.md)
##### [Understanding AppLocker rule collections](applocker\understanding-applocker-rule-collections.md)
##### [Understanding AppLocker allow and deny actions on rules](applocker\understanding-applocker-allow-and-deny-actions-on-rules.md)
##### [Understanding AppLocker rule condition types](applocker\understanding-applocker-rule-condition-types.md)
###### [Understanding the publisher rule condition in AppLocker](applocker\understanding-the-publisher-rule-condition-in-applocker.md)
###### [Understanding the path rule condition in AppLocker](applocker\understanding-the-path-rule-condition-in-applocker.md)
###### [Understanding the file hash rule condition in AppLocker](applocker\understanding-the-file-hash-rule-condition-in-applocker.md)
##### [Understanding AppLocker default rules](applocker\understanding-applocker-default-rules.md)
###### [Executable rules in AppLocker](applocker\executable-rules-in-applocker.md)
###### [Windows Installer rules in AppLocker](applocker\windows-installer-rules-in-applocker.md)
###### [Script rules in AppLocker](applocker\script-rules-in-applocker.md)
###### [DLL rules in AppLocker](applocker\dll-rules-in-applocker.md)
###### [Packaged apps and packaged app installer rules in AppLocker](applocker\packaged-apps-and-packaged-app-installer-rules-in-applocker.md)
#### [AppLocker architecture and components](applocker\applocker-architecture-and-components.md)
#### [AppLocker processes and interactions](applocker\applocker-processes-and-interactions.md)
#### [AppLocker functions](applocker\applocker-functions.md)
#### [Security considerations for AppLocker](applocker\security-considerations-for-applocker.md)
#### [Tools to Use with AppLocker](applocker\tools-to-use-with-applocker.md)
##### [Using Event Viewer with AppLocker](applocker\using-event-viewer-with-applocker.md)
#### [AppLocker Settings](applocker\applocker-settings.md)


