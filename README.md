# Q-SYS-Bose-PowerMatch-Amplifier

- Created to extract information from the Q-Sys Bose PowerMatch Plugin
  - Using a Plugins 'Component Controls' you can pass data to a text controller using Named Components.
  - "Tools->View Component Controls Info..." will show you the available controls associated with the Plugin.
  - Dock this tool box over the Design Elements area then highlight the Plugin you want to interrogate.

- 'Component Name' must be the same as the Bose PowerMatch plugin component.
- Tool adds the IP Address, and Fault to the Status.Sting for the Monitoring Proxy, so the IP Address of the
device is visible on Reflect/Core Manager.


- PM4500N vs PM8500N
 - When the PM4500N (4 channel) amp is selected the plugin will use Output 5 (Output Channel Fault) as the overall amplifier failure indicator.
 - When the PM8500N (8 channel) amp is selected the plugin will use Output 9 (Output Channel Fault) as the overall amplifier failure indicator.	

![powermatch](https://user-images.githubusercontent.com/98933978/186787948-f7fd7ef1-91f7-4f82-9bc0-5d2cdf99d860.JPG)
