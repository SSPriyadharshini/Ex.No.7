# Ex no.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 14/3/26
# Register no: 212223040156
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: ChatGPT


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# Procedure for Designing a Personal Productivity Assistant
## 1. Define Core Requirements
### The assistant should provide:
* Daily Task Manager: Add, delete, prioritize, and summarize tasks.
* Smart Scheduler: Organize time, avoid conflicts, and optimize schedules.
* Wellness Tips Generator: Give health and productivity tips tailored to user habits.
* General Knowledge Queries: Answer quick factual questions.
* Adaptability: Learn user preferences over time (memory simulation).

## 2. Identify & Construct Prompts for Each Task
### (a) Daily Task Manager
#### Prompt Example:
````
You are my productivity assistant. I will tell you tasks in natural language. Convert them into a structured to-do list with priority, deadline, and reminders.
````
#### User Input:
"Remind me to call mom at 6 PM and finish my project report by tomorrow."

#### AI Output:
* Call mom → Reminder at 6 PM today. (Priority: Medium)
* Finish project report → Deadline tomorrow 11:59 PM. (Priority: High)
  
### (b) Smart Scheduler
#### Prompt Example:
````
Here are my current tasks and appointments. Organize them into a conflict-free schedule. Suggest free time slots for relaxation or new tasks.
````
#### User Input:
* Meeting: 10–11 AM
* Gym: 7–8 PM
* Task: Finish report (2 hours, due tomorrow)

#### AI Output:
* 10:00–11:00 → Team meeting
* 2:00–4:00 → Work on report (high priority)
* 7:00–8:00 → Gym
* 5:00–5:30 → Free slot (suggest: coffee break or short walk)

### (c) Wellness Tips Generator
#### Prompt Example:
````
Suggest a wellness tip for today, considering I usually skip breaks and spend long hours at my desk.
````
#### AI Output:
Wellness Tip: Set a timer every 90 minutes to stand, stretch, and hydrate. A short walk can improve focus and reduce eye strain.

### (d) General Queries
#### Prompt Example:
````
Answer my quick questions concisely, like a helpful personal assistant.
````
#### User Input:
"What’s the weather in Chennai today?"

#### AI Output:
32°C, sunny with light humidity. A good day to stay hydrated.

### (e) Preference Adaptation (Optional Memory Simulation)
#### Prompt Example:
````
Remember my preferences: I prefer evening workouts and dislike coffee suggestions. Adapt future tips accordingly.
````
#### AI Output (Next Time):
“Wellness Tip: Since you prefer evenings, try a light 15-min stretch in the morning instead of coffee for energy.”

## 3. Simulate Natural Interaction (CLI Example)
````
User: Add a task – buy groceries at 5 PM.
Assistant: ✅ Task added – Reminder at 5 PM today.

User: What’s my schedule today?
Assistant: You have groceries at 5 PM. Free slots at 2–4 PM and 7–9 PM.

User: Suggest a wellness tip.
Assistant: Remember to drink 8 glasses of water today. Place a bottle near your desk.
````

## 4. Collect Feedback & Adapt Responses
* User can say: “I don’t want hydration reminders, focus on posture tips instead.”
* Assistant updates its response style accordingly.
### Expected Output (Like a Demo Response)
#### Personal Productivity Assistant Features:

#### Daily Task Manager
* Accepts tasks via natural language (e.g., “Remind me to call mom at 6 PM”).
* Organizes tasks by priority and deadline.
* Provides daily summaries and pending items.
#### Smart Scheduler
* Schedules events and sets reminders using contextual understanding.
* Notifies user of overlapping appointments or free time slots.
#### Wellness Tips Generator
* Suggests daily wellness advice (hydration, exercise, screen-time breaks).
* Adapts suggestions based on past user preferences and responses.
#### General Query Handling
* Provides quick, concise answers for user questions.
#### Adaptability (Optional Memory)
* Learns from user input (e.g., prefers evening workouts, dislikes coffee tips).
* Refines reminders and suggestions over time.

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
* Understand how to tailor LLM prompts to real-life applications.
* Foster creativity by designing features suited to their personal or academic lives.
* Learn prompt engineering techniques for optimal interaction with AI tools.
* Experience the versatility and utility of generative AI in solving everyday problems.
