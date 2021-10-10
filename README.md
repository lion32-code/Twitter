# Twitter Client Part 2*


**Twitter Client** is an android app receives tweets from the account using api and is then implemented into the app. The user can compose and post the tweet on twitter and would be visible on the app.

Submitted by: **Ruhi Rownak**

Time spent: **26** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can compose a new tweet.
	* [x] User can click a "Compose" icon in the AppBar on the top right
* [x] User can then enter a new tweet and post this to twitter
* [x] User is taken back to home timeline with new tweet visible in timeline
* [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
* [x] While composing a tweet, user can see a character counter with characters remaining for tweet out of 280

The following **optional** features are implemented:

* []Improve the user interface and theme the app to feel "twitter branded"
* [] Links in tweets are clickable and will launch the web browser
* [] User can select "reply" from detail view to respond to a tweet
* [] Move the "Compose" action to a FloatingActionButton instead of on the AppBar.
* [] Compose activity is replaced with a modal overlay
* [] Use Parcelable instead of Serializable using the popular Parceler library.
* [] User can open the twitter app offline and see last loaded tweets
	* [] Tweets are persisted into sqlite and can be displayed from the local DB
* [] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be persisted to disk and can later be resumed from the compose view.
* [] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='Twitter 2 Walkthrough.gif' title='Flixter Walkthrough' width='' alt='Twitter Walkthrough' />


## Notes

I had to try to use android studio without emulator so I did it by connecting usb cable into my android device to see whether the app functions properly or not. I had to ensure that the texts are visible whenever user is scrolling down.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
