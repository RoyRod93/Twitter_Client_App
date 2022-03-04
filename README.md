# *Twitter Client App*

**Twitter Client App** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

## User Stories

The following **required** functionality is completed:

- [x] User can **compose and post a new tweet**
- [x] User can click a “Compose” icon in the Action Bar on the top right
- [x] User can then enter a new tweet and post this to twitter
- [x] User is taken back to home timeline with **new tweet visible** in timeline
- [x] User can **see a counter with total number of characters left for tweet** on compose tweet page
- [x] User can click links in tweets launch the web browser 
- [x] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [x] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [x] User is displayed the relative timestamp for each tweet Example: "8m", "7h".
- [x] User can refresh tweets timeline by pulling down to refresh


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/3oPGPTR.gif' title='Video Walkthrough' width='250' height='450' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).


## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
