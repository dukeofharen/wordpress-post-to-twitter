(c) 2015 Duco Winterwerp - http://duco.cc

WordPress post to Twitter

I’ve just created a WordPress plugin which makes it ridiculously easy to post a tweet to Twitter through WordPress. In this post, I’ll explain how the plugin works.

- Download the plugin
As of now, the plugin is only available through GitHub: https://github.com/dukeofharen/wordpress-post-to-twitter

- Extract the contents to the plugin directory of WordPress
After you’ve done that, make sure you activate the plugin.

- Connect the plugin to your Twitter Account
OK, now it gets interesting. We need to ask Twitter for 4 keys.
1. Go to https://apps.twitter.com and log in with your account
2. Click “Create New App”
3. Fill in the necessary details
4. Go to “Keys and Access Tokens”

You need 4 keys, 2 keys are already available on this page: the Consumer Key and the Consumer Secret. At “Access Level” you will see “Read-only”, this needs to be “Read and write”. Click “Modify app permissions”, click “Read and write” and “Update Settings”. Your app now has “Read and write” permissions. Go back to “Keys and Access Tokens”. Now click “Create my access token”. Now you’ll also have the Access Token and the Access Token Secret. Now you have the 4 necessary keys to make posts to Twitter.

- Update the settings in WordPress
In your dashboard, go to “Settings” => “Post To Twitter”. You’ll see 4 empty fields: fill in the 4 codes you’ve generated. After you’ve filled in the codes, click “Save Changes” and after that “Test”. If everything went right, a tweet has been placed on your Twitter account.

- Tweet a post to Twitter
Now you’ve successfully connected Twitter to your blog, you’ll now see this box at the bottom of the update post page: 
Here you can select whether you want a tweet to be posted linking to this WordPress post, whether you want the featured image sent to Twitter and if you want a custom text to be tweeted (by default, the title of the post is tweeted). A link to the post will be sent with the tweet if you've enabled this option in the "Post To Twitter" settings page.