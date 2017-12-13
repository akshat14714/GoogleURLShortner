# GoogleURLShortner
A basic url shortner using AJAX and google APIs

### Google URL Shortener API
1. First, make sure you have a regular Google account. If you don't, you can create one [here](https://accounts.google.com/SignUp?hl=en).

2. Make sure that you are logged into the Google account that you want to associate with your project if you have more than one.

3. Navigate to the [Google Developers](https://developers.google.com/) page and click "Sign In" in the upper right hand corner.

4. Then, navigate to the [Developer Dashboard](https://console.developers.google.com/apis/dashboard) and click `Enable API`.

5. In the field that says `Search all 100+ APIs`, search for `URL Shortener` and select `URL Shortener API` (see below).
![IMAGE ALT TEXT HERE](https://s3.amazonaws.com/codecademy-content/courses/intermediate-javascript-requests/url-shortener-api.png)

6. You will then be redirected to a screen that says "A project is needed to enable APIs" Click `Create Project`. You may have to click `Create` again.

7. Name your project whatever you wish. Then click `Create`.

8. You'll be redirected to the search page again. Click `Enable` above the search bar. There will be another bar that says "To use this API, you may need credentials. Click `Create credentials` in the top right corner to get started."
![IMAGE ALT TEXT HERE](https://s3.amazonaws.com/codecademy-content/courses/intermediate-javascript-requests/url-shortener-api.png)

9. When you click `Create credentials`, you will be redirected to the `Credentials` page.

10. For "Which API are you using," it should already say "URL Shortener API" but select that if it does not.

11. Then, under "Where will you be calling the API from," select "Web browser (Javascript)."

12. Then, select "Public data" under "What data will you be accessing?" Your entries should include the following:
![IMAGE ALT TEXT HERE](https://s3.amazonaws.com/codecademy-content/courses/intermediate-javascript-requests/what-credentials.png)

13. Click "What credentials do I need?" You should be redirected to a page that says "Add credentials to your project." It should give you an API Key. That api key will always be available in the credentials console.


Congratulations! You have enabled the Google URL Shortener API and obtained an API Key!

### What To Do Next
* In the `public/main.js` file, save the API key you just created to the const called `apiKey`.
* Then just open the `index.html` file in your browser and you are set to go.
