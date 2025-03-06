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

The consensus was done by collecting the issues found by the 3 experts and analyzing the reason behind the statement. 

#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)

- [expert4_heuristic_evaluation_workbook](heuristic_evaluations/expert4_heuristic_evaluation_workbook.md)

#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | **Expert 2** | **Expert 3** | **Expert 4**| **Overall** | **Recommendations** |
| --------------- | ------------ | ------------ | ------------ | ----------- | ----------- | ------------------- |
| It was unclear why a workout started downloading a few days after installing the app. | 3 | 2 | 3 | 1 |  | Add a notification or explanatory message before the download starts, clarifying the reason (e.g., workout program update, automatic synchronization, etc.). |
When downloading a workout, I cant tell how long the download will take | 1 | 1 | 1 | 1 |  | Progress Bar for download.|
| When creating a workout, there is no progress to show how many exercises needed to create a workout | 1 | 2 | 1 | 1 | | Progress bar on top of screen, that shows progress with the exercises added |
| When choosing which days to work out, the buttons are by default all selected, which makes it confusing and easy to instead deselect the buttons you think you're selecting | 1 | 2 | ? | 3 |  |Make it clearer which buttons are selected by having a border around them |
| The names and instructions of some exercises differ in Brazilian Portuguese and European Portuguese.| 3 | 2 | 1 | 1 |  | Review exercise descriptions with native speakers and consider adaptations for European Portuguese. |
| Opening the app for the first time, there's a button that's in italian when the system is in portuguese from Portugal. | 2 | 1 | 1 | 2 |  | Fix the translation. |
| It is unclear how to change the app's language or if it is even possible. | 3 | 3 | 3 | 3 | | Add a clear language change option in the settings and an explanatory element in the interface. |
| There's no option to cancel a download. | 2 | 2 | 3 | 2 |  | Add an clear interface and with the right icon to represent a stop download button. |
| The analog clock used to choose when to work out is not very straightforward and may confuse some users. | 0 | 1 | 0 | 2 |  | Have a more simple interface to type the hour. |
| Custom workouts may show up twice as duplicates. | 2 | 3 | 2 | 3 |  | Fix them to only show once. |
| On the workout page, the most important information (the workout itself) is placed after additional content, which violates common navigation standards, as users expect the main content to be positioned at the top of the page. | 3 | 2 | 2 | 3 |  | Move the workout section to the top of the page to follow common interface standards, improving navigation and making it easier for users to find the main content. |
| When switching difficulties, workout days, or general goals, the app doesnt warn the user of the changes that may happen in the UI, and the possible problems. | 3 | 3 | 2 | 2 |  | Indicate to the user, when they perform more general settings changes and if the change is significant, what the alteration to the app are going to be. |
| The user can thoughtlessly start a workout without a warning. | 1 | 2 | 2 | 0 |  | Add a confirmation prompt that indicates the user he is about to start a workout. |
| The user can download things without meaning to. | 2 | 2 | 2 | 1 |  | Add a confirmation prompt informing the user that he is about to start a download. |
| Global group workouts are shown to be scheduled for `in 20148 days` by default. That's an error, as when clicked it shows under 1 minute wait times. | 1 | 2 | 1 | 2 |  | Fix to show the real date. |
| During the workout, it wasn't obvious that touching the screen would allow you to pause, repeat an exercise, move to the next one, or exit. | 1 | 2 | 1 | 1 |  | Add visual cues (e.g., semi-transparent icons for pause, next, or exit) and a short tutorial screen before the first workout. |
| Some achievements do not have a clear explanation of what they are awarded for. | 2 | 1 | 1 | 1 |  | Add brief descriptions or explanations to each achievement so that users understand how they are earned.|
| Its hard to tell where the option to change overall training difficulty and goals is (top right corner in "plan" tab). | 1 | 2 | 2 | 2 |  | Make the icon more prominent, or change it to something that indicates better what it is. |
| There is no option to play music during exercises. | 3 | 1 | 2 | 0 |  | Add a feature to play music during exercises, allowing users to choose built-in tracks or use their own music. |
| There is a lack of variety in exercises in the app's free version. | 3 | 2 | 3 | 2 |  | Add more diverse exercises to the free version, allowing users to choose based on their preferences, difficulty levels, or goals.|
| When trying to access the full list of possible workouts, by selecting the option "workout", in the bottom, i have to scroll all the way down, past more insignificant customization options, to see the list. Its also possible to see the full list by pressing the search symbol on the top right, but that is less intuitive. | 2 | 2 | 2 | 2 |  | Move the "all workouts" option to the top of the page. |
| The app allows for favouriting your favourite workouts, which saves time, but you are not able to favourite your custom workouts, which seems like a missed opportunity. | 2 | 1 | 1 | 2 |  | Let the user favourite both default and custom workouts for easy access. |
| Not many other shortcuts, app widgets, or tooltips are present. | 0 | 1 | 0 | 1 |  | Add widgets or shortcuts to increase ease of use for experienced users. |
| Intrusive membership signup messages. | 2 | 2 | 2 | 2 |  | Make them appear less often or in more specific situations where they would actually be required to access those features. |
| The app contains a lot of seemingly unnecessary features for most users, like duels, challenges, achievements, etc. that the average user would not go out of their way to do on their workout app. | 4| 3 | 3 | 3 |  | Make the more essential features be in focus. |
| There's no tutorial in the app the first time using it. | 1 | 0 | 2 | 1 |  | Make a little tutorial that explains what every section is about and the main features. |
| The Terms of Use and the Privacy Policy are blank | 3 | 2 | 3 | 2 |  | Fix the link that brought to the Terms of Use and the Privacy Policy.
| There is no option to enable or disable a brief explanation before starting an exercise.  | 2 | 1 | 2 | 2 |  | Add a setting that allows automatically playing an instruction before each exercise, with the option to disable it in the settings. |  
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



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 26-02-2025 | Francisco/ student      | Does most things on paper and would require a complete solution | [📄 Notes](interviews/interview-Francisco.md) |     |
| ...        |                    |                                                                 |                              |     |

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
