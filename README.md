# Bafnotes

A notes app written in Flutter, that should support text and audio notes and run on Android and iOS.

My motivation to write this app is twofold:
1. The primary reason is improving my coding skills in Flutter. I will (try to) make informed choices about things like which database to use, statemanagement approach and much more. For that purpose, I will regularly update the sections in this README with all new information I come across or learn, with the intent to turn this document into a tutorial / blogpost series kind of thing. 
2. I use a notes app daily, but am not really satisfied with the features most of them offer or the way they look / feel. I didn't really research this much though, as I made the decision to build an app myself fairly quickly.

The final goal is to create a notes app that is quick and easy to use with a cool design, to be released as a free app to the Google Play Store. 

## Features
* Add, save, review, edit, delete notes (TODO)
* Add multiple different things to notes, that correspond to a different layout for the shown note in the UI (TODO):
  * Text
  * Reminder date (have note pop-up when it is relevant to you)
  * Lists (todo, shopping, books, songs, ...)
  * Audio
  * Pictures
  * ...
* Search function (TODO)
* Favorites (TODO)
* Sort notes by: (TODO)
  * Added date
  * Reminder-date
  * Location?
 * Share notes with some else (Whatsapp, facebook,...)(TODO)
 * ...

WOULD BE GREAT:
If I could add a speech-to-text function, that would be GREAT. Should look into this.
 
## Testing
//TODO
## Database
//TODO
## State management
I will start out with the most standard way, just keeping local state in stateful widgets and [lift up the state][1] to higher-level widgets as I go along. I expect that passing down callbacks will become too hard to manage as the app grows, so at some point I will probably change to using [Provider][2] to make state available throughout the widget tree.

I might stop there if this turns out to be sufficient for this app, or I might move to a more advanced solution, like [MobX][3] or [Redux][4]. In that case I will probably use MobX because I'm most familiar with this library, but Redux might be interesting to explore too.  

[1]: https://flutter.dev/docs/development/data-and-backend/state-mgmt/simple#lifting-state-up
[2]: https://pub.dev/packages/provider
[3]: https://pub.dev/packages/mobx
[4]: https://pub.dev/packages/flutter_redux
//TODO
## UI & UX
//TODO
## Firebase (Analytics and Crash-reporting)
//TODO
## Deployment to Play store
//TODO



