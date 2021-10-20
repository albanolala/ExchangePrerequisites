# Set Exchange Prerequisites
*This script will help you in Exchange Server 2016 and 2019 prerequisites install process. This script is without mine or Microsoft's garranty. Execution and management of the script is therefore under your direct responsibility.*

## Overview

This script is intended to help you install all Exchange server 2016 and 2019 prerequisites. The prerequisites include all the components you need to install on windows server plus the best practices we recommend before installing Exchange server. For example: Disabling SMB 1.0, paging file configuration etc ..


## Instructions

To execute this script you need to be ad least a local admin of the machine in wich you are going to install Exchange.
You will have to execute a powershell session as admin, move to the path in wich you've saved the ps1 file and execute it in this way:

".\Set-ExchangePrerequisites.ps1"

## Script overview after execution

*This script checks the OS Version and than calles the function of each version of Exchange Server and OS. Exchange server 2016 can be installed on Windows 2012,2012R2 or 2016 and Exchange 2019 on Windows 2019. At his part Windows Server 2019 supports only Exchange server 2019.*

![image](https://user-images.githubusercontent.com/86245948/138175005-779c14c0-f060-4717-9282-d1292e59abc7.png)


## Exchange Server supportability matrix

![image](https://user-images.githubusercontent.com/86245948/138174515-4e304671-975c-44fb-b0a0-9c0494152af5.png)
