# Basic JavaScript example Intercom installation for logged-in users

This is the absolute minimum you need to add the Intercom Messenger to your website for logged-in users.

**Note**: This example is somewhat contrived because it's a static HTML page, which means it is impossible to track dynamic user logins without using JavaScript. However, if you have a serverside rendered page, this will show you how you could render the HTML to identify the user to Intercom.

## Instructions

1. Find your `app_id`
    * After logging into Intercom at [https://app.intercom.com](https://app.intercom.com), your `app_id` is in the URL: `https://app.intercom.com/a/apps/{app_id here}`
1. Find and replace Your_App_ID in [`index.html`](https://github.com/intercom/example-basic-javascript-install/blob/master/index.html)
1. Fill in user data by replacing `name`, `email`, and `created_at` fields with the user's real info
1. Open index.html
1. See Messenger in lower right hand corner!
