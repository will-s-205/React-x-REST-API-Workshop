# Zoom Chat Snippets

---

## Table of Content <!-- omit in toc -->
* [Check-in Time Slots](#check-in-time-slots)
* [Quick Links](#quick-links)
* [Waiting Room](#waiting-room)
* [NodeJS](#nodejs)
* [Start](#start)
* [Live on YouTube](#live-on-youtube)
* [Install Commands {Get Started}](#install-commands-get-started)
* [Workshop Steps](#workshop-steps)
* [YouTube](#youtube)
* [Create a .env File](#create-a-env-file)
* [Debugging - Let's Fix Those Problems 💪](#debugging---lets-fix-those-problems-)
* [Additional Questions 🤔](#additional-questions-)
* [Create a Kintone Web Database App](#create-a-kintone-web-database-app)
  * [Fields \& Field Codes](#fields--field-codes)
  * [Kintone API Token](#kintone-api-token)
* [Kintone Customization Tutorials](#kintone-customization-tutorials)
* [Quick Check-in](#quick-check-in)
* [Looking for the Kintone Subdomain Email? ✉️](#looking-for-the-kintone-subdomain-email-️)
* [Errors related to .env](#errors-related-to-env)
* [Join our Meetup Group](#join-our-meetup-group)
* [Got Kintone Questions?](#got-kintone-questions)
* [Survey \& Gift Card Raffle](#survey--gift-card-raffle)
* [Write up your experience!](#write-up-your-experience)
* [Log into Kintone Subdomain?](#log-into-kintone-subdomain)
* [step-by-step guide](#step-by-step-guide)
* [Becoming a Kintone Partner?](#becoming-a-kintone-partner)
* [What are Kintone Plug-ins](#what-are-kintone-plug-ins)
* [🚀 Have your Kintone Subdomain ready!](#-have-your-kintone-subdomain-ready)
* [Got Questions? 🤔](#got-questions-)
* [Why use Kintone?](#why-use-kintone)
* [Start the servers](#start-the-servers)
* [Where to get the Subdomain, View ID, and App ID?](#where-to-get-the-subdomain-view-id-and-app-id)
* [Live on YouTube](#live-on-youtube-1)
* [Contest](#contest)
* [Completed Code](#completed-code)

---

## Check-in Time Slots

* 10:00 - Hello
* 10:10 - Get Started
* 10:25 - npm install (root & backend)
* 10:35 - Walk through repo (.env.example, App.js, server.js, etc.)
* 10:45 - Create a Kintone App
* 11:00 - 1 hour left
* 11:15 - 45 min left
* 11:30 - 30 min left
* 11:45 - Wrap Up and Q&A
* 12:00 - Thank you & Survey Raffle

=   =   =   =   =   =   =   =   =   =

## Quick Links

🤖 Clone the Workshop Repository!
https://bit.ly/react-x-rest

🚀 Have your Kintone Subdomain ready!
https://kintone.dev/new

📺 YouTube live stream
https://youtu.be/JaWjQkeninU

🏆 Contest
https://bit.ly/kintonecontest23

=   =   =   =   =   =   =   =   =   =

## Waiting Room
=   =   =   =   =   =   =   =   =   =

Hello everyone, the workshop will start real soon!

Be sure you are ready by completing the following tasks:

1. 🤖 Clone the Workshop Repository!  
https://bit.ly/react-x-rest

2. 🚀 Have your Kintone Subdomain ready!
If you have not already, sign up for the FREE Kintone Developer License:  
https://kintone.dev/new

* ✅ Use Chrome or Firefox
* ⚠️ NO Safari
* ⚡ Accept Cookies first!

Thank you for waiting & see you soon!

=   =   =   =   =   =   =   =   =   =

## Node.js

⚡ Node.js v18.16.1 or higher is required to run this workshop.  
(The current LTS version is recommended)

For more information, refer to the Guide on Installing Node.js & npm {macOS & Windows}:
https://bit.ly/nodejs-setup-guide

=   =   =   =   =   =   =   =   =   =

## Start
=   =   =   =   =   =   =   =   =   =

Hello everyone, thank you for joining the workshop!

Here is how to get started:

1. 🤖 Clone the Workshop Repository!
https://bit.ly/react-x-rest

2. 🚀 Have your Kintone Subdomain ready!
If you have not already, sign up for the FREE Kintone Developer License by filling out this web form:  
https://kintone.dev/new

* ✅ Use Chrome or Firefox
* ⚠️ NO Safari
* ⚡ Accept Cookies first!

=   =   =   =   =   =   =   =   =   =

## Live on YouTube

If you get lost, you can "rewind" on our lives stream on YouTube:
https://youtu.be/JaWjQkeninU

=   =   =   =   =   =   =   =   =   =

## Install Commands {Get Started}

# 2 terminal windows are needed for this workshop.

# First clone the workshop repo:

cd Downloads

git clone https://github.com/kintone-workshops/React-x-REST-API-Workshop

cd React-x-REST-API-Workshop

# Then install the dependencies from the project root directory:

npm install

# Then install the dependencies from the backend directory:

cd backend && npm install

=   =   =   =   =   =   =   =   =   =

## Workshop Steps

We have all the steps for the workshop here in the repo:

./docs/Workshop_Steps.md

or https://github.com/kintone-workshops/React-x-REST-API-Workshop/blob/main/docs/Workshop_Steps.md

=   =   =   =   =   =   =   =   =   =

## Where to get Kintone Web Database Subdomain?

Sign up for the FREE Kintone Developer License by filling out this web form:

https://kintone.dev/new

* ✅ Use Chrome or Firefox
* ⚠️ NO Safari
* ⚡ Accept Cookies first!

=   =   =   =   =   =   =   =   =   =

## YouTube
=   =   =   =   =   =   =   =   =   =

This is also live on YouTube:
https://youtu.be/JaWjQkeninU

It is a bit delayed but for those who want to "rewind", this is another great option ~

This workshop will also be uploaded to our YouTube Channel!

Kintone Developer Program
https://bit.ly/KDP_Video

Subscribe so you get notified with the workshop recording gets uploaded! 🔔

=   =   =   =   =   =   =   =   =   =

## Create a .env File

Using the .env.example file as a template, create a .env file.

Then input your Kintone credentials like the following:

SUBDOMAIN = "example"
APPID = "1"
APITOKEN = "1J22qNAR54I4eiMcd0JmfDAavJNfNJDVaqt34X9A"

⚠️ DO NOT DELETE THE .env.example FILE!
.env.example is used by env-cmd to verify that the .env file is correctly configured.

=   =   =   =   =   =   =   =   =   =

## Debugging - Let's Fix Those Problems 💪

Here is a rundown of common problems that may occur & its solutions!

https://github.com/kintone-workshops/React-x-REST-API-Workshop#debugging

If you have additional questions during the workshop, feel free to message me.

=   =   =   =   =   =   =   =   =   =

## Additional Questions 🤔

If you have questions afterwards, post them at our Kintone Developer Community

https://forum.kintone.dev/

=   =   =   =   =   =   =   =   =   =

## Create a Kintone Web Database App

### Fields & Field Codes
How to set the Field Codes for the Kintone App?
1. Hover over the field
2. Click the top right gear icon ⚙️
3. Select Settings from the drop-down menu
4. Click the edit button Edit Button
5. Enter the new field code
6. Click the Save button

⚠️ Field Codes are case-sensitive ⚠️

Set the following Field Codes

3x Text Fields
* Field Name -> Field Code
* Country -> country
* State -> state
* City -> city

Save!

⚡ Be sure to click Save and Activate App buttons! 💪

### Kintone API Token

To generate an API Token for a Kintone App:

1. Go to the Kintone App
1. Go to the Gear icon ⚙️ (top right corner) > Open the App Settings page
1. Click on the **App Settings** Tab > Click on **API Token** settings
1. Click the `Generate` button to generate a token
1. Enable the `View records` & `Add records` checkboxes
1. Click the `Save` button (top left corner) to save the token setting
1. Finally, click the Activate / Update App button (top right corner) to implement the token setting change.

Ref:  
https://github.com/kintone-workshops/React-x-REST-API-Workshop/blob/main/docs/Workshop_Steps.md#d-create-a-kintone-web-database-app

=   =   =   =   =   =   =   =   =   =

## Kintone Customization Tutorials

If you want additional projects to start playing around with Kintone, check out this page:

https://kintone.dev/en/landing-page/tutorial-gallery/

=   =   =   =   =   =   =   =   =   =

## Quick Check-in

Thank you for all those who DM me with questions

Looks like everyone figured out where you need to go.

If you are still stuck, please let me know ~

=   =   =   =   =   =   =   =   =   =

## Looking for the Kintone Subdomain Email? ✉️

Search the following in your email app:

Welcome to Kintone! One More Step to Developer License

The email will be from developer@kintone.com

=   =   =   =   =   =   =   =   =   =

## Errors related to .env

If you get one of the following error messages:  

* [webpack-cli] Error: Missing environment variable: KINTONE_BASE_URL
* [webpack-cli] Error: Missing environment variable: KINTONE_PASSWORD
* [webpack-cli] Error: Missing environment variable: KINTONE_USERNAME
* [webpack-cli] Error: Missing environment variable: VIEW_ID
* [webpack-cli] TypeError: Cannot convert undefined or null to object
* Failed to find .env file at default paths: [./.env,./.env.js,./.env.json]
* Failed to find .env file at default paths: [./.env,./.env.js,./.env.json]
* Failed to upload JavaScript/CSS files
* KintoneRestAPIError: [520] [CB_WA01] Password authentication failed...

Then please verify that
* your .env file has been correctly configured
* your username and password for your Kintone account are correct
* you have not modified the .env.example

=   =   =   =   =   =   =   =   =   =

## Join our Meetup Group
https://www.meetup.com/kintone-developers/

## Got Kintone Questions?

Please post them in our Kintone Developer Community!

https://forum.kintone.dev/

=   =   =   =   =   =   =   =   =   =

## Survey & Gift Card Raffle

Enter to WIN a $25 Amazon Gift Card! 💰️

https://bit.ly/kdp-aug-2023

Your feedback is vital for us to improve our workshop!
Thank you for your time & input ~

=   =   =   =   =   =   =   =   =   =

## Write up your experience!

Post to Dev.to or Medium about your experience with Kintone customization ~

See what others post about Kintone
https://dev.to/t/kintone

You might be interested in
Deploy a REST API calling node.js App to Heroku article

https://dev.to/will_yama/deploy-a-rest-api-calling-node-js-app-to-heroku-2mia

React & REST API: How to render responses

https://dev.to/will_yama/how-to-render-responses-96c

=   =   =   =   =   =   =   =   =   =

If you want to check out our amChart x Data Visualization workshop content:

https://youtu.be/fHNj6MieBzw

=   =   =   =   =   =   =   =   =   =

## Log into Kintone Subdomain?

Your login link would be
YOUR_SUBDOMAIN.kintone.com

---

Subdomain: example
URL: example.kintone.com

=   =   =   =   =   =   =   =   =   =

## step-by-step guide

If you are ever lost, check out our step-by-step guide here:

https://github.com/kintone-workshops/React-x-REST-API-Workshop/blob/main/docs/Workshop_Steps.md

=   =   =   =   =   =   =   =   =   =

## Becoming a Kintone Partner?

https://www.kintone.com/en-us/become-a-partner/

=   =   =   =   =   =   =   =   =   =

## What are Kintone Plug-ins

https://kintone.dev/en/plugins/introduction-to-plug-ins/what-are-kintone-plug-ins/

=   =   =   =   =   =   =   =   =   =

## 🚀 Have your Kintone Subdomain ready!

If you have not already, sign up for the FREE Kintone Developer License by filling out this web form:

https://kintone.dev/new

* ✅ Use Chrome or Firefox
* ⚠️ NO Safari
* ⚡ Accept Cookies first!

=   =   =   =   =   =   =   =   =   =

## Got Questions? 🤔
Feel free to msg me with a workshop-related or a general Kintone question to me anytime ~

=   =   =   =   =   =   =   =   =   =

## Why use Kintone?
* Super easy to use database / backend solution
* You can use vanilla JS to build customizations right on the platform
* Companies are hiring engineers to build Kintone integrations

More information:
* Get Hacking with Kintone - https://kintone.dev/en/landing-page/hackathon/
* Job Listing - Kintone Developer Forum - https://forum.kintone.dev/t/seeking-independent-contractors-with-kintone-customization-programming-skills/550

=   =   =   =   =   =   =   =   =   =

## Start the servers

Open two terminal windows

From the project root directory, run:
npm run start

From the backend directory, run:
npm run start

=   =   =   =   =   =   =   =   =   =

## Where to get the Subdomain, View ID, and App ID?

Go to your Kintone App's custom view & grab the URL
Kintone App's URL follows this template:
https://<SUBDOMAIN>.kintone.com/k/<App_ID>/
Example:

https://example.kintone.com/k/1/
Subdomain = example
KINTONE_BASE_URL = https://example.kintone.com
App ID = 1

=   =   =   =   =   =   =   =   =   =

## Live on YouTube

If you get lost, you can "rewind" on our lives stream on YouTube:
https://youtu.be/JaWjQkeninU

=   =   =   =   =   =   =   =   =   =

Direct Message with your email address if you forgot your Kintone Subdomain

=   =   =   =   =   =   =   =   =   =

The KINTONE_BASE_URL variable is based on your subdomain.

For example:
Subdomain = example
KINTONE_BASE_URL = https://example.kintone.com

=   =   =   =   =   =   =   =   =   =

## Contest

https://dev.to/kintonedevprogram/contest-kintone-customization-contest-2023-3bkl

* Example: https://dev.to/kintonedevprogram/js-customization-to-generate-qr-code-from-kintone-record-values-27e8
* Contest: https://dev.to/kintonedevprogram/contest-kintone-customization-contest-2023-3bkl
* Forum Category: https://forum.kintone.dev/c/contest/11

=   =   =   =   =   =   =   =   =   =

## Completed Code

If you want the completed code for the index.js file, you can find it here:  
./docs/Solution_server.js

=   =   =   =   =   =   =   =   =   =
