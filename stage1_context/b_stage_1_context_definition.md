[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Seven    |  Gives 7-minute long daily workouts        | [Competitor Analysis Seven](competitors/Competitor%20Analysis%20Seven.md) |





## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method

We used four experts that did a analysis to the app using the heuristics by the Nielsen Norman Group, considering the following severity scale:

> 0 - I don't agree that this is a usability problem at all;
> 1 - Cosmetic problem;
> 2 - Minor usability problem; 
> 3 - Major usability problem;
> 4 - Usability catastrophe.

The consensus was done by collecting the issues found by the 4 experts and analyzing the reason behind the statement. 

#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)

- [expert4_heuristic_evaluation_workbook](heuristic_evaluations/expert4_heuristic_evaluation_workbook.md)

#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | **Expert 2** | **Expert 3** | **Expert 4**| **Overall** | **Recommendations** |
| --------------- | ------------ | ------------ | ------------ | ----------- | ----------- | ------------------- |
| It was unclear why a workout started downloading a few days after installing the app. | 3 | 2 | 3 | 1 | 2 | Add a notification or explanatory message before the download starts, clarifying the reason (e.g., workout program update, automatic synchronization, etc.). |
When downloading a workout, I cant tell how long the download will take | 1 | 1 | 1 | 1 | 1 | Progress Bar for download.|
| When creating a workout, there is no progress to show how many exercises needed to create a workout | 1 | 2 | 1 | 1 | 1 | Progress bar on top of screen, that shows progress with the exercises added |
| When choosing which days to work out, the buttons are by default all selected, which makes it confusing and easy to instead deselect the buttons you think you're selecting | 1 | 2 | 2 | 3 | 2 |Make it clearer which buttons are selected by having a border around them |
| The names and instructions of some exercises differ in Brazilian Portuguese and European Portuguese.| 3 | 2 | 1 | 1 | 2 | Review exercise descriptions with native speakers and consider adaptations for European Portuguese. |
| Opening the app for the first time, there's a button that's in italian when the system is in portuguese from Portugal. | 2 | 1 | 1 | 2 | 2 | Fix the translation. |
| It is unclear how to change the app's language or if it is even possible. | 3 | 3 | 3 | 3 | 3 | Add a clear language change option in the settings and an explanatory element in the interface. |
| There's no option to cancel a download. | 2 | 2 | 3 | 2 | 2 | Add an clear interface and with the right icon to represent a stop download button. |
| The analog clock used to choose when to work out is not very straightforward and may confuse some users. | 0 | 1 | 0 | 2 | 1 | Have a more simple interface to type the hour. |
| Custom workouts may show up twice as duplicates. | 2 | 3 | 2 | 3 | 3 | Fix them to only show once. |
| On the workout page, the most important information (the workout itself) is placed after additional content, which violates common navigation standards, as users expect the main content to be positioned at the top of the page. | 3 | 2 | 2 | 3 | 3 | Move the workout section to the top of the page to follow common interface standards, improving navigation and making it easier for users to find the main content. |
| When switching difficulties, workout days, or general goals, the app doesnt warn the user of the changes that may happen in the UI, and the possible problems. | 3 | 3 | 2 | 2 | 3 | Indicate to the user, when they perform more general settings changes and if the change is significant, what the alteration to the app are going to be. |
| The user can thoughtlessly start a workout without a warning. | 1 | 2 | 2 | 0 | 1 | Add a confirmation prompt that indicates the user he is about to start a workout. |
| The user can download things without meaning to. | 2 | 2 | 2 | 1 | 2 | Add a confirmation prompt informing the user that he is about to start a download. |
| Global group workouts are shown to be scheduled for `in 20148 days` by default. That's an error, as when clicked it shows under 1 minute wait times. | 1 | 2 | 1 | 2 | 2 | Fix to show the real date. |
| During the workout, it wasn't obvious that touching the screen would allow you to pause, repeat an exercise, move to the next one, or exit. | 1 | 2 | 1 | 1 | 1 | Add visual cues (e.g., semi-transparent icons for pause, next, or exit) and a short tutorial screen before the first workout. |
| Some achievements do not have a clear explanation of what they are awarded for. | 2 | 1 | 1 | 1 | 1 | Add brief descriptions or explanations to each achievement so that users understand how they are earned.|
| Its hard to tell where the option to change overall training difficulty and goals is (top right corner in "plan" tab). | 1 | 2 | 2 | 2 | 2 | Make the icon more prominent, or change it to something that indicates better what it is. |
| There is no option to play music during exercises. | 3 | 1 | 2 | 0 | 2 | Add a feature to play music during exercises, allowing users to choose built-in tracks or use their own music. |
| There is a lack of variety in exercises in the app's free version. | 3 | 2 | 3 | 2 | 3 | Add more diverse exercises to the free version, allowing users to choose based on their preferences, difficulty levels, or goals.|
| When trying to access the full list of possible workouts, by selecting the option "workout", in the bottom, i have to scroll all the way down, past more insignificant customization options, to see the list. Its also possible to see the full list by pressing the search symbol on the top right, but that is less intuitive. | 2 | 2 | 2 | 2 | 2 | Move the "all workouts" option to the top of the page. |
| The app allows for favouriting your favourite workouts, which saves time, but you are not able to favourite your custom workouts, which seems like a missed opportunity. | 2 | 1 | 1 | 2 | 2 | Let the user favourite both default and custom workouts for easy access. |
| Not many other shortcuts, app widgets, or tooltips are present. | 0 | 1 | 0 | 1 | 1 | Add widgets or shortcuts to increase ease of use for experienced users. |
| Intrusive membership signup messages. | 2 | 2 | 2 | 2 | 2 | Make them appear less often or in more specific situations where they would actually be required to access those features. |
| The app contains a lot of seemingly unnecessary features for most users, like duels, challenges, achievements, etc. that the average user would not go out of their way to do on their workout app. | 4 | 3 | 3 | 3 | 3 | Make the more essential features be in focus. |
| There's no tutorial in the app the first time using it. | 1 | 0 | 2 | 1 | 1 | Make a little tutorial that explains what every section is about and the main features. |
| The Terms of Use and the Privacy Policy are blank | 3 | 2 | 3 | 2 | 3 | Fix the link that brought to the Terms of Use and the Privacy Policy.
| There is no option to enable or disable a brief explanation before starting an exercise.  | 2 | 1 | 2 | 2 | 2 | Add a setting that allows automatically playing an instruction before each exercise, with the option to disable it in the settings. |  
### - Cognitive Walkthrough

#### Method

In this process we tried to simulate the thought process of new user i.e. a person who has just installed the app Seven and is trying to perform basic tasks, as explained in the next section.

#### Task Selection and Task Analysis

The tasks selected are **"Doing a workout"** and **"Create and personalize a workout"** because the main focus of this system is to give the workouts in question to the users and these tasks must have simple and clear steps to achieve. Otherwise, the app fails its primary objective.

| Task                          | Subtasks                              |
| ----------------------------- | --------------------------------------|
| 	**1. Doing a workout** 		| Select a goal							|
|								| Choose the days to workout			|
|								| Choose the time of workout			| 
|                               | Start workout            				|

| Task                          | Subtasks                              |
| ----------------------------- | --------------------------------------|
| **1. Create and personalize a workout**| Move to the workouts section |
| 								| Scroll down to "Custom Made" section	|
|								| Click to create a workout				|
|								| Choose the exercises to add to workout| 
|								| Save the workout 						|

#### Results

Task: **Doing a workout**

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Select a goal   | Yes	|  There's text to explain what to do and you must select one of three goals to continue|	Yes |  There is a bar on top of the app to show the progress | | | |
| 2      | Choose the days to workout   | Yes |  There's text saying what to do and you must select at least one day to workout | Yes	|  The bar on top will progress  | | | |
| 3      | Choose the time to workout   | Yes |  There's text to explain the step and you get shown an interface to choose the time     | Yes |  After choosing the time of day to workout, it switches to the Plans Section     | | | |
| 4    | Start the workout | Yes 	|  There's an easily viewable "Start the workout" button | Yes | The screen changes to Workout mode, showing the current exercise and the timer | | |

---

Task: **Create and personalize a workout**

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Move to the workouts section   |  Yes                                         |   On the bottom of the app show the different sections    | Yes | The section shows the different workouts categories | | | |
| 2      | Scroll down to "Custom Made" section  | Yes | It's intuitive to scroll down because the "Events" section is being shown halfway down the page | Yes | After entering the "Custom Made" section, there's text explaining the section and a button to create a workout | | | |
| 3      | Click to create a workout | Yes | There is a button blue that stands out more and it says "Create Workout"   | Yes                                                                                  | It loads a list of exercises available | | | |
| 4      |  Choose the exercises to add to workout | Yes |   The list of exercises have an plus icon on right to add the exercise   | No | To create a workout it needs at least 3 exercises | | Add a progress bar to show progress of creating a workout | |
| 5    | Save the workout | Yes | There's a blue "Done" button | Yes | Goes back to the "Custom Made" section showing the workout just created | | | |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluation, cognitive walkthrough, online reviews, user feedback, etc.]

### SWOT Analysis

|   Strengths   |
| ------------ |
Offers simple workouts, clear and without eqquipment.
The app has intituive and easy to understand user interface.
This app is also available for smart watches.
The idea of Gamification is that feeling like completing a workout is a quest game, helps build a habit.
Having reminders helps with the consistency.

| Weaknesses |
| ---------- |
This app just provides basic personalization.
Lack of variety in exercises in the app's free version.
Some settings don't specify what happens when changing it.

| Opportunities |
| ------------- |
A option to play music from spotify/youtube music or from your own device songs.

| Threats |
| ------- |
The competitor offers more trackers like how much water the user drank or how many steps taken.
The panel of stats is accessed more quickly in a competing app.

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

The approach used to communicate with users involved conducting interviews with a diverse group of people for whom sports are an important part of their lives, as well as with those who actively use or are interested in fitness apps. The goal of the interviews was to understand their needs, preferences, and challenges when using fitness apps, as well as to gather information about their expectations. 

The questions considered during the interview focused on understanding the user's daily routine, sports habits, goals, and motivation for working out, as well as their expectations from fitness apps. The questions were grouped into several categories: general questions about physical activities, goals and motivation, features and usability of fitness apps, personalization and analytics, and social integration within the app. Questions:

**Main Questions**

1.Can you describe your typical day?

2.Do you engage in any sports or physical activities? If not, would you like to start in the future?

3.What types of sports or physical activities do you prefer? Why?

4.Do you use any apps or devices for your workouts? If yes, which ones?

**Questions About Goals and Motivation**

5.What goals do you set for yourself when engaging in sports (weight loss, muscle gain, endurance, etc.)?

6.What motivates you to continue working out? / What motivates you to start training?

7.What obstacles prevent you from achieving your fitness goals?

**Questions About Features and Usability**

8.What features are most important to you in a fitness app?

9.Are there any features you would like to see in fitness apps that you haven't found yet? / What kind of support or tips would you like to receive in an app?

10.What do you like about existing fitness apps?

11.What frustrates or annoys you about existing fitness apps?

12.What would an ideal fitness app look like for you?

**Questions About Personalization and Analytics**

13.How important are personalized recommendations and workouts to you?

14.How important is progress tracking and achievement monitoring for you?

15.What kind of information or analytics about your workouts would you like to see in an app?

**Questions About Social Integration**

16.How important are social features, such as sharing achievements or competing with friends?

17.What role does the community play in your motivation to work out?

18.Do you have any suggestions for improving interaction with other users in fitness apps? 
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 26-02-2025 | Francisco / student      | Does most things on paper and would require a complete solution | [📄 Francisco](interviews/interview-Francisco.md) |     |
| 27-02-2025 | Bernardo Lázaros / student |                                                           | [📄 Bernardo](interviews/interview-Bernardo.md) |     |
| 27-02-2025 | Paulo Dias / professor at the university |                                                | [📄 Paulo](interviews/interview-Paulo.md)     |     |
| 27-02-2025 | Solomiia Koba / student |                                                | [📄 Solomiia](interviews/interview-Solomiia.md)     |     |
| 27-02-2025 | Tomás / student |                                                | [📄 Tomas](interviews/interview-Tomas.md)     |     |
| 03-03-2025 | Lyosha / works in an alcohol store |                                                | [📄 Lyosha](interviews/interview-Lyosha.md)     |     |
| 04-03-2025 | Styopa / works at a university |                                                | [📄 Styopa](interviews/interview-Styopa.md)     |     |
| 05-03-2025 | Sasha / student |                                                | [📄 Sasha](interviews/interview-Sasha.md)     |     |




### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
