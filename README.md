# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 13/10/2025
# Register no.: 212222060249
# Aim: 
To develop a prompt-based application using Lovable AI - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

## AI Tools Required: 
Building a sophisticated prompt-based AI assistant like Asha involves several interconnected AI technologies, primarily from the field of Natural Language Processing (NLP). Here are the essential tools and components:


# Explanation: 
**Prompt:** 
Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time.

## Procedure for Designing a Prompt-Based Personal Productivity Assistant

1.  **Define Requirements:** Establish Asha's core features (Task Manager, Scheduler, Wellness, Queries), user profile (preferences), tone, and interaction rules.
2.  **Construct LLM Prompts:** Create initial role-setting prompts for Asha's persona, then task-specific action prompts to guide the LLM's understanding and response generation.
3.  **Simulate Interaction:** Implement a system to send user input to the LLM (with prompts) and display its responses, iteratively testing with varied complexity of user queries.
4.  **Refine Responses:** Analyze LLM outputs against requirements for accuracy and tone, then adjust internal prompts to improve performance.
5.  **Evaluate Performance Metrics:** Define and track key metrics such as intent recognition accuracy, entity extraction precision, and user satisfaction (e.g., via surveys or explicit feedback).
6.  **Iterative Development & Deployment:** Continuously cycle through steps 2-5, refining the prompt structure and potentially fine-tuning the underlying LLM, leading to deployment upon meeting performance benchmarks.
7.  **Integrate Memory (Optional):** Store user preferences and interaction history to dynamically inform future LLM prompts for personalized responses.

## Prompt:
Create a personalized daily schedule for me, Soundariya, that I can follow every day. I’m a student who wants to balance study time, project work, exercise, meals, and relaxation. Include time for morning routine, focused study blocks, short breaks, meals, evening relaxation, and sufficient sleep. Make it productive but not overwhelming — something realistic to follow daily.

## Smart Scheduler

Schedule reminders contextually.

Detect conflicting or overlapping events.

Suggest free slots for new activities.

<img width="1159" height="676" alt="image" src="https://github.com/user-attachments/assets/d913372d-4c3b-4bd7-8135-3346b4fb40da" />
<img width="1082" height="399" alt="image" src="https://github.com/user-attachments/assets/c71cbda8-379f-4f79-a037-8674926d4470" />


## Daily Task Manager

Add and manage tasks using natural language.

Categorize tasks by priority and deadline.

Provide summaries and track completion status.

## Daily Task Manager Design
## 1. Aim

To create a Daily Task Manager that allows a user to:

Add and manage tasks using natural language.

Categorize tasks by priority, deadline, and type.

Track completion status and generate summaries.

Support a productive, organized, and balanced daily schedule.

## 2. Features
Feature	Description
Task Creation	Add tasks by typing natural language (e.g., “Finish ECE assignment by 5 PM, high priority”).
Task Categorization	Categorize tasks into priority levels (High, Medium, Low) and types (Study, Work, Personal).
Deadlines / Scheduling	Assign due dates and times to tasks; optionally integrate with a daily timetable.
Completion Tracking	Mark tasks as complete; automatically track progress and generate summaries.
Reminders / Notifications	Optional reminders for tasks with deadlines.
Daily / Weekly Summary	Generate summaries of completed, pending, and upcoming tasks.
Search & Filter	Filter tasks by priority, category, or deadline for quick management.
## 3. Workflow / How It Works

Input Task: User types a task in natural language.

Example: “Add ‘Study SQL for 1 hour’ tomorrow at 7 PM, high priority.”

Task Parsing: The system interprets the input:

Action: Add Task

Task Name: Study SQL

Time / Deadline: Tomorrow at 7 PM

Priority: High

Category: Study

Task Storage: The task is stored in a database or list with metadata.

Task Display: Tasks are displayed in a table or calendar view, sorted by priority or deadline.

Completion & Updates: User marks tasks as complete or edits them.

Summary Generation: At the end of the day, the system generates a daily report:

Completed tasks

Pending tasks

Upcoming deadlines

Total time spent per category

## 4. Example Interaction (Prompt-based)
Adding Tasks

User:

“Add ‘Finish ECE assignment’ by today at 5 PM, high priority.”

System (Asha-like response):

“Task ‘Finish ECE assignment’ has been added with high priority, due today at 5 PM.”



## Wellness Companion

Share personalized wellness tips (hydration, posture, meditation).

Suggest screen-time breaks or stretching exercises.

Adapt tips based on user behavior.

<img width="979" height="681" alt="image" src="https://github.com/user-attachments/assets/dc269fa5-60a2-4169-8ac8-56d13a57bfdc" />


## General Query Responder

**User Input (Soundariya):** "Tell me about the basics of front-end web development."

**Asha’s Interpretation:**
*   **Action:** Answer Academic/General Query
*   **Query Topic:** Front-end web development basics (highly relevant to Soundariya's IT interests!)

**Asha’s Output:**
"Oh, that's a brilliant question, Soundariya, especially with your HTML & CSS practice! Front-end web development is all about creating the part of a website that users actually see and interact with.

The three main pillars are:
1.  **HTML (HyperText Markup Language):** This is the **structure** of a webpage, like the skeleton. It defines headings, paragraphs, images, links, etc.
2.  **CSS (Cascading Style Sheets):** This is the **styling** of a webpage, making it look pretty! It controls colors, fonts, layout, and responsiveness for different devices.
3.  **JavaScript:** This adds **interactivity** to a webpage. Think dynamic content, animations, form validations, and more complex user experiences.



## Outcome:

A personalized daily schedule was designed for Soundariya, balancing college hours, self-study, skill development, project work, and personal care.

A Daily Task Manager framework was created to allow task addition, categorization by priority and deadline, and tracking of completion using natural language input.

A Wellness Companion module was developed to provide personalized wellness tips, hydration reminders, posture checks, meditation prompts, and screen-time breaks, adapted to daily activities.

A General Query Responder module was designed to provide instant academic explanations, technical guidance, and general knowledge or news updates, supporting real-time learning.

## Conclusion:
The integrated system demonstrates that prompt-based applications can be effectively used to organize daily tasks, manage time, and maintain wellness for students.

By combining task management, personalized schedules, wellness guidance, and query resolution, the system provides a comprehensive assistant tailored to Soundariya’s academic and personal needs.

The structured approach ensures that productivity is maximized while maintaining health, balance, and consistent learning.

This framework can be expanded or customized further for other students or professionals to enhance efficiency and well-being in their daily routines.



# Result: 
The Daily Task Manager enables efficient task management and progress tracking, ensuring tasks are completed in a structured and timely manner.

The Wellness Companion helps maintain physical and mental well-being, preventing burnout during long study or project sessions.

The General Query Responder supports instant clarification of academic concepts and access to current information, making study and project work more effective.

Overall, the combination of these modules leads to a holistic productivity and wellness system, promoting discipline, focus, and balanced daily routines.
