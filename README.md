## Getting Started:


###### Description

Amazon Web Services (abbreviated AWS) is a collection of remote computing services (also called web services) that together make up a cloud computing platform, offered over the Internet by Amazon.com. 
The most central and well-known of these services are Amazon EC2 and Amazon S3. 
The service is advertised as providing a large computing capacity (potentially many servers) much faster and cheaper than building a physical server farm.
	
###### Actions

1.  Allocate Elastic IP Address
2.  Associate/Disassociate Elastic IP Address
3.	Associate/Disassociate Route Table
4.	Attach/Detach Internet Gateway to VPC
5.	Attach/Detach Network Interface
6.	Attach/Detach EBS volume to instance
7.	Add rule to security group
8.	Create/Delete Security Group
9.	Create Instance
10.	Create/Delete Internet Gateway
11.	Create Network ACL in a VPC
12.	Create/Delete Network ACL Entry
13.	Create/Delete Network Interface
14.	Create/Delete Route
15.	Create Route Table
16.	Create Subnet
17.	Create/Delete EBS Volume
18.	Create/Delete VPC
19.	Allocate and Associate VPC Address
20.	Delete Network ACL
21.	Describe Addresses
22.	Modify Attribute of Instance
23.	Release Elastic IP Address
24.	Replace Network ACL Association
25.	Replace Route
26.	Replace Route Table Association
27.	Remove rule from security group
28.	Start/Stop Instance
29.	Terminate Instance	

###### Compatibility:

1. On the executing agent the java and the Amazon EC2 API Tools must be installed and JAVA_HOME and EC2_HOME must be defined.
2. Download Amazon EC2 API Tools from Amazon S3 https://aws.amazon.com/items/351?externalID=351
	

###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. ITPA Shared Action Pack should be installed. 

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):

Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**


###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_AMAZON.PUB.DOC.xml)

###### Third party licenses:

The third-party library and license document reference.[Third party licenses](source/ae/DOCUMENTATION/PCK.AUTOMIC_AMAZON.PUB.LICENSES.xml)

###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)
