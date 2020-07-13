# Intro
This plugin is based on Moodle zoom plugin (https://moodle.org/plugins/mod_zoom). so Many thanks to Rex Lorenzo for this awesome plugin.

Zoom is the web and app based video conferencing service (http://zoom.us). This plugin offers tight integration with Moodle, supporting meeting creation, synchronization, grading, and backup/restore.

We extend the feature of this plugin like custom reporting, fetch report and synchronization based on participant provided name. 

# Prerequisites

This plugin is designed for Educational or Business Zoom accounts.

To connec to the Zoom APIs this plugin requires an account level JWT app to be
created. To create an account-level JWT app the Developer Role Permission is
required.

See https://marketplace.zoom.us/docs/guides/build/jwt-app. You will need to create a JWT app and that will generate the API key and secret.

## Installation

1. Install plugin to mod/zoom. More details at https://docs.moodle.org/39/en/Installing_plugins#Installing_a_plugin
2. Once you install the plugin you need to set the following set the following
   settings to enable the plugin:

- Zoom API key (mod_zoom | apikey)
- Zoom API secret (mod_zoom | apisecret)
- Zoom home page URL (mod_zoom | zoomurl), Link to your organization's custom Zoom landing page.

Please note that the API key and secret is not the same as the LTI key/secret.

More details at https://moodle.org/plugins/mod_zoom

Zoom Participants Reports (customized).
<p align="center">
<img src="https://i.imgur.com/Io7VyM4.png">

</p>

