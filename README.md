# PALB
Python AWS Lambda Bot 

For syncing a source feed with target messengers. 

## Stack
* Python 3.7+
* AWS Lambdas

## MVP
Capture content from Twitter via Twitter API and send it to Telegram. Have the source API and target messenger be configurable for future reuse.
###  Further Plans
* Make the content type (tag/account) and keyword configurable.
* Make the Telegram target (private chat/group/channel) type and ID (which specific person/group/channel) configurable.
* Create a Discord bot to handle Discord as receiving end messenger
