# Intro

This is an extension of Moodle [Zoom plugin](https://moodle.org/plugins/mod_zoom). We update it for attendance report and marking for the students. 

# About Original Plugin
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

# Changes in this extension
- Zoom Participants Reports
- Student wise unified attendance report
- Attendance marking for all session

## Report Path

### For List of all session of a online classes

```Dashboard->My courses->Your Course Name->General->Your Zoom Session-> Sessions```

### For Attendance Report

```Dashboard->My courses->Your Course Name->General->Your Zoom Session-> Attendance Report```

### For Participants Report of a session

```Dashboard->My courses->Your Course Name->General->Your Zoom Session-> Participants```

## Example report:

<p align="center">
    <img src="https://i.imgur.com/4C5GRCz.png">
    <img src="https://i.imgur.com/5dX1Qj9.png">
</p>
