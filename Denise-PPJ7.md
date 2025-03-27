# PPJ 7: 
Denise Payumo PPJ Week 8

**Tasks:**

- Hold Spring Break Meeting on 3/19 - 3 Hrs
- Edit Team Contract - 1 hr
- Setup Github Issues - 1 hr
- Implement Pause menu - 3 hrs
- Implement and edit Paulo's Sound Dictionary - 2 hrs

**Total Hours: 10 hrs**

**Entry** 

I had a very busy last two weeks--including spring break-- working on projects for other classes. I haven't been able to allocate as much time into actively working on the game itself, but I took time over the break to talk to everyone and let them know about the conversation Thomas and I had during office hours. I told them how we felt we needed to redistribute the work in the team contract, remove some of the load from Thomas' shoulders, as well as migrate to Github Issues for tracking progress and tasks. I spent some time to get used to and move some of our biggest tasks to the platform and edit the team contract with Thomas.


**Milestone Description**

![image](https://github.com/user-attachments/assets/d5105ba9-1a23-4f18-b3ba-d0294212ed34)


In terms of milestones, after the conversation I had during office hours I felt it wasn't worth redoing the design for the current main menu and win screen ui. I spent more time figuring out our next priorities and finding a better way to organize our tasks (github issues). I still managed to create the pause menu and gave it some functionality, (esc to open, close, and back out from the options/controls menu). I also helped out Paulo by looking over and making some tweaks to the script he made for the AudioDictionary and AudioManager. I brought those changes to my branch and started implementing it into our game scene, and I was able to refine the heartbeat sound and make it play smoother since my previous bandaid fix would abruptly cut it off.


**Documentation**


![image](https://github.com/user-attachments/assets/8a14a8e3-7d49-462a-b53c-679b1309b710)
![image](https://github.com/user-attachments/assets/b732aa18-159c-470e-8ed5-7a1015460cc5)


(Above) A screenshot of the pause menu I implemented in game and the basic info I put in the Controls section.

![image](https://github.com/user-attachments/assets/b10641dc-dd73-49f1-87a0-fd25dab4933c)![image](https://github.com/user-attachments/assets/fa7efcc7-cc03-4df0-b16d-b3d95a2de5eb)



(Above) The implementation of the AudioDictionary and AudioManager i put on my branch.

We held a meeting on 3/26/25 to do some work together, discuss the response to our proposed contract revisions, and talk about what we're working on/going to work on. Paulo created the AudioDictionary scriptable object and did a great job. He said I could look over it and make any changes I wanted so I took it over to my branch and edited it to be able to play both 2d audio and 3d audio. I also divided it into two separate scripts called AudioDictionary.cs and AudioManager.cs and put it into the scene to see if I could get it to work which it did :D I was able to further fix the heartbeat audio because it was pretty scuffed with my bandaid fix for the alpha. I hope to be able to utilize these scripts and have an easier time adding the implementing the sound effects needed for better feedback and a better player experience.


**Looking ahead:**
- I still haven't managed to put ALL our upcoming tasks onto github issues nor have I been able to divid them into smaller manageable tasks, so I plan to continue doing that.
- Gonna be investing more time into this class now that my other projects aren't so in the way.
- I still want to add more audio and visuals for feedback to refine the heartbeat mechanic, and I told Thomas that I'm interested in taking on part of the other 2 hallucination events and I am gonna try to see what I can get done for those before the beta.
