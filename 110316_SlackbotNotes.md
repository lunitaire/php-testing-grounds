# Slack Bots Talk - PHPAtlanta

Integration options
* Apps vs custom integrations
  * Internal tool, not meant for distribution
* Incoming webhooks
  * Notifications, HTTP request with JSOn
* Slask commands
  * On-demand actions
  * Submits an HTTP request to endpoint
  * Three flavors: built-in, custom integrations, app commands
    * Custom: internal, less restrictions
    * App: Only POST requests with SSL endpoints with valid cert, able to use across different teams
* Bot Users
  * Can be standalone or part of an applications
  * Have a name and icon
  * They use a token and interact via APIs
  * Needs to be user friendly
* APIs: web, rtm, events
  * Real Time Messaging API
    * Based on web sockets
    * Listen to everything, react to what you want
  * SCIM API
    * Only available to teams in the Plus Plan

Tools
* Botkit
  * https://howdy.ai/botkit/
* Tons of other clients and libraries
  * https://api.slack.com/community
* Tunnel
  * Ngrok 
    * Command Line Tool that creates a tunnel on a port
    * $ ngrok http 8000
    * New URL every time you restart connection
    * Paid version lets you keep URL
* Slack Checklist
  * https://api.slack.com/docs/slack-apps-checklist

//Lunchbox
* a bot that helps you schedule lunch outings
* originally built in NodeJS, then re-written in PHP/Laravel
* installed by over 1,300 Slack teams

Prep
* Add to appstore
* Make a landing page
* Provide documentation
* Provide a clear support contact
* Use the Slack button
* Don't spam or abuse your users or the platform

https://trello.com/b/HPpclqd8/slack-app-ideaboard
https://speakerdeck.com/nicdev/developing-bots-for-slack

