# Socialbase

Thinking about adding Social Networking features to your app? Doing that nowadays can be cumbersome as you have to build a proper API backend, host it and consume it from your app, Does that sound a lot for an app developer ? yes it does.

You might have heard of Firebase, a BaaS that can help you add real time communication and data storage capabilities to your app, where your data model will be represented in JSON.

Socialbase is a simple JSON file that you can drop into your Firebase collection (inspired by [Tapglue](https://www.tapglue.com)) , this will create the minimum data structure to enable social networking in your app.

Excited? [Download](socialbase.json) the file and enjoy!

## Now what?
The following collections are available in the current Socialbase structure:
* **Users**: List of users
* **Search**: Basic users search index
* **Events**: List of events(bookmarks, saves ..etc)
* **Posts**: List of users' posts
* **Like**: List of users' likes
* **Comments**: List of users' comments
* **Connections**: List of users' connections

Use Firebase [Android](https://www.firebase.com/docs/android/quickstart.html) or [iOS](https://www.firebase.com/docs/ios/quickstart.html) SDKs to consume and manage the data.

## Docs
Work in progress.

## Contribute
Here is a list of ideas that can be useful for contributors
* Adding documention
* Add third party search providers (eg: Elasticsearch)
* Android and iOS app samples
* Tutorials

