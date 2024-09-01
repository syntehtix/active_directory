# 01 Installing the Domain Controller

1. Use 'sconfig' to:
    - Change hostname
    - Change IP to static
    - Change DNS to own IP

2. Install Active Directory Windows Feature

''''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
''''