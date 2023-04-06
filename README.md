## ND_npwd_quickpack



![NDFramework Help Guide (5)](https://user-images.githubusercontent.com/112611821/230280684-7df9ad70-1768-4231-8ac9-c45647a3a637.png)







First, download the ZIP folder containing the necessary resources for the pack.

Extract the contents of the ZIP folder to a convenient location on your computer.
Navigate to the extracted folder and locate the "resources" folder.
Copy the "resources" folder and paste it into your server's "resources" folder, which should be located in your server's main directory.

Open your server.cfg file using a text editor.
Add this to your server.cfg for PMA-VOICE.
This must be placed before resources.

Server.cfg Voice config
setr voice_useNativeAudio true
setr voice_useSendingRangeOnly true
setr voice_defaultCycle "GRAVE"
setr voice_defaultVolume 0.3
setr voice_enableRadioAnim 1
setr voice_syncData 1

Next, add the following start priority to your server.cfg

Finally, import the SQL file found in the npwd folder to your MYSQL database. This can typically be done using a tool like PHPMyAdmin or the MySQL command-line interface. Make sure to create a new database if one doesn't already exist for the npwd data.

Save your server.cfg file and start or restart your server.

# Congratulations! You have now successfully installed the resource-pack and are ready to use its contents on your server. Remember to double-check your configurations and settings to ensure everything is working as expected.


## NDFramework Discord
https://discord.gg/andys-development-857672921912836116
## NDFramework GitHub
https://github.com/ND-Framework
