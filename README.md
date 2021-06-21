# GTM Base Container
This repository contains the GTM base container, a [Design System](https://designsystem.gov.au/) based GTM configuration compatible with Google Analytics for the Australian Government.
The base container template was constructed by Data Runs Deep, and is maintained/regularly updated by the DTA Observatory Team.

**Setup instructions**
1. Download the .json file from this repository
2. Head into **tagmanager.google.com -> Admin -> Container -> Import Container**
3. Click "Choose container file" and locate the above JSON on your local machine
4. Click "Choose workspace". We recommend **Existing -> Default Workspace**
5. Choose an import option. Choose "**Merge**" if you have existing tags and triggers you wish to keep, otherwise choose "**Overwrite**".
6. Review all the changes and click "**Save**" to add the base container to your website.
7. Go into "Folders" and modify the values under **[BC] #1 - GTM - Configuration - Core (10)** and **[BC] #2 - GTM - Configuration - Design System** to match your website's specifications and CSS selectors. 

**Further assistance**

We have more detailed documentation available at https://docs.google.com/document/d/1wii12j_z7rpddVFnn0YaOZjHmnZPD8mzVkjca6Buo7U. 
Please send us an email at [observatory@dta.gov.au](mailto:observatory@dta.gov.au) to gain access to this document.
