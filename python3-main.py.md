# Installing playwright

Time for us to run the main Python file. This part might shoot you with errors, but there is nothing we cannot resolve...

Type: `python3 main.py` in the same terminal (if you closed it, head back to the previous page of the documentation and look at how we entered the terminal last time). In some cases `python3 main.py` does not work, run `python main.py` instead. Once you press enter, you should see some colorful text and then be prompted by an error:

![](<.gitbook/assets/image (2).png>)

![](<.gitbook/assets/image (6).png>)

Don't worry, all this error is asking us to do is install _Playwright_, this is responsible for scraping the screenshots. _Playwright_ can be installed in the following way: `npx playwright install`. This could take some time since we are installing a significantly larger package.\
Once you install _Playwright_, you might have to type `playwright install` just in case it does not download _Chromium_.
