# Task-Manager-Web-App

The application is a collaborative task management system built using Django, featuring the following core functionalities:

1. **User Authentication and Authorization:** Users can create accounts, log in securely, and manage their profiles within the system.

2. **Team Formation:** Users have the ability to create teams and invite other users to join their teams, facilitating collaboration among team members.

3. **Task Management:** Each user can create tasks, assign them to team members, and set due dates to ensure timely completion.

4. **Dashboard:** The application provides a centralized dashboard where users can view and manage tasks assigned to them, as well as tasks assigned to their teams.

To enhance the system further, additional features can be implemented:

1. **Task Search and Filtering:** Users can search, order, and filter tasks based on various criteria such as name, completion status, priority, due date ranges, assigned developer, or team/project.

2. **Priority System:** A priority system is introduced, allowing users to assign priority levels to tasks and filter them accordingly. Automated reminders are provided for high-priority tasks nearing their due dates.

3. **Task Dependencies:** Users can establish dependencies between tasks, enabling the application to adjust task timelines based on these dependencies.

4. **Notification System:** A notification system alerts users about task assignments and upcoming due dates, ensuring timely communication and task management.

5. **Gamification Elements:** To motivate users, gamification elements such as achievement badges, leaderboards, or a points system based on task completion can be introduced, fostering engagement and productivity.




# Group Project - Team Lynx

## Team members
The members of the team are:
- Adil Kassam
- Hasan Issa
- Lewis Kai Ho Wong
- Fardeen Idrus
- Bruno Miguel Fonseca Cavaca

## Project structure
The project is called `task_manager`.  It currently consists of a single app `tasks`.

## Deployed version of the application
The deployed version of the application can be found at [https://fardeenidrus.pythonanywhere.com/].

![image](https://github.com/Adil-Kassam/Task-Manager-Web-App/assets/76568714/d460df82-982e-4670-8c48-3cbe2968f28d)


## Installation instructions
To install the software and use it in your local development environment, you must first set up and activate a local development environment.  From the root of the project:

```
$ virtualenv venv
$ source venv/bin/activate
```

Install all required packages:

```
$ pip3 install -r requirements.txt
```

Migrate the database:

```
$ python3 manage.py migrate
```

Seed the development database with:

```
$ python3 manage.py seed
```

Run all tests with:
```
$ python3 manage.py test
```



## Sources
The packages used by this application are specified in `requirements.txt`




