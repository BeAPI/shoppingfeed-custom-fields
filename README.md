# ShoppingFeed Custom Fields

## Description

Integrate data from ACF fields for the ShoppingFeed plugin in your xml products feed

## Installation

Requires the shoppingfeed plugin

- Activate the plugin in Plugins > Installed Plugins

## Changelog

### 1.0.5 (8-07-2025)

* fix: set visibility to public for the __wakeup() method in the ShoppingFeedCustomFields class

### 1.0.4 (28-08-2023)

* fix: missing value for select with single value

### 1.0.3 (24-08-2023)

* fix: The selected/unselected ACF fields are saved correctly

### 1.0.2 (12-05-2022)

* added: Readme file
* added: Notice in the plugin admin page

## Configuration

To start using the plugin correctly, you need to configure some ACF fields first

- In Plugins > Installed Plugins > ShoppingFeed Custom Fields > settings, choose the ACF fields to export

### Supported fields

Please do note that only the following ACF fields will be exported. Any other field will not!

'text',
'textarea',
'number',
'email',
'password',
'url',
'select',
'checkbox',
'radio',
'true_false',
'link',