# OctoWebhook #
An OctoPrint plugin for monitoring your printer and prints via Webhook

# Based on #
[OctoSlack](https://github.com/fraschetti/Octoslack) by [Chris Fraschetti](https://github.com/fraschetti)

# Features #
 - Support for both Slack and Mattermost
 - Monitor both print status as well as printer connectivity status
 - Slack+Mattermost WebHooks and Slack API Token
 - Respond to Slack commands to check print status or cancel/pause/resume a print
     - Requires use of the Slack API Token
 - Customizable messages
 - Support for posting to one more channels as well as event level channel overrides
 - Support for inclusion of RasPi temperature, bed temperature, nozzle temperates, and nozzle height
 - Custom bot name/icon/emoji
 - Optional inclusion of printer snapshot images with each message
     - Support for snapshot hosting on either Amazon S3 or Imgur (with album support)
 - Support for additional snapshot images from IP cameras

 # Supported Events #
 - Print started
 - Print failed
 - Print cancelled
 - Print paused
 - Print resumed
 - Print finished
 - Print progress (% complete)
 - Print progress (time interval)
 - Print progress (Z height change)
 - G-code sent to printer
 - Timelapse render started
 - Timelapse render finished
 - Timelapse render failed
 - OctoPrint error
 - OctoPrint started
 - OctoPrint stopped
 - Printer connecting
 - Printer connected
 - Printer disconnecting
 - Printer disconnected

# Manual installation steps #

    pip install "https://github.com/aleohl/OctoWebhook/archive/master.zip"

# Examples #

> ### Print Started ###
> ![Print started example](/screenshots/Octoslack-PrintStarted.png?raw=true)
> ###### Left = Slack  /  Right = Mattermost ######

> ### Print Progress ###
> ![Print progress example](/screenshots/Octoslack-PrintProgress.png?raw=true)
> ###### Left = Slack  /  Right = Mattermost ######

> ### Print Finished ###
> ![Print finished example](/screenshots/Octoslack-PrintFinished.png?raw=true)
> ###### Left = Slack  /  Right = Mattermost ######
