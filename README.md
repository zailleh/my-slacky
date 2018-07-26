# Slacky
### Very basic slack chat app. Didn't realise the name was already used by an app when I thought of it!
![Slacky](https://i.imgur.com/NPd5dVj.png)
## Technology
Built using common libraries:
* jQuery
* Underscore

### Authentication
Presently, for testing purposes, the authentication has a hard-coded key. The key included in this repository is not valid and for example only. This app should implement oAuth2 authentication when the user loads it so that it is added to the group of their choice and the key stored locally only.

### Slack API Methods Used:
| Method | Permissions Required |
| ------ | -------------------- |
| [user.info](https://api.slack.com/methods/users.info) | [users:read](https://api.slack.com/scopes/users:read) |
| [groups.list](https://api.slack.com/methods/groups.list) | [groups:read](https://api.slack.com/scopes/groups:read) |
| [chat.postMessage](https://api.slack.com/methods/chat.postMessage) | [chat:write:user](https://api.slack.com/scopes/chat:write:user) |
| [groups.history](https://api.slack.com/methods/groups.history) | [groups:history](https://api.slack.com/scopes/chat:write:user) |


## To Do
* Add Authentication so any user can log in and view their groups
* Format markup text into html
* Nest Threads
* Get Attachments
* More!
* Rename and rebrand
