# Login-and-Registration-using-Firebase

This demo Android app demonstrates authenticating with Firebase Login for Facebook, Google, Twitter,
email & password, and anonymous.

### Setup
0. Sign up and create a new [Firebase](https://www.firebase.com).
0. Create apps for each provider on their developer consoles. See the Firebase
   [authentication provider docs](https://www.firebase.com/docs/android/guide/user-auth.html#section-providers)
   for more details.
    - [Facebook](https://developers.facebook.com/docs/android/getting-started)
    - [Google](https://developers.google.com/+/mobile/android/getting-started)
    - [Twitter](https://apps.twitter.com/app/new)
0. Enable Facebook, Google, Twitter, Email, and Anonymous providers on the Firebase Dashboard for
   your app. See the
   [enabling providers section](https://www.firebase.com/docs/android/guide/user-auth.html#section-enable-providers)
   of the Firebase user authentication docs for more details.
0. Populate all of the values in [`res/values/keys.xml`](/app/src/main/res/values/keys.xml).
