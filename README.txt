# WordPress Plugin Boilerplate
Contributors: edigermatthew  
Donate link: https://example.com/  
Tags: webhooks, integration, optimantra, zoho, vivewell  
Requires at least: 3.0.1  
Tested up to: 3.4  
Stable tag: 0.1.0  
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  

Boilerplate wordpress plugin.

## Description
This is a boilerplate for creating a WordPress plugin. It is based on DevinVinson's WordPress Plugin Boilerplate (https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) with some code style changes to fit our preferences.

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
- DevinVinson's WordPress Plugin Boilerplate (https://github.com/DevinVinson/WordPress-Plugin-Boilerplate)


== Changelog ==

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog (https://keepachangelog.com/en/1.0.0/),
and this project adheres to Semantic Versioning (https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-11-26
= Added =
- Added boilerplate files.
- Added `README.md`.
- Added `CHANGELOG.md`.