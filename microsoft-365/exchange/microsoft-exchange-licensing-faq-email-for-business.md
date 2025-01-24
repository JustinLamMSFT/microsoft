# Exchange licensing FAQs

The following FAQ provides answers to common questions about licensing Exchange.

.heading-bg-color-layout-container-uidd681{ background-color: !important; }

## Transitioning between Exchange Server versions

Expand all | Collapse all

- ### Do I get rights to the Outlook client when I buy Exchange Server 2019 licenses?
    
    No, the Outlook client license was no longer included with any Exchange CAL after Exchange Server 2003, and must be purchased separately for Exchange Server 2019. The Exchange Server 2019 Standard CAL provides the rights to access e-mail, calendar, contacts, and tasks through either Outlook on the web, or through a mobile device via Exchange ActiveSync.
    

.heading-bg-color-layout-container-uid9d3e{ background-color: !important; }

## Server pricing and licensing

Expand all | Collapse all

- ### Does the Enterprise CAL require the Enterprise Server or vice versa?
    
      
    No. Both the Standard and Enterprise CALs can be used with either server edition.
    
- ### What are the licensing implications if I choose to run Exchange Server 2019 on a virtual machine rather than directly on a physical server?
    
      
    One server license is required for each running instance of Exchange Server 2019—whether it is installed natively on a physical machine or a virtual machine [Learn more about virtualization support](https://go.microsoft.com/fwlink/p/?LinkId=401231)
    
- ### Is there an External Connector license for Exchange Server 2019 for companies that want to offer email to non-employees such as corporate alumni or retirees (that is, “external users”)?
    
      
    No. External users do not require CALs to access Exchange Server 2019; access rights to standard Exchange functionality by external users is included with the Exchange Server 2019 license itself.
    
- ### If several users share the same desktop, do they each need an Exchange Enterprise CAL?
    
      
    Customers may still license Exchange Server 2019 with either per-user or per-device CALs. If several users share a desktop and do not individually access the Exchange server from other locations, such as their home PCs, then they can be licensed with one device CAL.
    
- ### Are there any licensing prerequisites for Exchange Server 2019 or CALs?
    
      
    Yes. For more information, see [Exchange Server 2019 prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=618325).
    
- ### Can a customer purchase certain features like the In-Place Archive separately from the Enterprise CAL?
    
      
    Customers can get the In-Place Archive and In-Place Hold features through Exchange Online Archiving for Exchange Server, and they can get advanced security through Exchange Online Protection. All other premium features are only available in the Enterprise CAL or E-CAL Suite.
    
- ### Are services still included with the Enterprise CAL?
    
      
    Yes. Customers are charged annually for subscriptions to Exchange Online Protection to protect their users from viruses and spam, and Data Loss Prevention (DLP) in Exchange Online (collectively “Services”). Customers may also choose to purchase the Exchange Enterprise CAL without Services if they do not need DLP or anti-virus and anti-spam protection.
    
- ### Can I purchase the Enterprise CAL without services?
    
      
    If purchased in Open, the Exchange Enterprise CAL is available either with or without Services. If purchased in Select, customers have two options. They can buy the License (L-only) and get the CAL without Software Assurance or Services. Or if they want Software Assurance (L&SA), they must also buy the Services.
    

.heading-bg-color-layout-container-uid7ada{ background-color: !important; }

## Exchange Online pricing and licensing

Expand all | Collapse all

- ### How is Exchange Online licensed?
    
      
    Exchange Online is licensed via a subscription model in which each user needs a User Subscription License (USL). Three types of subscriptions are available: Exchange Online Kiosk, Exchange Online Plan 1, and Exchange Online Plan 2. These subscriptions can be purchased on their own or as part of a Microsoft 365 plan that includes SharePoint Online, OneDrive, and Microsoft 365 Apps for enterprise.
    
- ### Where can I find detailed information about the different subscription types in Exchange Online?
    
      
    To compare the different plans, see [comparing Exchange Online plans](https://www.microsoft.com/en-us/microsoft-365/exchange/compare-microsoft-exchange-online-plans). Or, for more detail, see the [Exchange Online service description](https://go.microsoft.com/fwlink/p/?LinkId=401232).
    
- ### Do conference rooms require subscriptions? Is there a limit to the number of them?
    
      
    No. Resource mailboxes, including Room Mailboxes and Equipment Mailboxes, are special mailbox types that are provided free of charge as part of Exchange Online. There is no limit to the number of conference room subscriptions.
    
- ### Do shared mailboxes require subscriptions?
    
    No. Shared mailboxes don’t have login credentials, so they are only accessible by licensed users who have been granted delegate access (full mailbox permission, send as, or send on behalf of).
    
    Shared mailboxes do not include a personal archive or legal hold capabilities. If you need these features, then you can purchase either Exchange Online Plan 1 or Plan 2 and assign it to the shared mailbox.
    
    There is no limit to the number of shared mailboxes though the size is limited to 50GB. If you require a shared mailbox that is larger than 50GB, an Exchange Online Plan 2 license will need to be assigned to it.
    
- ### Can I enable In-Place Archive for a shared mailbox?
    
    You must assign the shared mailbox to either an Exchange Online Plan 1 plus Exchange Online Archiving subscription, or to an Exchange Online Plan 2 subscription in order to enable In-Place Archive. A shared mailbox can’t be used to archive email for an organization, except for those messages that are sent from the shared mailbox or received by the shared mailbox.
    
    An In-Place Archive can only be used to archive mail for a single user or entity for which a license has been applied. Using an In-Place Archive as a means to store mail from multiple users or entities is prohibited. For example, IT administrators cannot create shared mailboxes and have users copy (via CC or Transport rule) a shared mailbox for the explicit purpose of archiving.
    
- ### Can I put a shared mailbox on In-Place Hold?
    
      
    You must assign the shared mailbox an Exchange Online Plan 2 subscription in order to put it on In-Place Hold.
    
- ### Do mailboxes used to send email via SMTP (such as those used by line of business applications and on-premises appliances) require subscriptions?
    
      
    Yes, these mailboxes require a subscription. The subscription type can be Exchange Online Kiosk or Exchange Online Plan 1 or Plan 2.  
      
    
- ### Do Discovery Search Mailboxes (used to store multi-mailbox search results) require subscriptions?
    
      
    No. For more information about Discovery Search Mailboxes, see [create a Discovery Mailbox to store search results](https://go.microsoft.com/fwlink/p/?LinkID=532697).
    
- ### What are the licensing requirements for public folder mailboxes in Exchange Online?
    
      
    Public folder mailboxes are available to users with Exchange Online Plan 1 and Plan 2 subscriptions. They are not available for Exchange Online Kiosk users.
    
- ### Can I use journaling or transport rules to copy messages to an Exchange Online mailbox for the purpose of archiving?
    
      
    No. Using journaling, transport rules, or auto-forwarding rules to copy messages to an Exchange Online mailbox for dual-delivery purposes is not permitted. To preserve messages, you must put user content on In-Place Hold, or journal the messages to an external journal target.
    
- ### Is there a limit on how long messages are stored in the primary mailbox or the archive?
    
      
    There are no limits on the duration of retention policy. You can set the retention duration based on your business needs.
    
- ### What is the meaning of "unlimited storage" in Exchange Online Plan 2?
    
      
    The In-Place Archive feature in Exchange Online Plan 2 provides unlimited storage of email data for one user. The In-Place Archive has a default quota that is large enough to accommodate reasonable use, including the import of one user’s historical email. In the unlikely event that a user reaches this quota, Microsoft 365 automatically increases the size of the archive, which means that users won't run out of mailbox storage space and administrators won't have to request additional storage for archive mailboxes.
    
- ### If a user leaves my company, and I need to retain a copy of the data in their mailbox and In-Place Archive, what are my options?
    
    You have several options:  
    • You can export that user’s data to a PST file and store it on-premises.  
    • You can retain the data in that user’s mailbox by placing the user on In-Place Hold and marking the mailbox as inactive, as [described here](https://go.microsoft.com/fwlink/p/?LinkId=401236). It isn’t necessary to maintain a user subscription license for the inactive mailbox.  
    • If you have a hybrid deployment of Exchange Server and Exchange Online, you can migrate the mailbox back on-premises. Learn more about hybrid deployments [here](https://go.microsoft.com/fwlink/p/?LinkID=532698).
    
- ### What features aren't available to Exchange Online Kiosk users?
    
      
    Exchange Online Kiosk is designed for users who require fewer messaging features because they do not have dedicated computers. The subscription provides 2 GB of mailbox space per user and web-based access through Outlook on the web. Certain features are disabled for Kiosk users, including inbox rules, public folder mailboxes, site mailboxes, and delegate access to other mailboxes. For more information, see the [Exchange Online service description](https://go.microsoft.com/fwlink/p/?LinkId=401232).
    
- ### Do Kiosk user subscriptions include capabilities like In-Place eDiscovery and custom retention policies?
    
      
    Yes, all Exchange Online subscriptions, including Exchange Online Kiosk, allow organization-wide capabilities such as In-Place eDiscovery, journaling, custom retention policies, and premier anti-spam and anti-malware filtering via Exchange Online Protection.
    
- ### Do Kiosk users have different geo-redundancy and uptime service level agreements (SLA) than other subscription types?
    
      
    Users with Kiosk mailboxes are protected by the same uptime SLA and geo-redundancy protection as other Exchange Online mailboxes.
    
- ### Can I put a Kiosk mailbox on In-Place Hold?
    
      
    In order to place a Kiosk mailbox on In-Place Hold, you must upgrade it to Exchange Online Plan 2 or purchase the Exchange Online Archiving for Exchange Online add-on.
    
- ### Can I upgrade a user from Exchange Online Plan 1 to Exchange Online Plan 2?
    
      
    Yes. In the Microsoft Online Services Portal, you can assign the user a new subscription and remove the old one. This will automatically update the user’s capabilities in Exchange Online. The procedure for purchasing new subscriptions and cancelling old ones varies; check your specific license agreement for details.
    
- ### Can I downgrade a user from Exchange Online Plan 2 to Exchange Online Plan 1?
    
    Yes. In the Microsoft Online Services Portal, you can assign the user a new subscription and remove the old one. This will automatically update the user’s capabilities in Exchange Online. For the smoothest transition, you should remove any In-Place Holds from the user’s mailbox prior to assigning them the new subscription. The downgrade behavior is as follows:
    
    • Mailbox data: All data in the user’s mailbox and archive is preserved. If the user has a total of more than 50 GB of data in the primary mailbox plus the archive, the conversion will succeed, but the mailbox will be out of compliance from a licensing perspective until the excess data is deleted by the user.  
    • In-Place Hold: If the mailbox is on In-Place Hold, the hold remains in place. The mailbox will be out of compliance from a licensing perspective until the In-Place Hold is cleared. If you are using Directory Sync, you can clear the In-Place Hold by updating the user's Active Directory object, otherwise you must call support to have it cleared.  
    • Hosted voice mail: This feature is automatically disabled for the user as part of the transition.
    
    The procedure for purchasing new subscriptions and cancelling old ones varies; check your specific license agreement for details.
    
- ### Can I downgrade a user from Exchange Online Plan 1 to Exchange Online Kiosk?
    
    Yes. In the Microsoft Online Services Portal, you can assign the user a new subscription and remove the old one. This will automatically update the user’s capabilities in Exchange Online. For the smoothest transition, you should delete the user’s inbox rules and SMS notifications prior to assigning them the new subscription. The downgrade behavior is as follows:
    
    •Mailbox size: If the size exceeds 2 GB, the action will fail.  
    • Inbox rules: Existing inbox rules are left in place but they are not editable. You can call Microsoft 365 support and have them delete the user's rules on your behalf in order to bring the mailbox into compliance with licensing terms.  
    • SMS notifications: Existing SMS notifications are left in place, but new ones can’t be created. You can call Microsoft 365 support and have them delete the user’s existing SMS notifications in order to bring the mailbox into compliance with licensing terms.
    
    The procedure for purchasing new subscriptions and cancelling old ones varies; check your specific license agreement for details.
    
- ### If my organization is Hybrid with Microsoft 365 and I do not host mailboxes on-premises, do I still need to license Exchange Server?
    
    If you do not host any mailboxes on the servers used to connect to Microsoft 365 you can license them using the Microsoft 365 Hybrid Configuration Wizard (HCW) which you can find [here](https://go.microsoft.com/fwlink/p/?linkid=2095076) .The HCW validates your Microsoft 365 subscription and installs the appropriate licenses on your servers.    
    
- ### If I have already licensed a server using a Hybrid key, and I want to re-license it with a Standard Edition key or Enterprise Edition key, how do I do that?
    
    You can use PowerShell to enter the new product key.
    
- ### If I have some users hosted in Exchange Online, and some users on-premises, can I point my MX record at Microsoft 365 instead of my on-premises servers? If so, do I need Exchange Online Protection subscriptions for the on-premises users?
    
    You can point your MX record to Exchange Online in a hybrid deployment. In this scenario, Exchange Online Protection (EOP) provides anti-spam and anti-malware filtering on inbound mail for the on-premises users, so these on-premises users require EOP subscriptions.
    
- ### Are there any restrictions on delegating access to a user mailbox (or shared mailbox) to others?
    
    A user with an F1 license cannot configure delegates to their own mailbox, but they can access another mailbox (including shared mailboxes) and perform any actions which have been delegated to them.
    

.heading-bg-color-layout-container-uide9ae{ background-color: !important; }

## Exchange resources

- [Exchange Online Protection](https://www.microsoft.com/en-us/microsoft-365/exchange/exchange-email-security-spam-protection)
    
- [Exchange Online Archiving](https://www.microsoft.com/en-us/microsoft-365/exchange/microsoft-exchange-online-archiving-email)
    
- [Information for IT pros](https://go.microsoft.com/fwlink/p/?LinkID=401219&clcid=0x409&culture=en-us&country=US)
    
- [Information for IT partners](https://go.microsoft.com/fwlink/p/?LinkID=616592&clcid=0x409&culture=en-us&country=US)
    

.heading-bg-color-layout-container-uid52a6{ background-color: !important; }