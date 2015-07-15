<img src="http://i.giphy.com/kCVIL0CLNWv2E.gif" height="100"/>

### Philosophy

The goal of this challenge is to get insight on how you approach an everyday task, not a hypothetical algorithm unicorn puzzle of doom. Complete the challenge by writing code that you would write again any day and pick up with ease 5 years from now. Basically, write code you're proud of.

### Values

- We exclusively use Objective-C and Xcode, please don't go beyond that.
- We highly value code cleanliness, reusability, structure and hierarchy.
- We make extensive use of code formatting, code reviews and tests.
- We are huge fans of popular 3rd party libraries, so use them when it makes sense to not re-invent the wheel (e.g. AFNetworking is fine) but make sure you show us what you can do on your own.
- We love modern app design!
- We are big fans of small, incremental commits, not 5,000 LoC `Initial Commit.` and `Added stuff.` monsters.
- We know StackOverflow et al. exist; getting inspiration from other sources is totally fine as long as you attribute them in your code.
- We delight our users with a familiar but fresh UX.

### Time Limit

The task is doable in a half day over the weekend. It is OK to leave reasonable TODOs in the code when you run out of time or took a shortcut, just explain yourself.

Overall, please complete this challenge within ≈2 weeks of receiving it.

### The Challenge

1. Create a simple app with a text entry field, and as you type it will display autocomplete results from the Google Places JSON API endpoint (i.e. not using their built-in autocomplete SDK). 
  - **Important Note:** For this challenge, you cannot use Google's built in GMSPlacesClient:autocompleteQuery code to return parsed place results for you. You must instead use the JSON API provided and parse the return results yourself.
2. Once the user selects one of the results, transition to a new view showing basic information pulled from the Places JSON API. The way you display the results and detailed view is up to you.

**Note**: You should build this as if it were a real project that you had to maintain for the foreseeable future. You should ensure the user experience is balanced with the robustness and cleanliness of your code. We left this open ended, but it doesn't mean you should rush through it and just send something functional without any polish. This should be a direct representation of who you are.

When you're all done: 
- Commit it to a repo in your personal Github account that we can access (or zip the project and host it somewhere for us to download, _including_ the git history)
- If there are any special instructions (besides running `pod install` for Cocoapods) to get your project running, please let us know
- Shoot us a quick email letting us know you're done and we'll clone it and run it from our machines

### Google Places API

You can obtain an API key by signing up for a free Google Places API account.

Places API Documentation:  [https://developers.google.com/places/documentation/](https://developers.google.com/places/documentation/)

### Review

When reviewing your submission, we'll be looking at the following (not necessarily in this order):

- Code Quality
  - Is the code reasonably easy to understand and well-organized (i.e. broken down into models, networking, views, controllers)? Could we plug our app into your code reasonably fast?
  - Is your code reasonably robust (i.e. what happens when the server returns errors or there is no internet connection and how do you display those to the user)?

- Functionality
  - Core functionality of searching and showing results
  - Accuracy of the returned results (easy to find something locally or far away)

- Experience
  - How does the user experience feel?
