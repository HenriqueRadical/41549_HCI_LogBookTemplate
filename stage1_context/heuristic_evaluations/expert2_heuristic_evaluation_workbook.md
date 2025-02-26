<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Diogo Nascimento
**Date**: 26-02-2025
**Product**: Seven app


Severity Scale adopted: 0 - I don't agree that this is a usability problem at all; 1 - Cosmetic problem; 2 - Minor usability problem; 3 - Major usability problem; 4 - Usability catastrophe.
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                      | **Severity** | Recommendation                         |
| ---------------------------------------------- | ------------ | -------------------------------------- |
| When downloading a workout, I cant tell        |      1       | Progress Bar for download              |
| how long the download will take                |              |                                        |
| ---------------------------------------------- | ------------ | -------------------------------------- |
| When I reopen the app, there is no clear       |      2       | Show a intuitive "symbol" to indicate  |
| way to see if Ive already done a workout today |              | a workout has already been done today  |
| I have a streak of two days, but only sunday appears to be marked as "complete". Also I have done a lot of workouts on Wednesday (I havent I merely pretended to (as I did on Sunday)), and not only does Wednesday not appears as "complete", I also cant go back to previous days to see what I did, including Sunday | 4 | Allow the user to go back through previous days to see what workouts they did |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| User may not be familiar with terms such as "Core", or may not be able to diferentiate between a "Cardio" or "Strength" training | 0            | Nevermind, they have it |
| I cant change the language, and if I can, I cant find it anywhere | 3            | If its there, make it more visible, like in the profile, if it isnt, put it there               |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Go back arrow is too small and maybe easily probably missable | 0            | Make it bigger or something               |
| Another thing   | 4            |                |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| When switching difficulties, workout days, or general goals, the app doesnt warn the user of the changes that may happen in the UI, and the possible problems | 1            | Indicate to the user, when they perform more general settings changes and if the change is significant, what the alteration to the app are going to be |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Its hard to tell where the option to change overall training difficulty and goals is (top right corner in "plan" tab) | 2            | Make the icon more prominent, or change it to something that indicates better what it is |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| When trying to access the full list of possible workouts, by selecting the option "workout", in the bottom, i have to scroll all the way down, past more insignificant customization options, to see the list. Its also possible to see the full list by pressing the search symbol on the top right, but that is less intuitive | 2            | Move the "all workouts" option to the top of the page |


# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The navigation on the page "workouts" feels clutered with options I selected once, and then never again | 2            | In the "workouts" tab, more space should be given to options like "Categories" and "Custom made", and less for options like "Instructors" or "Challenges"  |
| Another thing   | 4            |                |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| There are no error messages | 0            | Make errors on purpose idk |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Everything seems well documented | 0            | Keep it up               |
