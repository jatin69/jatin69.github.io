---
layout: project
title:  "Atlas Adventure"
bannerDescription: "Amazon Alexa Skill to play the geography variant 
of the classic word building game - word chain."
techUsed: Alexa Node.js SDK, AWS Lambda, CloudWatch, Google Places API
githubRepo: jatin69/atlas-adventure
comments: true
priority: 5
date: 2018-02-13
---

# Atlas-adventure

<img align="right" src="https://raw.githubusercontent.com/jatin69/Atlas-adventure/master/skill-icon/skill-icon.png">
Atlas Adventure is an alexa skill. 

With this, the user can play the geography variant of the classic word building game - word chain.
Game proceeds by Saying the name of cities in turns, starting with last letter of previously said city. 

It has got country mode, lifelines, and spelling options. 
You can find it live <a href="https://www.amazon.com/Jatin-Rohilla-Atlas-Adventure/dp/B079R8DTBV/">on the amazon store</a> .


## Setting up the skill

- `git clone https://github.com/jatin69/Atlas-adventure.git`
- `cd Atlas-adventure/lambda/`
- `npm install`
- `subl index.js`

- To publish
	- setup AWS CLI and configure it. 
	- check out the `publish.bat` and update your function name in the script.
	- run script from `Atlas-adventure/`
	- This should zip and upload the code and modules to aws.

### Setting up AWS CLI

- [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/installing.html). Verify using `aws --version`
- [Configure](https://developer.amazon.com/blogs/post/Tx1UE9W1NQ0GYII/publishing-your-skill-code-to-lambda-via-the-command-line-interface) and verify using `aws lambda list-functions`. This should list your available lambda functions.
- Install 7z and make sure it works on command line.
- write `publish.bat` automation script
- test configuration steps on a hello world skill. The skill should be published and be working fine in testing.
