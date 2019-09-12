# WP Front End Profile

[![Build Status](https://travis-ci.com/musamamasood/wp-frontend-profile.svg?branch=master)](https://travis-ci.com/musamamasood/wp-frontend-profile)

WP Front End Profile allows users to edit their profile without going into the dashboard to do so.

## Description

WP Front End Profile give you the ability to add a extensible user profile section to the front end of your WordPress website. By default the plugin adds two tabs to the front end profile. One of these titled profile allows a user to edit their user data including email, first and last names, URL and bio (description). The password tab allows a user to change their password for the site.

### Plugin Extensibility

As the front end profile is rendered with tabs you can easily add your own tabs with your own fields to store user meta data. Tabs and fields are added through filters and all the saving of the data is taken care of for you.

You can add the following field types:

*	WYSIWYG
*	Select
*   Text Area
*	Checkbox
*	Password
*	Email
*	Text

## Installation

1. Upload to your plugins folder, usually `wp-content/plugins/`
2. Activate the plugin on the plugin screen.
3. Once activated the plugin will appear under your `Dashboard` menu.

## Contributing

Contributions are more than welcome, both through issues, and pull requests.

## Changelog

### 0.2.2
* Security: Fix privilege escalation and XSS vulnerabilities.

### 0.2.1
* Added ability to display form via shortcode.

### 0.2
* Include a nonce in the front end editing form for security.

### 0.1
* Initial launch.