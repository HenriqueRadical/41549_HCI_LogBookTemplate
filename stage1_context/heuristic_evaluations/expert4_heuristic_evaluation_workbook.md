<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Henrique Reveles 119786
**Date**: 26-02-2025
**Product**: App Seven

Severity Scale adopted: 

• 0 - I don't agree that this is a usability problem at all;

• 1 - Cosmetic problem;

• 2 - Minor usability problem; 

• 3 - Major usability problem;

• 4 - Usability catastrophe.

Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

---

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| When choosing which days to work out, the buttons are by default all selected, which makes it confusing and easy to instead deselect the buttons you think you're selecting | 3            | Make it clearer which buttons are selected by having a border around them instead of a simple color change which could both indicate they are selected or not, making it more confusing               |
| Another thing   | 4            |                |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Everything seems easy to understand, no issues were found.   | 0            |                |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The analog clock used to choose when to work out is not very straightforward and may confuse some users. | 3            | Have a more simple interface to type the hour.               |
| Custom workouts may show up twice as duplicates.   | 4            | Fix them to only show once.               |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| App seems consistent, no issues were found.   | 0            |                |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Global group workouts are shown to be scheduled for `in 20148 days` by default. That's an error, as when clicked it shows under 1 minute wait times. | 4            | Fix to show the real date               |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No issues were found. Mostly only having to select a workout, and then doing it afterwards, not much recall is necessary. | 0            |                |
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The app allows for favouriting your favourite workouts, which saves time, but you are not able ot favourite your custom workouts, which seems like a missed opportunity. | 3            | Let the user favourite both default and custom workouts for easy access.               |
| Not many other shortcuts, app widgets, or tooltips are present.   | 3            | Add widgets or shortcuts to increase ease of use for experienced users.               |
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Intrusive membership signup messages | 3            | Make them appear less often or in more specific situations where they would actually be required to access those features               |
| The app contains a lot fo seemingly unnecessary features for most users, like duels, challenges, achievements, etc. that the average user would not go out of their way to do on their workout app.   | 3            | Make the more essential features be in focus               |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Was unable to locate any errors.   | 0            |                |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Documentation for this app does not seem to exist.  | 4            |                |
