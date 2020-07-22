# Netbox templates for Ubiquiti UniFi

Ubiquiti Unifi device type templates for NetBox

## Prequesition

Add manufacturer to NetBox, before importing the template.

Disclaimer: For the import templates to work, the name has to be *Ubiquiti Inc*.

### Manual way

Go to *Menu > Devices > Manufacturers* and press **Add**

Set follow values:
* **Name** value to *Ubiquiti Inc*
* **Slug** value to *ubiquiti*

Press **Create**

### Import way

Go to *Menu > Devices > Manufacturers* and press **Import**

Paste in following input:
```
name,slug
Ubiqiti Inc,ubiqiti
```

Press **Submit**

## Import of templates

Go to *Menu > Devices > Device Types* and press **Import**

Copy the content of netbox_ubiquiti_devicetypes.yaml file and paste it into **Data** textfield.

Select *YAML* as **Format** (should be default).

Press **Submit**

## License

MIT

## Author Information

Please send suggestion or pull requests to make this templates better. Also let me know if you encounter any issues.

Repo created in 2020 by [Tobias Lindberg](https://github.com/tobiasehlert)