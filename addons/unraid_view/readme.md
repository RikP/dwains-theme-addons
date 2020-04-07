# UnRAID Monitoring View for Dwains-Theme
#### Version 0.1

![unraid-monitor](https://github.com/noodlemctwoodle/homeassistant/blob/master/www/images/github/views/unraid.png)

### UnRAID Data Monitoring Feeds

| [UnRAID-API](https://github.com/noodlemctwoodle/homeassistant/blob/master/packages/ha-core/areas/cabinet/devices/unraid/readme.md#unraid-api-configuration) | [UnRAID-SNMP](https://github.com/noodlemctwoodle/homeassistant/blob/master/packages/ha-core/areas/cabinet/devices/unraid/readme.md#unraid-snmp-configuration) | [UnRAID Glances Container](https://github.com/nicolargo/glances) |
|-----------------------|-----------------|--------------------------------|
| View arrayStatus      | HDD Array Temps | View total per disk used space |
| View arrayProtection  | LAN Throughput  | View total per disk free space |
| Total arrayDiskSpace  | Disk Space      | View CPU usage                 |
| Start/Stop Containers | CPU Load        | View RAM usage                 |

Version 0.1
 - Initial view
 - Glances container support
 - Glances Home Assistant Integration
 - Added swipe card for docker containers
 - UnRAID-API added
 - Container Support
 - Added SNMP [config](https://github.com/noodlemctwoodle/homeassistant/blob/b2b1bed306b16d1366f25835d2840cea42f72352/packages/ha-core/areas/cabinet/devices/unraid/unraid_monitoring.yaml#L36)
 - combined disk usage into swipe card
 - Added HDD temperatures to temperatures swipe-card
 - Added LAN Throughput bar graph to resources swipe-card
 - Removed Tap actions on mini-graph-card and bar-card
 - Fixed graph height issue on swipe-card
 - Added bullets to swipe card and removed progress bar
 - Fixed template issue on 'Array Usage' when Home Assistant gets value of unavailable or none
 - Fixed issue with bar-card border radius
 - Fixed Mini-Graph-Card line colours
 - Fixed Font Size Bar-Card Colour overlap issue


 Dwains-Theme UnRAID view can be found [here](https://github.com/noodlemctwoodle/homeassistant/blob/master/user_content/views/computers_user_content.yaml)

 #### Credits
 - [Dwain](https://github.com/dwainscheeren/lovelace-dwains-theme) Thanks for your assistance and ideas on this :)
 - [Stephan](https://github.com/Stephan296) Thanks for creating the version sensor curl request and exploring the correct configuration for the UnRAID-API.
 - [ElectricBrainUK](https://github.com/ElectricBrainUK/UnraidAPI) Thanks for creating this API for us to use and making this dashboard possible
 - [123](https://community.home-assistant.io/u/123/summary) Thanks for solving the problem with parenthesis
 - [Avi](https://github.com/abeksis/My-HomeAssistant-Config) Thanks for creating the awesome graphics used in v0.1 containers swipe-card and also providing code snips. 


### Donations

If you like my work please feel free to buy me a coffee

<a href="https://www.buymeacoffee.com/noodlemctwoodle" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>