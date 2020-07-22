# Netbox templates for Ubiquiti UniFi

Ubiquiti Unifi device type templates for NetBox

Note: Most templates in this repo have been merged over to [netbox-community/devicetype-library](https://github.com/netbox-community/devicetype-library/tree/master/device-types/Ubiquiti) repo as well.

## Prequesition

Add manufacturer to NetBox, before importing the template.

Disclaimer: For the import templates to work, the name has to be *Ubiquiti*.

### Manual way

Go to *Menu > Devices > Manufacturers* and press **Add**

Set follow values:
* **Name** value to *Ubiquiti*
* **Slug** value to *ubiquiti*

Press **Create**

### Import way

Go to *Menu > Devices > Manufacturers* and press **Import**

Paste in following input:
```
name,slug
Ubiqiti,ubiqiti
```

Press **Submit**

## Import of templates

Go to *Menu > Devices > Device Types* and press **Import**

Copy the content of [netbox_ubiquiti_devicetypes.yaml](netbox_ubiquiti_devicetypes.yaml) file and paste it into **Data** textfield.

Select *YAML* as **Format** (should be default).

Press **Submit**

## List of Ubiquiti UniFi devices

* UniFi AC In-Wall *(UAP-AC-IW)*
* UniFi AC In-Wall Pro *(UAP-AC-IW-PRO)*
* UniFi AP (legacy) *(UAP)*
* UniFi AP AC EDU *(UAP-AC-EDU)*
* UniFi AP AC HD *(UAP-AC-HD)*
* UniFi AP AC Lite *(UAP-AC-LITE)*
* UniFi AP AC LR *(UAP-AC-LR)*
* UniFi AP AC Pro *(UAP-AC-PRO)*
* UniFi AP AC SHD *(UAP-AC-SHD)*
* UniFi AP Beacon HD *(UAP-BeaconHD)*
* UniFi AP Long-Range (legacy) *(UAP-LR)*
* UniFi AP Outdoor 5 (legacy) *(UAP-Outdoor5)*
* UniFi AP Outdoor+ (legacy) *(UAP-Outdoor+)*
* UniFi AP PRO (legacy) *(UAP-PRO)*
* UniFi AP XG *(UAP-XG)*
* UniFi Cloud Key *(UC-CK)*
* UniFi Cloud Key Gen2 *(UCK-G2)*
* UniFi Cloud Key Gen2 Plus *(UCK-G2-PLUS)*
* UniFi Dream Machine *(UDM)*
* UniFi Dream Machine Pro *(UDM-Pro)*
* UniFi Flex HD *(UAP-FlexHD)*
* UniFi HD In-Wall *(UAP-IW-HD)*
* UniFi Industrial Switch *(USW-Industrial)*
* UniFi LTE *(U-LTE)*
* UniFi nanoHD *(UAP-nanoHD)*
* UniFi NVR *(UVC-NVR-2TB)*
* UniFi Protect Network Video Recorder *(UNVR)*
* UniFi Security Gateway *(USG)*
* UniFi Security Gateway Pro 4 *(USG-PRO-4)*
* UniFi Switch 16 PoE Gen2 *(USW-16-POE)*
* UniFi Switch 16 XG *(US-16-XG)*
* UniFi Switch 16-150W *(US-16-150W)*
* UniFi Switch 24 *(US-24)*
* UniFi Switch 24 PoE Gen2 *(USW-24-POE)*
* UniFi Switch 48 *(US-48)*
* UniFi Switch 48 PoE Gen2 *(USW-48-POE)*
* UniFi Switch 8 *(US-8)*
* UniFi Switch 8-150W *(US-8-150W)*
* UniFi Switch 8-60W *(US-8-60W)*
* UniFi Switch Flex *(USW-Flex)*
* UniFi Switch Flex Mini *(USW-Flex-Mini)*
* UniFi Switch PoE 24-250W *(US-24-250W)*
* UniFi Switch PoE 24-500W *(US-24-500W)*
* UniFi Switch PoE 48-500W *(US-48-500W)*
* UniFi Switch PoE 48-750W *(US-48-750W)*
* UniFi Switch Pro 24 PoE Gen2 *(USW-Pro-24-POE)*
* UniFi Switch Pro 48 PoE Gen2 *(USW-Pro-48-POE)*
* UniFi Switch XG 6PoE *(US-XG-6POE)*
* UniFi Video Camera G3 *(UVC-G3)*
* UniFi Video Camera G3 AF *(UVC-G3-AF)*
* UniFi Video Camera G3 Bullet *(UVC-G3-BULLET)*
* UniFi Video Camera G3 Dome *(UVC-G3-DOME)*
* UniFi Video Camera G3 FLEX *(UVC-G3-FLEX)*
* UniFi Video Camera G3 Micro *(UVC-G3-MICRO)*
* UniFi Video Camera G3 PRO *(UVC-G3-PRO)*
* UniFi Video Camera G4 Bullet *(UVC-G4-BULLET)*
* UniFi Video Camera G4 PRO *(UVC-G4-PRO)*
* UniFi WiFi BaseStation XG *(UWB-XG)*
* UniFi WiFi BaseStation XG Black *(UWB-XG-BK)*
* UniFi XG Server *(UAS-XG)*

## License

MIT

## Author Information

Please send suggestion or pull requests to make this templates better. Also let me know if you encounter any issues.

Repo created in 2020 by [Tobias Lindberg](https://github.com/tobiasehlert)
