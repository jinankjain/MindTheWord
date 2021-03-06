Troubleshooting
===============

Quality of Translations
-----------------------

*Mind the Word* depends on the *Google Translate* and *Yandex Translate* services. Therefore, the quality of the translations provided by *Mind the Word* depends on the quality of these services. 


Google Translate's Unreliability
--------------------------------

Recently, the option to use Google within Mind The Word stopped working for many users. If you see no translations when you select *Google* as your translation provider in the options page, you are probably being affected by this problem. That is why we started offering an alternative: *Yandex*. Its translation service has been much more reliable recently. Please give it a try! Note that Yandex requires an *API key*, but you can [obtain one for free](https://tech.yandex.com/keys/get/?service=trnsl). 


Blank Options Page
------------------

A few users have been experiencing a problem in which the options page is blank and no translation configuration can be created, as shown in the screenshot below:

![BlankOptions](BlankOptions.png)


This problem seems to be caused by failed storage or retrieval of the options in Google's synchronized storage servers when *Mind The Word* is installed and loaded for the first time. This may be due to a temporary communication problem with Google.

In order to solve this problem, please try the following:

1. uninstall the extension;

2. close chrome;

3. reopen chrome;

4. reinstall [Mind The Word](http://chrome.google.com/webstore/detail/mindtheword/fabjlaokbhaoehejcoblhahcekmogbom);

5. visit some webpage;

6. open the extension's options page;

This has been reported to work for other users. If it doesn't work for you, please [contact us](mailto:MindTheWord@gmail.com).



Help us to help you
-------------------

If you contact us, it is very helpful if you take screenshots (i.e. pictures of your screen) of error messages shown in the javascript console. The following instructions explain how you can do that:


1. If you don't know how to take screnshots in your operating system, read how to do it in [Windows](http://www.wikihow.com/Take-a-Screenshot-in-Microsoft-Windows) or in [Mac](http://www.wikihow.com/Take-a-Screenshot-in-Mac-OS-X)).

2. open the options page of Mind The Word.

3. go to Chrome's menu (in the upper right corner) and click on the menu item "More Tools> Javascript Console".

4. reload the options page.

5. Take screenshots of the options page (both of your basic options and your advanced options) together with the Javascript console.

6. Send the screenshots and a description of your problem to [us](mailto:MindTheWord@gmail.com).


The images below show how to open the Javascript Console and how a screenshot of the options page with the console message log looks like.

![JSConsole](JSConsole.png)

![OptionsConsole](OptionsConsole.png)



The screenshots of your options will show us whether you are configuring the extension correctly, and the screenshots of the javascript console will show us whether any error is occurring during the execution of the code in the options page.


You can do the same thing for the website that you are trying to translate:

1. open a webpage that you would like to be translated by Mind The Word.

2. open the javascript console, as explained above.

3. reload the webpage.

4. take screenshots of the webpage together with the javascript console.

5. send the screenshots and a description of your problem to [us](mailto:MindTheWord@gmail.com).

With the information provided by the screenshots, we will be more able to help you.
If any of the steps described above is unclear, please tell us.