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
| **Pain Points**  | Hard to find people outside of the gym willing to join, with difficulty finding means to advertise it             |
| **Motivation**   | Get more clients, and help the business that he cares about                |
| **Full Profile** | [📄 Read More](personas/persona_António.md) |

---


# Scenarios


## Scenario 0: Maria goes on a Museum Tour (EXAMPLE, NOT FINAL)

[Maria had always loved modern art, but she often found museum visits overwhelming—so many exhibits, so much information, and little guidance on where to start. Today, she was visiting a contemporary art museum that had recently introduced an **interactive guide**.  ]

[As she entered the museum, Maria received a notification on her phone, reminding her to launch the app. She opened it and was greeted with a personalized welcome screen. The system, aware of her general interests in **digital media and abstract art**, suggested a self-guided tour tailored to her preferences.  ]

[Curious, Maria followed the suggested path. As she approached the first painting, the guide vibrated slightly—a prompt that additional content was available. Holding up the guide, she saw an **overlay** appear on the screen, revealing a time-lapse animation of the artist creating the piece. A small **audio clip** played, explaining the artist’s thought process and influences. Maria found this fascinating; it was as if the artwork was coming to life in front of her.  ]

[As she continued her tour, Maria **bookmarked** her favorite pieces, leaving notes about what she found intriguing. The system, recognizing her engagement, suggested another exhibit nearby featuring similar themes. Midway through her visit, she received a pop-up asking if she’d like a **short quiz** on the artworks she had explored, offering an interactive way to reflect on what she had learned.  ]

## Scenario 1-1: Ana wants to do a 10-minute workout at home and invites her friends to join her for a virtual session.

In the evening, while in her apartment, Ana decides to do a 10-minute workout. She opens the fitness app on her phone and in the **"Workouts"** section, she **selects a workout** that she likes and requires no equipment.

Then, Ana decides to **invite her friends to a joint workout**. In the **"Messages"** section, she finds her friends and writes them a message suggesting they train together.

After her friends confirm their participation, Ana **starts the selected workout, inviting her friends to join**. The workout begins once all participants have confirmed their readiness.

During the workout, Ana and her friends **follow the instructions on the screen**. Each participant sees the workout video and can **communicate via voice chat** to maintain communication and motivation during the session.

After the workout is completed, Ana **ends the session**.

## Scenario 2-1: Rafael wants to do one of his favorite workouts (EXAMPLE, POSSIBLY FINAL)

When the workday finishes Rafael wishes to do a chest workout, having already **marked as one favorite workout** in his app. The Rafael proceeds with opening the app, and **selecting the "workouts" panel**, where there are displayed all the workouts available in the app. In this panel, he goes to the area of **favorites workouts** and selects the chest workout. Therefore appears **information about the workout** and **selects the option to start the workout**.  

After the workout, he **can see the overall stats**, showing him the time of the workout and the calories burned. 

He can see all his stats **in the panel "stats"**.

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

**R4 -** When atributting a workout to another user, the option to create a new workout should be given, alongside the option to select one that has already been made;

**R5 -** 

**R6 -** 


## C.2. Non-functional requirements

**R1 -** Downloading a new workout should not take more than 3 seconds;

**R2 -** The most commonly utilised options, such as accessing created workouts and checking messages, should be more easily visible, and more readily available;

**R3 -** A user should receive a message or any other notification from another user in less than 3 seconds;

**R4 -** 

**R5 -** 

**R6 -** 


---
[Back to main Logbook Page](hci_logbook.md)
