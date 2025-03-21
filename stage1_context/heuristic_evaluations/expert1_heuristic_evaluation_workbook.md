<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Maria-Aleksandra Korjenevskaya
**Date**: 25-02-2025
**Product**: Application Seven (portuguese version)

Severity Scale adopted: 
• 0 - I don't agree that this is a usability problem at all; 
• 1 - Cosmetic problem;
• 2 - Minor usability problem;
• 3 - Major usability problem;
• 4 - Usability catastrophe.

Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| It was unclear why a workout started downloading a few days after installing the app.| 3            | Add a notification or explanatory message before the download starts, clarifying the reason (e.g., workout program update, automatic synchronization, etc.).               |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|The names and instructions of some exercises differ in Brazilian Portuguese and European Portuguese.| 3            |Review exercise descriptions with native speakers and consider adaptations for European Portuguese.            |


# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| It is unclear how to change the app's language or if it is even possible. | 3            | Add a clear language change option in the settings and an explanatory element in the interface.               |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|On the workout page, the most important information (the workout itself) is placed after additional content, which violates common navigation standards, as users expect the main content to be positioned at the top of the page. | 3            | Move the workout section to the top of the page to follow common interface standards, improving navigation and making it easier for users to find the main content.               |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|There is no confirmation step before starting a workout, which may lead to accidentally starting the wrong workout. | 1          |Add a confirmation step before starting the workout so that users can ensure they have selected the correct one.                |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|During the workout, it wasn't obvious that touching the screen would allow you to pause, repeat an exercise, move to the next one, or exit. | 1            | Add visual cues (e.g., semi-transparent icons for pause, next, or exit) and a short tutorial screen before the first workout.              |
| Some achievements do not have a clear explanation of what they are awarded for. | 2           |Add brief descriptions or explanations to each achievement so that users understand how they are earned                |
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| There is no option to play music during exercises. | 3            | Add a feature to play music during exercises, allowing users to choose built-in tracks or use their own music.               |
| There is a lack of variety in exercises in the app's free version. | 3            | Add more diverse exercises to the free version, allowing users to choose based on their preferences, difficulty levels, or goals.|
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

The visual design is focused on the essentials. No changes needed. The design is minimalistic and effectively prioritizes the most relevant information.
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

I haven't encountered any situations with errors in the app to evaluate this point.

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|There are no tips for beginners.| 2           |Introduce a tutorial mode upon first use.              |
|There is no option to enable or disable a brief explanation before starting an exercise.  | 2           | Add a setting that allows automatically playing an instruction before each exercise, with the option to disable it in the settings.               |
