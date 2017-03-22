# Startkit to do your bots

## You're not a developer? Try Dexter! 
It's so simple as writing the dialog, in River Script (the best way to define a conversation).
But it is able to use variables, have conditionals, send images, send buttons, or even get JSON from webs or posting items. And if you want more complexity, you can embed javascript inside!

http://docs.rundexter.com/writing/basics/first-things-first/

## You're not a developer but you want NLP? Try API.ai or Wit.ai

API.ai will allow you to have a great NLP, with Entity Recognition, and build apps for a lot of channel, including Alexa and Google Home. The great limitation is that the conversations cannot be as complex as in other platforms.
https://api.ai/

Wit.ai will allow you to do great bos for Facebook, with more complexity in the dialogs than API.ai, and is very easy to use.

Both can be used also as external NLP for your bots.

## You're a developer? You can try the flowbot!

It's based on Microsoft Bot Framework, so you will be able to use all the functionalities provided by Microsoft.

Visit https://github.com/jseijas/generator-flowbot for more information

### You want to test your local developed bot without deploying it

Just try https://ngrok.com/
It will generate an https url that is a tunnel to your local machine!

### You want to deploy your bot for free

You can try https://www.heroku.com/
You'll be able to deploy from a github, from a dropbox or using it's own github.
To use it's own github, install the heroku CLI: https://devcenter.heroku.com/articles/heroku-cli
Once you install the cli you can do:
- heroku login (To login into your heroku)
- git add .
- git commit -m "comment for the commit"
- heroku create name-of-your-project
- git push heroku master

This will automatically deploy your node app.

## Create a Facebook App

1. Navigate to: https://www.facebook.com/bookmarks/pages
2. Click in Create a Page
![Click in Create a page](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step2.png)
3. Select a category
![Select a category](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step3.png)
4. Insert a name for the Page and click Get Started
![Insert a name for the Page](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step4.png)
5. Click the About of the Page
![Click About](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step5.png)
6. Copy the Page Id, you'll need it later.
![Get the Page Id](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step6.png)
7. Navigate to: https://developers.facebook.com/quickstarts/?platform=web
8. Enter a name for the App and click Create New Facebook App Id
![Enter App Name](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step7.png)
9. Select "Apps for Messenger" as the Category and click Create App Id
![Create App Id](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step8.png)
10. Copy the App Id and the App Secret, you'll need them later
![Copy App Id and Secret](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step9.png)
11. Click on the Messenger settings, and select your Page. This will generate a Token. Copy the token, you'll need it later.
![Copy App Token](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step10.png)
12. Click in Setup Webhooks
![Click Setup Webhooks](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step11.png)
13. Put your callback URL and your verify token. Activate the subscription fields that you need. Click Verify and Save.
![Click Setup Webhooks](https://raw.githubusercontent.com/jseijas/botstart/master/assets/facebook/step12.png)







