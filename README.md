# WordPress Plugin Boilerplate

## Description
This is a boilerplate for creating a WordPress plugin. It is based on [DevinVinson's WordPress Plugin Boilerplate](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) with some code style changes to fit our preferences.

## Features
- Basic plugin structure
- Example hooks and filters
- Sample settings page
- Localization support

## Installation
1. Download the plugin files.
2. Upload the plugin folder to the `/wp-content/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.

## Usage
1. Customize the plugin files to suit your needs.
2. Add your custom functionality in the appropriate files.
3. Use the provided hooks and filters to extend WordPress functionality.

## File Structure
plugin-name/ ├── includes/ │ ├── class-plugin-name-activator.php │ ├── class-plugin-name-deactivator.php │ └── class-plugin-name.php ├── languages/ │ └── plugin-name.pot ├── admin/ │ ├── class-plugin-name-admin.php │ └── css/ │ └── plugin-name-admin.css │ └── js/ │ └── plugin-name-admin.js ├── public/ │ ├── class-plugin-name-public.php │ └── css/ │ └── plugin-name-public.css │ └── js/ │ └── plugin-name-public.js ├── uninstall.php ├── plugin-name.php └── readme.txt

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This plugin is licensed under the GPLv2 or later.

## Credits
- [DevinVinson's WordPress Plugin Boilerplate](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate)
- [Matthew Ediger](https://wonderjarcreative.com)
