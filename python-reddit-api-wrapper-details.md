# Python Reddit API Wrapper details

Head over to that folder where you have all the source files saved, rename the `.env.template` file to `.env`, you might get a prompt from windows, ignore it. Once you are done, right click the file and open it with **notepad**_, although any IDE can be used._

Once you open the notepad file, you should see:\
`REDDIT_CLIENT_ID = ""`\
`REDDIT_CLIENT_SECRET = ""`\
`REDDIT_USERNAME = ""`\
`REDDIT_PASSWORD = ""`\
`REDDIT_2FA="no"` The valid options are "yes" "no" all lowercase. \
`RANDOM_THREAD = "yes"`  "yes" or "no"\
`THEME = "light"` "dark" or "light"\
`SUBREDDIT = "AskReddit"` \
`OPACITY = "1"` 0 -> 1

So the next we are going to be doing is the most essential part of this part. Avoid any errors here!

Head over to the apps page under the preferences page, [_https://www.reddit.com/prefs/apps_](https://www.reddit.com/prefs/apps). Once you are here, you should scroll down and see a button saying `create another app` (could be different if your first app), click it. Once you click it, you should see:

![](<.gitbook/assets/image (6) (1).png>)

Name: You can put in any name, for example: `automated-bot`\
\`\`Radio Button: Where it shows you the three radio buttons, pick the third one, that is the **script** one.\
Description: Put in anything, does not matter.\
About URL: Link any webpage like `https://google.com`.\
Redirect URI: Link any webpage like `https://google.com`.

Great, you are done here, now just create the app!

Copy the text highlighted blue, that is your `REDDIT_CLIENT_ID`, the text highlighted orange is your `REDDIT_CLIENT_SECRET` (DO NOT SHARE THIS WITH ANYONE, I WILL BE DELETING THIS APPLICATION). The text where it says developers (the one I blurred out, where there is an arrow pointing) is your `REDDIT_USERNAME` and `REDDIT_PASSWORD` is your **Reddit** account's password. No, your information is **not logged.**

Head over to your `.env` file and enter the client ID, secret, username & password **within the quotations.** Hit `Ctrl+S` to save the file. For the love of god, ensure there are no mistakes here.
