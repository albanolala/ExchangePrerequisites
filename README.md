# Set Exchange Prerequisites
*This script will help you in Exchange Server 2016 and 2019 prerequisites install process. This script is without mine or Microsofts garranty. Execution and management of the script is therefore under your direct responsibility.*

## Overview

This script is intended to help you install all Exchange server 2016 and 2019 prerequisites. The prerequisites include all the components you need to install on windows server plus the best practices we recommend before installing Exchange server. For example: Disabling SMB 1.0, paging file configuration etc ..


## Instructions

To execute this script you need to be ad least a local admin of the machine in wich you0re going to install Exchange. 
You will have to execute a powershell session as admin, move to the path in wich you've saved the ps1 file and execute it in this way:

".\Set-ExchangePrerequisites.ps1"
