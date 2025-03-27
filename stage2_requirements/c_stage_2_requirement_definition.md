[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: Ana 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Ana\|100](personas/Ana.jpg)  |
| **Name**         | Ana                               |
| **Age**          | 25                             |
| **Occupation**   | Photographer and designer                           |
| **Location**     | She changes location every 2 months                               |
| **Goals**        | Maintain her health and physical well-being           |
| **Pain Points**  | Finding a variety of exercises, which require little to no equipment              |
| **Motivation**   | By keeping herself in shape she is able to travel the world, learn about other cultures and document them     |
| **Full Profile** | [📄 Read More](personas/persona_Ana.md) |

---
## Persona: Rafael 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Rafael\|100](personas/Rafael.jpg)  |
| **Name**         | Rafael                               |
| **Age**          | 30                             |
| **Occupation**   | Finance Analyst                           |
| **Location**     | Aveiro, Portugal                               |
| **Goals**        | Integrate consistent exercise into his life           |
| **Pain Points**  | Lack of a clear direction to take, and way to properly register said direction              |
| **Motivation**   | Stay generally fit and healthy     |
| **Full Profile** | [📄 Read More](personas/persona_Rafael.md) |

---
## Persona: Antonio 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Antonio\|100](personas/Antonio.jpg)            |
| **Name**         | António Almeida                                |
| **Age**          | 27                                 |
| **Occupation**   | Personal trainer                           |
| **Location**     | Leiria, Portugal                               |
| **Goals**        | Bring more people to his gym, and help his clients with workout planning           |
| **Pain Points**  | Hard to keep proper track of his clients' info, and communicate with them about their work            |
| **Motivation**   | Get more clients, and help the business that he cares about                |
| **Full Profile** | [📄 Read More](personas/persona_António.md) |

---


# Scenarios

## Scenario 1-1: Ana wants to do a 10-minute workout at home and invites her friends to join her for a virtual session.

In the evening, while in her apartment, Ana decides to do a 10-minute workout. She opens the fitness app on her phone and in the **"Workouts"** section, she **selects a workout** that she likes and requires no equipment.

Then, Ana decides to **invite her friends to a joint workout**. In the **"Messages"** section, she finds her friends and writes them a message suggesting they train together.

After her friends confirm their participation, Ana **starts the selected workout, inviting her friends to join**. The workout begins once all participants have confirmed their readiness.

During the workout, Ana and her friends **follow the instructions on the screen**. Each participant sees the workout video and can **communicate via voice chat** to maintain communication and motivation during the session.

After the workout is completed, Ana **ends the session**.

## Scenario 2-1: Rafael wants to do one of his favorite workouts

When the workday finishes, Rafael **receives a reminder to work out** on the phone, today he wishes to do a chest workout, having already **marked it as one favorite workout** in his app. The Rafael proceeds with opening the app, and **selecting the "workouts" panel**, where there are displayed all the workouts available in the app. In this panel, he goes to the area of **favorites workouts** and selects the chest workout. Therefore appears **information about the workout** and **selects the option to start the workout**.  

After the workout, Rafael goes to the app and **sees the overall stats**, which show him the duration of the workout and the calories burned. Rafael intrigued about his progress this week, goes **to the panel "stats"** where all his progress is displayed, selecting a period, in this case, **selecting this week**.

## Scenario 2-2: Rafael wishes to create a workout

Rafael finishes watching a video about a specific training style and decides to try it tomorrow, saving a workout based on that. So, he opens the app and **goes to the panel workouts**, **selecting the option to create a new workout**. Emerges a list of exercises, where Rafael **adds which exercises** had been mentioned in the video, after inserting all of the exercises, he **clicks on the option to save**, saving it by the name "Workout for Tuesdays". 

## Scenario 3-1: António adds a new client in the app

After the first day of training with a new client, António asks them if they have [an app] on their phone. The client confirms they have it, and so he asks them to **add him as a dedicated personal trainer** on it.

António starts by opening the app, and **selecting the "socials" option**. Upon opening it, besides the list of all his current clients, he selects the **option to check for "student" requests**, and notices his client already sent him a request. He selects the "green accept" option next to their name, and the app sends him back to the client list, with the newly added client on the top.

By doing this, António hopes to be able to keep a recording of this particular clients **body stats**, alongside any defined **workout schedules** and have a **dedicated way to communicate** with them about fitness.

## Scenario 3-2: António creates a new personal workout for a client

After a day of training with one of his clients, they tell him that they are going on vacation for a couple of weeks and that they would like a recommendation for exercises to do at the end of an afternoon.

He decides to assign his client a simple workout for the next couple of weeks, starting by opening [the app] on his phone, going to the "socials" tab. By selecting the client in his list clients, he can **select the "organize workouts" option**, and after selecting Monday, Wednesday, and Friday, as the days for the workout, he is given the **option to either use one of his already made workouts, or create a brand new one**. Seeing as this client is much older than most, and their training is different than usual, he **chooses the option to "create a new workout" from scratch**.

He selects exercises that he knows target mostly the legs and the core, as well as some specific cardio exercises, including the number of repetitions/duration of each exercise, and a small "interval of 1 minute" in between each exercise. He finishes by pressing "conclude workout".

After arriving home, he remembers that the client was still pretty inexperient, so he decides to record a video of himself performing the full workout, as a means of helping them. After recording, he reopens the app, goes back to "socials", chooses his client, and by **selecting the "edit workout" option**, he uploads his recording and appends it to the workout.

After 2 weeks, the client returns from their trip, and thanks him for the workout he sent, before returning to their regular training.

---

# Requirements


## C.1. Functional requirements

**R1 -** The system must allow the user to consolidate a variety of exercises into a single, easily accessible group (workout);

**R2 -** The system must provide a brief and understandable description of each available exercise;

**R3 -** The user should be able to change their profile stats, including name, picture, weight, height and bio;

**R4 -** The system must provide the user with pre-made workouts, based on their profile attributes;

**R5 -** The user should be able to save certain workouts as favorites, accessing them easily in a designated "favorites" tab;

**R6 -** The user should be able to see and edit their workouts for the week


## C.2. Non-functional requirements

**R1 -** Downloading a new workout should not take more than 3 seconds;

**R2 -** The most commonly utilised options, such as accessing created workouts and checking messages, should be more easily visible, and more readily available;

**R3 -** A user should receive a message or any other notification from another user in less than 3 seconds;

**R4 -** Workouts shared between two users should display the current exercise at the same time for both users

**R5 -** 

**R6 -** 


---
[Back to main Logbook Page](hci_logbook.md)
