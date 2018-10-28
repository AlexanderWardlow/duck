#VerseRehearse
Functional Specification

Team Duck
Last Updated: October 12, 2018

#Overview
_Ducks in a row (DiaR)_
VerseRehearse is an app that helps people memorize Scripture verses by playing two different games.

This Specification is not complete.  It is an overview of what the user will see when they interact with DiaR.  It does not discuss technical details and will need to be adjusted several times before it is finished. More details will be added after discussing the original design with the client and stakeholders.

DiaR is an Android app which will allow users to memorize blocks of text quickly, easily, and efficiently. DiaR utilizes fun games for people to stare at so they can become the new next modern day prophet.

#Customer
- Dr. Brandle

#Employer
- Dr. Stanly

#Intended Audience
Our intended audience is focused on individuals who want to memorize an abundance of Bible Verses. In the future, this app may be able to contain a script to a play or a long presentation. However, this is not the main focus at the time.

#Scenarios

##Scenario 1: Junior
Junior is the Sunday school champion of the third grade class at Peace, Faith, Hope and Love Lutheran Church.  He routinely wins sword drills and is always eagerly waving his stubby hand around when questions are asked.  Junior is currently distressed because he did not get candy the past two weeks at Bible quizzing, due to the fact that he has a really hard time memorizing Bible verses. His mom, dad, baby sister, hamster, and even great aunt Rita are sick and tired of quizzing him morning, afternoon and night over his memory verses. Somehow, he always manages to forget the verses 27 seconds before his Bible quizzing meeting. 

While watching soccer practice one day, Junior's mom hears about a new app, VerseRehearse from Kevin's mom.  She downloads it on her Android phone, and is immediately dazzled by the fun games and how easy it is to use. She thinks even Great Aunt Rita could get the hang of it, and that's saying something.  She shows Junior the new app after practice, and has never looked back.  Because of practicing on VerseRehearse, Junior is now the champion of Bible Quizzing as well, and took home a trophy twice his size last spring at the Semi-Regional Evangelical Louisville 8 year-old Bible Study Tournament.

##Scenario 2: Tammy
Tammy is an undergrad student with a serious caffeine addiction. She's taking 22 credit hours, working in the admissions office, and is on the varsity aerobic walking team at her liberal arts college.  Tammy eyes are a little bleary from all the activity, but she'd still like to make Scripture memorization a priority.  She doesn't know how in the world she'll make time for this and is feeling stuck.  

While browsing the app store one day, Tammy sees the new app VerseRehearse gaining popularity with the masses.  She decided to try it out during a 2AM study session when her brain was too fried to notice she'd been procrastinating for well over two hours.  She chose her favorite verse on the app, picked the game she wanted, and found she could productively memorize late at night, despite all odds, thanks to VerseRehearse.  Now, she's decided that instead of being bombarded by pictures of pumpkin spice lattes and dog vidoes on social media, she'll use VerseRehearse on her phone to memorize Scripture.  Now she can whisper along when the chapel speaker reads Scripture without cracking a Bible, and she knows the verses of encouragement she needs for those late night study sessions.     

#Goals
- interactive activities to assist in memorization of Bible Verses.
- friendly and warm theme that people will want to frequent.
- interfaces and accounts for the user to select preference on which verses to learn and how long they want it to take to learn.
- collect data on users progress and report on this data.


#Non Goals
This version will not support the following features:
    - individual user accounts
    - the option to switch languages
    - coach or teacher dashboard
    - difficulty levels
    - voice recognition
    - verse proficiency tracker 

#Screen by Screen Specification
VerseRehearse has multiple screens that are used when navigating through the app.  Each screen will be created with the same color theme and have a strong sense of unity throughout, which will be done by a graphic designer. Individual screens in VerseRehearse will be bolded for clarity.

#Terms and Conditions
VerseRehearse will collect and send data to researchers about the user's performance after the end of each game.  This information includes the name of the user, the number of question answered incorrectly, total time to complete a single verse, which game played, the number of times attempted on a verse with the specific game, and the date and time the game was completed.

