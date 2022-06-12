# Python Reddit API Wrapper details

Head over to that folder where you have all the source files saved, rename the `.env.template` file to `.env`, you might get a prompt from windows, ignore it. Once you are done, right click the file and open it with _Notepad_, _although any IDE can be used_.

Once you open the notepad file, you should see:\
`REDDIT_CLIENT_ID = ""`\
`REDDIT_CLIENT_SECRET = ""`\
`REDDIT_USERNAME = ""`\
`REDDIT_PASSWORD = ""`\
`REDDIT_2FA = "no"` the valid options are "yes" or "no" all lowercase\
`RANDOM_THREAD = "yes"` "yes" or "no"\
`THEME = "light"` "dark" or "light"\
`SUBREDDIT = "AskReddit"`\
`OPACITY = "1"` 0 to 1

The next step will be the most essential in this entire section. Avoid any errors here!

Head over to the _apps_ page under the _prefs_ page: [https://www.reddit.com/prefs/apps](https://www.reddit.com/prefs/apps). Once you are here, you should scroll down and see a button saying _create another app..._ (it could be different if it's your first app), click it. Once you click it, you should see:

![](<.gitbook/assets/image (6) (1).png>)

**Name**: you can put in any name, for example: `automated-bot`\
**Radio Buttons**: where it shows you the three radio buttons, pick the third one, that is the _script_ one.\
**Description**: put in anything, it does not matter.\
**About URL**: link any webpage like `https://google.com`.\
**Redirect URI**: link any webpage like `https://google.com`.

Great, you created the app! now you need to fill in the valules
![Image](https://user-images.githubusercontent.com/66544866/173240642-af00257e-4414-4a57-a3be-24443ee7c29f.png)


Copy the text under "personal use script", that is your `REDDIT_CLIENT_ID`, the text right next to SECRET is your `REDDIT_CLIENT_SECRET` (**DO NOT SHARE THIS WITH ANYONE**).

The text where it says _developers_ is your `REDDIT_USERNAME` and `REDDIT_PASSWORD` is your Reddit account's password. **Your information is not logged**.

Head over to your `.env` file and enter the client ID, secret, username and password within the quotations. Hit `Ctrl+S` to save the file. For the love of God, ensure there are no mistakes here.
