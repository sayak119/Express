# Express

## Inspiration

**AAC** or **Augmentative and Alternative Communication** can be defined as a non-speech form of communication. This form of communication usually uses images and/or speech generating mechanism. The need for AAC is due to various reasons. Some of frequent AAC users are people who are treated with the following -

* Autism - About **1%** of world's population has autism spectrum disorder.
* Parkinson's disease - About **1 million** people are affected by it alone in the U.S.
* Cerebral Palsy - About **17 million** people are affected by it globally.
* Dementia - Around **50 million** people have dementia worldwide with around **10 million** new cases every year.
* Traumatic Brain Injury - Results in loss of speech or not able to form words or loss of memory.
* People who can't speak (mute) -  It effects around **40 million** people globally.

Speech is the most important form of communication. In this age of connectivity, people with disability should not be left behind irrespective of their age, gender, etc. The best form of communication for them is via pictures or images or a mix of both.

## What it does

**Express** is a react native app that combines images with verbal cues so that people with disability can communicate. It is intuitive, helps build communication and bonding. With each image, there are words that describe it and questions or statements related with that image. For example: With image of water, there are statements like I want to drink water. Now this would not be a complete solution in our opinion. So we had to add text to speech conversion so that it can be played instead of showing the screen to give a more natural feeling. It also has different rate of speech and pitch which can be adjusted according to the needs.

 This can be helpful in everyday life in various scenarios like kids who lie in the autism spectrum can use it to communicate with their parents, teachers, friends, etc and ask them for help or express their feelings. People with dementia can use it to remember family members or helpers or ask for day to day things and places. People who are learning sign languages, in their early stage, can use it to communicate or can also use it to communicate with other people who don't know sign language. It will help the community to become understandable.

It is a multi language app so that its reach can become global.

## How I built it

First of all we searched about the various problems which are in the community and which hinders communication. We came to know what problems people face when they can't use their voice or even facial expressions to express themselves properly or to just simply interact. We are a group of students and we came up with this idea. Built using react-native, reactjs, google-translate and expo.

## Challenges I ran into

We are fairly new to react-native and expo and setting up was one of the challenges.

## Accomplishments that I'm proud of

The app works

## Installation

* Clone the directory 

`git clone https://github.com/sayak119/Express.git`
* Then run the following commands

```
cd Express
npm i
sudo sysctl -w fs.inotify.max_user_instances=1024
sudo sysctl -w fs.inotify.max_user_watches=12288
npm start
```
* This will start the packager and give you a QR code to scan for Expo.
* Now install the Expo app for Android (tested on that) from the Google Play Store and make an account.
* Connect your local machine using your phone's hotspot (because they need to be on the same ip). You can also create your custom domain by setting an environment variable.
* Now scan the QR code using the expo app.

**You can also publish the app**
```
sudo npm i -g exp
exp start
exp publish
```

## What's next for Express

I will try to add sign languages and add more languages.

**The images were taken from [Flaticon](https://www.flaticon.com/)**
