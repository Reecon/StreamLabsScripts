# Reecon's StreamLabs Chatbot Scripts

Hey there! Thanks for checking out my scripting foo.

Here is an overview of the stuff I made for the StreamLabs Chatbot. Give feedback, request features or improve/change things yourself :)

## CatchPhrases

[Repository](https://github.com/Reecon/SLCatchPhrases "CatPhrases Repository")

[Latest Release](https://github.com/Reecon/SLCatchPhrases/releases/latest "CatchPhrases Latest Release")

This catches phrases (get it? -.- ) or keywords you can define via regular expressions and sends the defined responses to chat.

The syntax for the config file looks like this:
`/.*[wW].*[oO].*[wW].*/ "WOW"`

And here is a screenshot of the UI in the bot.

![CatchPhrases Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/CatchPhrases.png "CatchPhrases Bot UI")

## Singularity

[Repository](https://github.com/Reecon/SLSingularity "Singularity Repository")

[Latest Release](https://github.com/Reecon/SLSingularity/releases/latest "Singularity Latest Release")

A simple script that allows people to whisper the bot for TextToSpeech. It uses the built in Windows TTS engine and voices.

![Singularity Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/Singularity.png "Singularity Bot UI")

## CareBearStare

[Repository](https://github.com/Reecon/SLCareBearStare "CareBearStare Repository")

[Latest Release](https://github.com/Reecon/SLCareBearStare/releases/latest "CareBearStare Latest Release")

This script is alternative to the normal shoutout command. What makes this special is the ability to define custom responses based on the shoutout target.

It also comes with an overlay which shows the targets user image and the defined blurb. It's simple HTML that can be animated with CSS in OBS's browser source settings, for example.

![CareBearStare Animation Example](https://github.com/Reecon/StreamLabsScripts/raw/master/images/stare_animation.gif "CareBearStare Animation Example")

![CareBearStare Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/CareBearStare.png "CareBearStare Bot UI")

## PetQueue

[Repository](https://github.com/Reecon/SLPetQueue "PetQueue Repository")

[Latest Release](https://github.com/Reecon/SLPetQueue/releases/latest "PetQueue Latest Release")

If you like seeing people's pets and don't want to miss any in chat, this is the thing for you! This gives folks a chat command that collects the links and displays them on a simple website, so you can go through them when the time is right.

![PetQueue WebUI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/PetQueueBrowser.png "PetQueue WebUI")

![PetQueue Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/PetQueue.png "PetQueue Bot UI")

## CombinedDonationBar

[Repository](https://github.com/Reecon/SLCombinedDonationBar "CombinedDonationBar Repository")

Although basic functionality is working, this is still under construction.

It's a simple donation bar, but it combines StreamLabs donations and Cheers in your channel to go towards a common goal.

![CombinedDonationBar Overlay](https://github.com/Reecon/StreamLabsScripts/raw/master/images/bar_animation.gif "CombinedDonationBar Overlay")

![CombinedDonationBar Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/ProgressBar.png "CombinedDonationBar Bot UI")

## RaidBot

[Repository](https://github.com/Reecon/SLRaidBot "RaidBot Repository")

In early development.

Keeps track of channel you raid/host and channels that raid/host you. You can also add channels manually.

The website shows you a quick overview of the channels that raided/hosted you and that you raided/hosted. The list is sorted in reverse order of the last channel you hosted. It also shows who is currently online and what they are streaming.

Screenshot of the current UI with example data.

![RaidBot WebUI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/RaidBotWeb.png "RaidBot WebUI")

![RaidBot Bot UI](https://github.com/Reecon/StreamLabsScripts/raw/master/images/RaidBot.png "RaidBot Bot UI")
