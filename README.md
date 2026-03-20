# DeviceSettings-StartMenu-and-Taskbar

This repository contains the necessary configuration files for managing device settings related to the Start Menu and Taskbar within Microsoft Intune. These settings can be applied to Windows devices to create a standardized and controlled user experience.

## Configuration Files

- **Start-Layout.xml**: This XML file defines the layout of the Start Menu, including pinned items and group arrangements.
- **Configure-Start-Pins.json**: This JSON file provides configuration for pinned items within the Start Menu, allowing for customization and control.

## Usage
1. Make a Configuration Profile
2. Select Settings Catalog
3. Search for "Start"
4. Then the Configure-Start-Pins.json needs to be configured in "Configure Start Pins"
5. Then the Start-Layout.xml needs to be configured in "Start Layout"
6. Save the profile and assign to a group

### Start-Layout.xml

1. Modify the `Start-Layout.xml` file to fit your organization's needs.
2. Import the XML file into your Intune configuration profile.
3. Assign the profile to the desired user groups.

### Configure-Start-Pins.json

1. Edit the `Configure-Start-Pins.json` file to configure the pinned items.
2. Import the JSON file into your Intune configuration profile.
3. Assign the profile to the desired user groups.

## Contributing

Feel free to fork this repository or submit pull requests for any improvements or additional functionalities.

## Support

If you encounter any issues or have any questions, please open an issue on GitHub or contact the repository maintainer.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Additional Resources

- [Intune Start Menu Documentation](https://learn.microsoft.com/en-us/mem/intune/)
- [Windows Start Menu Customization](https://learn.microsoft.com/en-us/windows/configuration/start-layout-xml-desktop)

---

**Note:** Please ensure to consult your organization's policies and guidelines before implementing any changes to device settings.
