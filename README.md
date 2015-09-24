# Slack Webhook Example
This example is an exercise in sending a message to slack using Webhook and JQuery.

## Webhook
You will need to stup the incomming webhook integration on your slack org. (https://api.slack.com/incoming-webhooks)
Then use the url that is generated for you

  https://hooks.slack.com/services/T00000000/B00000000/XXXXXXXXXXXXXXXXXXXXXXXX

## Notes
The "channel" field looks like it is more dependent on it's content, like #random or @john, than the field name "channel". This example you are able to post to a channel or at someone. If you post @ someone, it shows from the slackbot DM.

## Security
If you make this page public you are opening ANYONE to post to your slack org! Suggest putting this behind authentication or within a locked down internal network. It does not know who is using it, you can change the name that shows in "username", but it still posts as the webhook bot.
