# SimpleToDo
# Pre-work - SimpleToDo

Simpletodo is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: Juliann Farrell

Time spent: 4 hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/yudwJYv.gif' width="600" /> alt='Video Walkthrough' />

GIF created with [LiceCap](https://i.imgur.com/7nVWd2l.gif).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** This is my first time ever creating an app. I believe that Android compared to when I had an andriod phone years ago has definetely changed their layouts and overall design. The user interface in Andriods has become more sleeker and cleaner than in other years and has become more cohesive in their design for example by changing their color scheme and fonts. Working for the first time in the Andriod development I have seen a change in the overall look compared to when I had an Andriod. Testing out the code that I had I have saw that it does look a lot different and more current. 

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** In the pre-work the ArrayAdapter is used to to create the vertical list. In order to create this list we used an Adapter. The best adapter to use is the Array Adapter because the adapter coverts objects into view items. This adapter is important in order to create a correct and simplified view of the vertical list. We use the convertview in the getview to help us get the java object into a view visible in the app. Convertview also helps us see if there is already an exisitng view being reused or not. 

## Notes

Describe any challenges encountered while building the app.

I had a bit of trouble uploading the code because my Android Studio wouldn't upload to Github. 

## License

    Copyright 2020 Juliann Farrell

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
