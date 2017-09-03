# TravisCI-Webhooks

This simple PHP code will allow you to send Travis-CI build notifications to your discord channel. 

## Screenshot
![](/../images/discord_screenshot.png)

## Setup
1. Configure your webserver of choice and make sure it has support for PHP
2. Configure the script, making sure to add your unique Discord webhook URL. 
3. Add the following to your `.travis.yml` file. More configuration options can be found [here](https://docs.travis-ci.com/user/notifications/#Configuring-webhook-notifications)
```yml
notifications:
  webhooks: http://your-domain.com/travis-ci.php
```
