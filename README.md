## Google Places Search

#### Philosophy

We have been trying to get all of our iOS applicants to complete a practical test that we believe is relevant to our core product.  It also allows us to see how you think and how you approach a real world problem from scratch. 

We're not big into puzzles, so nothing about this is a trick. Just approach it as you would any other task for a project.

#### Task Description

1. Create a simple app with a text entry field, and as you type it will display autocomplete results from the Google Places JSON API endpoint (i.e. not using their built-in autocomplete SDK). 
  - **Important Note:** For this challenge, you cannot use Google's built in GMSPlacesClient:autocompleteQuery code to return parsed place results for you. You must instead use the JSON API provided and parse the return results yourself.
2. Once the user selects one of the results, transition to a new view showing basic information pulled from the Places JSON API. The way you display the results and detailed view is up to you.

**Note**: You should build this as if it were a real project that you had to maintain for the foreseeable future. You should ensure the user experience is balanced with the robustness and cleanliness of your code. We left this open ended, but it doesn't mean you should rush through it and just send something functional without any polish. This is a direct representation of who you are.

When you're all done: 
- Commit it to a repo in your personal Github account that we can access (or zip the project and host it somewhere for us to download)
- If there are any special instructions (besides running `pod install` for Cocoapods) to get your project running, please let us know
- Shoot us a quick email letting us know you're done and we'll clone it and run it from our machines

#### Language

- We use Objective-C mostly still, but feel free to use Swift if you'd prefer.

#### Time Limit

Estimated time to complete the basic functionality (w/o bonus points) is ~4-5 hours, depending on if you've used Google Places API before. Submissions should be received within 2 weeks from the date you received the project.

#### Google Places API

You can obtain an API key by signing up for a free Google Places API account.

Places API Documentation:  [https://developers.google.com/places/documentation/](https://developers.google.com/places/documentation/)

#### Review

When reviewing your submission, we'll be looking at the following (not necessarily in this order):

- Code Quality
  - Is the code reasonably easy to understand and well-organized (i.e. broken down into models, networking, views, controllers)? Could we plug our app into your code reasonably fast?
  - Is your code reasonably robust (i.e. what happens when the server returns errors or there is no internet connection and how do you display those to the user)?

- Functionality
  - Core functionality of searching and showing results
  - Accuracy of the returned results (easy to find something locally or far away)

- Experience
  - How does the user experience feel?
