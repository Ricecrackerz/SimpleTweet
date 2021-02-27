# Project 2 - *SimpleTweet*

**Name of your app** is an android app that allows a user to view his Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **5-6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x] User can **view tweets from their home timeline**
- [x] User is displayed the username, name, and body for each tweet
- [x] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh

The following **optional** features are implemented:

- [ ] User can view more tweets as they scroll with infinite pagination
- [ ] Improve the user interface and theme the app to feel "twitter branded"
- [ ] Links in tweets are clickable and will launch the web browser
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can see embedded image media within the tweet detail view
- [ ] User can watch embedded video within the tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Ricecrackerz/SimpleTweet/blob/master/SimpleTweetNEW.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

There were an abundant amount of issues regarding this project. First, it required you to download certain SDKs and without that knowledge one could take a lot of time figuring it out. Another issue was properly opening the SimpleTweet app, as well as refactoring classes. I had to reopen a new SimpleTweet file and close Android Studio. By doing this, Android Studio was able to recognize the class files. I also had a lot of issues with tweets being shown on my emulator. I would have to refresh a lot of times to have it show up and sometimes it would crash when refreshing. My AVDs were also missing, and I had to switch to API 27 to properly load the tweets. My emulator would bug out, presenting a fully black screen, bits of text everywhere, and applications spread out all over the emulator. Coding this project was fairly easy, but dealing with all the external issues and bugs took almost three to four hours in total. I wish I had more of that time to focus on the stretch stories as they were very interesting and compelling to me. Especially since I am an aspiring mobile app developer.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Vincent Hoang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