The initial screen after the user first downloads VerseRehearse will include a pop-up of the Terms and Conditions, alerting the user to the fact that their data will be collected, and giving them the option to accept or deny the terms. If denied, the user will not have access to the app. After accepted, the user will not see this pop-up again. Wording of the terms and conditions will be completed by our legal team. 

#HomePage
This page will show a generic welcome message that introduces the app to the user. , and specify the general layout.  The layout is choose a verse, choose a game, study the verse, then play the game.  This greeting will be written by our marketing team.  There will be a button in the center, saying "Let's get started".

#Select Bible Verse
The Select Bible Verse screen will enable a user to choose the book of the Bible, Chapter, and Verse by tapping on drop-down lists.  The Verse chosen will be displayed on the screen.  The user then has the option to choose a different verse or click ok to get started.  

*Technical Note - The user must be connected to the internet to load Bible verse options.  This game can only be played if connected to the internet. If disconnected, display an error message.

#Select Game
After selecting a verse, the user will choose between two games: Frog Hop or Letter Head. These game titles will be displayed with a fun picture and a small description at the bottom of each.  

#Memorization Screen
Next, a screen with the user's chosen verse will be displayed.  No time limit is given for the amount of time a user can study the verse.  Cautious Callie can study for an hour while Rushing Richard can start on it after 15 seconds of cramming.  The user will indicate they are done with studying and ready for the game by clicking the "Let's go" button in the lower right-hand corner. 

#Frog Hop
This game will show a frog sitting on an initial lily pad in a pond waiting to hop to the next lily pad.  Two lily pad options will be displayed with one having the correct first word and the other having an incorrect first word that was generated.

*Techical note: A dictionary of probable first words and middle words of verses can be created.  Check each time to make sure there are no two lily pad options with identical options.  

 If the incorrect answer is chosen, the frog will fall with a splash through the incorrect lily pad and be placed back at the first initial lily pad.  If the user selects the correct lily pad, their frog triumphantly hops to it and the second word's options are generated.  This pattern will continue until the entire verse is completed.  

#LetterHead
This game will have three rounds.  The verse will first show up with three words missing, indicated by a blank space with an underline underneath it.  The next phase will have up to six words missing, and the final stage will have up to ten words missing.  If there are less than the round's amount of missing words, all the spaces will be blank with underlines.  The user must type the correct first letter of each word that is missing from the verse.  If they type in 'r' and that is the correct first letter, the whole word (ex. resurrection) will be filled in for them, and they can move to the next blank.  If the user guesses incorrectly three times on one blank, they will be launched back to the Memorization Screen before continuing with LetterHead game play.

#Play Again?
After completing a game, the Play Again? screen will have two options: Replay or Choose a new verse.  If the user chooses replay, they will go back into the game they just finished and play it again.  If 'new verse' is selected, the user will start the progression from the top again and choose their Bible verse and game again.  During this screen, the user's game information will be sent to researchers for collection.

*Techical Note - the user must be connected to the internet during this screen as well, or an error message will be displayed. 

# Ideas

- Duolingo may be a good template/example to draw inspiration from for this app
- User could only type first letter to fill in words that are missing, possibly even give them choice of three first letters initially

# Feature List

# Definite features

- Games
- Bible verse lookup
- User accounts
- Memorization tools/activities
- Mulitple language support

# Possible features

- User defined lists of verses
- Varying difficulties
- Notifications/Reminders
- Adaptive to obseved skill/proficiency
- Verbal input
- Include sets of verses, Basics
- Bible reading

## Environment/Architecture
What software/hardware will be used in creating project

# Software
Programing will be done with Xamarin.

# Hardware
- Androids to test apps.
- Lab machines for programing.
- Virtual machines (and motherships) may be required.

# Limitations
- Programs must be written in object oriented programing language, such as c#, java. No javascript.

