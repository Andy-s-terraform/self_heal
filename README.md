# self_heal
I created the windows batch first as the older servers the application was on did not have powershell installed. I then created the powershell script once the application was remediated.


Both scripts were created to look in a ‘failed transfer’ folder to check for files, any files found were then re-named appropriately, placed into the transfer folder and the service would be re-started.

The scripts were set to run at a certain time so that the files were ingested in time for no loss of service. 

A readable log was created for support needs
