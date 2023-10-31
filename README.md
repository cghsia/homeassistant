# homeassistant
Various Home Assistant automations I'm using or have used for sharing/collaborative documentation.

# File listing

## axis_vmd4_automation-group-of-actions.yaml
Automation turning on lights based on motion detection using Axis Video Motion Detection 4 (VMD4), turning on lights only if the sun is below the horizon (or after sunset but before sunrise)). This automation includes time-based conditional actions (group of actions) along with a random delay to keep lights on before turning off. The automation will auto-restart if VMD4 continually detects motion.

This automation is based off of the following HA documentation: https://www.home-assistant.io/docs/scripts/#choose-a-group-of-actions

## node-red_axis_vmd4.json
More or less the same as axis_vmd4_automation-group-of-actions.yaml but done in Node-Red

## node-red_axis_vmd4-email-notification.json
More or less the same as node-red_axis_vmd4.json but with email notification along with picture attachment when Axis VMD4 detected motion. Clean JSON without secrets/authentication information.
