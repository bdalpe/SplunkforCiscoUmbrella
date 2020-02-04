Cisco Umbrella App for Splunk
=============================
### Description ###
The Cisco Umbrella App for Splunk provides dashboards and an interactive query exploration tool for reporting and analysis of Umbrella DNS logs. Quickly find security incidents, policy violations, and other DNS anomolies.

### Installing ###
Clone the Github repo to your `$SPLUNK_HOME/etc/apps` directory.

    git clone https://github.com/bdalpe/SplunkforCiscoUmbrella
    
Or download from Github and upload the zip file to your Splunk server using the App Manager in the UI.

By default, the Umbrella data model has acceleration disabled. To load dashboards faster, it is recommended to enable acceleration for at least the last 7 days.

### Prerequsities ###
You'll need to have the following installed for the app to work correctly. 

* [Umbrella Add-on for Splunk Enterprise](https://splunkbase.splunk.com/app/3629/)
* [URL Toolbox](https://splunkbase.splunk.com/app/2734/)

### Legal ###	
* Cisco, Cisco Umbrella, and the Umbrella Logo, are registred trademarks of Cisco.	
* The Orange OpenDNS Logo is a registered trademark of Cisco OpenDNS, LLC.	
* Company names, trademarks, and product logos are property of their respective owners. Use does not imply any affiliation or endorsement.
