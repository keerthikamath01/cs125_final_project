# CS125 Final Project - Catch Phrase Game (Android App)

## Project Overview

This is an Android app implementation of the classic Catch Phrase game.
Players select a category, then have 60 seconds to describe words to their team while keeping score.
The app leverages Java programming, Android UI design with XML, and API integration.

## How to Play

1. Launch the App → Start in LaunchActivity
2. Navigate to MainActivity → see the Categories Page
    - Four categories: Disney, Animals, Sports, UIUC
    - First three categories use the Datamuse API to fetch words dynamically
    - UIUC category uses a predefined array of words
3. Navigate to GameActivity → 60-second gameplay:
    - Word appears in the center
    - Countdown timer at the top
    - Score displayed at the bottom
    - **Tap right side** → mark word as correct (score +1)
    - **Tap left side** → pass the word

## Features
- Four dynamic and static categories of words
- Countdown timer for fast-paced gameplay
- Tap-based interactions for correct/passed words
- UI designed with XML layouts

## Project Structure
- Java files: LaunchActivity.java, MainActivity.java, GameActivity.java
- Layout files: activity_launch.xml, activity_main.xml, activity_game.xml

## Project Video
https://youtu.be/uIb_zqq2zAU

## Setup Notes
- This project was originally created in 2020 and uses an older Android Gradle setup (AGP 3.5.3)
- May require updating Gradle/AGP to build in modern Android Studio
- Uses Java 8

## Technologies
- Java 8
- Android Studio (older version)
- Gradle 5.4.1 (original project)
- Datamuse API for word categories
