# User stories

### Context:
A visitor is someone that does not have an account yet.
A member has an account but is not logged in
An user has an account and is logged in
A teacher is an user who is a teacher
A student is an user who is a student

## Auth

Feature: Login
As a: member
I want to: login using my email and password
So I can: access the rest of the app
Feature validated if: I can access the rest of the app

Feature: Registration
As a: visitor
I want to: register using my email, password, and fullname
So I can: login
Feature validated if: I can login with the same credentials

Feature: Logout
As a: user
I want to: Logout
So I can: log with another account
Feature validated if: I cannot access the rest of the app

Feature: Reset password
As a: member
I want to: reset my password
So I can: log back in
Feature validated if: I receive an email with a link to reset my password, and I can login using said password

Feature: Delete account
As a: user
I want to: delete my account
Feature validated if: I can no longer login using my old credentials

## Calendar

Feature: View all events for N period of time
As a: user
I want to: view all events scheduled in my calendar for this week
So I can: organize my planning this week
Feature validated if: I can see the events

Feature: Create a new event for myself
As a: user
I want to: create a new event for myself
So: I will not forgot about it
Feature validated if: I can create an event and I can see it 

Feature: Create a new event for my student
As a: teacher
I want to: create a new event for one of my student
So I can: meet with my student while he is available
Feature validated if: when creating a new event, I can choose a student to assign this event to, and they can see the event in their calendar

## Tasks

Feature: Create a new task for myself
As a: user
I want to: create a new task for myself
So: I will not forgot about it
Feature validated if: I can create a task and I can see it 

Feature: Create a new task for my student
As a: teacher
I want to: create a new task for one of my student
So I can: assign my student some work to do for next session
Feature validated if: when creating a task, I can choose a student to assign this task to, and they can see the task in their dashboard

## Chat

Feature: View my chats
As a: user
I want to: view all my open discussions
So I can: choose one and talk with my interlocutor
Feature validated if: I can click on a chat and see the previous messages exchanged

Feature: Send a message
As a: user
I want to: send a message to someone else
So I can: Discuss with them about my studies
Feature validated if: I can send a message to someone and they receive a notification and can read it

## Dashboard

Feature: View tasks summary
As a: user
I want to: see all the tasks that are assigned to me
So I can: organize myself to finish them
Feature validated if: I can see all the tasks assigned to me that are not marked as done

Feature: View events summary
As a: user
I want to: see all the events that I am participating to
So I: will not forget about them and be present on time
Feature validated if: I can see all the events that I am participating to and that did not happen yet
