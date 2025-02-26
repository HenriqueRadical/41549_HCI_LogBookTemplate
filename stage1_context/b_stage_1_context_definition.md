[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| [Amazon Shoes]    | [Online platform selling shoe laces]        | [[Competitor Analysis AmazonShoes]] |
| [Fnac Atacadores] | [Smartphone app to buy and sell shoe laces] |                                     |





## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]


#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

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

Task: Doing a workout

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Select a goal   | Yes	|  There is text to explain what to do and must select one of three goals to continue|	Yes |  There is bar on top of the app to show the progress | | | |
| 2      | Choose the days to workout   | Yes |  Text saying what to do and must select at least one day to workout | Yes	|  The bar on top will progress  | | | |
| 3      | Choose the time to workout   | Yes |  There is a text to explain the step and will prompt a interface to choose the time     | Yes |  After the choosing the time of the day to workout, will switch to the Plans Section     | | | |
| 4    | Start the workout | Yes 	|  The button is big and blue and it says "Start the workout" | Yes | The screen changes to Workout mode showing the current exercise and the timer | | |

---

Task: Create and personalize a workout

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Move to the workouts section   |  Yes                                         |   On the bottom of the app show the different sections    | Yes | The section shows the different workouts categories | | | |
| 2      | Scroll down to "Custom Made" section  | Yes | It's intuitive to scroll down because the "Events" section is being shown halfway through | Yes | After entering the "Custom Made" section, there is a text explaining the section and a button to create a workout | | | |
| 3      | Click to create a workout | Yes | There is a button blue that stands out more and it says "Create Workout"   | Yes                                                                                  | It loads a list of exercises available | | | |
| 4      |  Choose the exercises to add to workout | Yes |   The list of exercises have an plus icon on right to add the exercise   | No | To create a workout its needs at least 3 exercises | | Add a progress bar to show progress of creating a workout | |
| 5    | Save the workout | Yes | There is blue button saying "Done" | Yes | Goes back to the "Custom Made" section showing the workout just created | | | |



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
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
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
