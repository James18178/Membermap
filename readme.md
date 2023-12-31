English | [简体中文](README_ch.md)

# Membermap
Project From: https://github.com/McAtze/-XT-Membermap
- This project is only optimized for Chinese users

## Functions
- Membermap based on Google Maps Geocode, JavaScript and Staticmap API
- The map use the default XenForo location field with OptIn for every user
- Permissions and map markers per user group
- Map marker clustering
- Choose between 4 different map types (Roadmap, Hybrid, Terrain and Satellite)
- Default map coordinates and zoom in options
- Enable/Disable POI on membermap
- Enable/Disable clustering on membermap
- Checking if Api key is valid/available when entering in options
- Minimize the api calls
- Static mini map per user in account an as widget available
- 3 different widgets are available (Stats, Legend and Minimap (User based))
- Ignored user hidden on map
- Logs in ACP per Api call with response in detail view

### Installation

1. Auto-installation
   1. Go to ACP => Add-Ons and upload the ZIP file

2. Manually installation
   1. Upload all files in `/upload`, `js` and `styles` folder in your forum root
   2. Got to ACP => Add-Ons an install the new listed add-on

### Requirements

- PHP 7.2.0+
- XenForo 2.2.0+

### Screenshots
#### Backend
![Options](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/Options.png)
![StyleProperties](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/StyleProperties.png)
![SearchForUsers](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/SearchForUsers.png)
![BatchUpdateUsersConfirm](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/BatchUpdateUsersConfirm.png)
![Permissions](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/Permissions.png)
![RebuildMapData](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/RebuildMapData.png)
![AccountEdit](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/AccountEdit_OptIn.png)

#### UserAccount/Profile
![AccountEdit](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/AccountEdit_OptOut.png)
![AdminUserEdit](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/AdminUserEdit.png)

#### Frontend
![Membermap](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/MembermapView.png)
![Membermap](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/MembermapUserView.png)
![MembermapBelow](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/MembermapBelow.png)
![MembermapSidebar](https://github.com/McAtze/-XT-Membermap/blob/main/screenshots/MembermapSidebar.png)
