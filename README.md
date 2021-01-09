# WhatTodo



![logo](/assets/Logo/horizontal.png)

Life can feel overwhelming. But it doesn’t have to. 

A Simple To-do app design in flutter to keep track of your task on daily basis. You can add project, labels and due-date to your tasks


## Features

- Build on [**BLoC**](#bloc-diagram) Architecture Pattern
- Add [**Projects**](#project) by specifying a unique color to it
- Add [**Labels**](#labels) by specifying a unique color to it
- Add [**Task**](#task) by defining its priority
- [**Swipe**](#swipe-the-task) to delete or complete the task
- [**Sorting**](#sorting) Task
- Works offline using [**Sqflite**](https://github.com/tekartik/sqflite "Flutter Database") database

## BLoC Diagram
This diagram show case the dependencies to create a feature specific BLoCs.The HomeBloc is independent and used as communication channel between its child widgets.

![](https://i.imgur.com/byajGE7.png)

## Widget-BLoC Relationship
This diagram shows that how each widget uses BLoCs.

![](https://i.imgur.com/fHGTASw.png)

## Project
The app already has a preloaded **_Inbox_** project. You can add more projects by clicking add project button on SideDrawer. From material color list you can specify any single color to the project

![](https://i.imgur.com/f01IjGz.gif)

> You can assign only one project to a single task

## Labels
You can add multiple labels by clicking add Labels button on SideDrawer. From material color list you can specify any single color to the label

![](https://i.imgur.com/tZQgEwW.gif)

> You can assign multiple labels to a single task

## Task
You can add task with multiple attributes. You must assign a project to task if not than by default it will be added in _Inbox_ project.
Task can have zero or more to label assing to it

![](https://i.imgur.com/mNs0D3B.gif)

## Swipe the Task
You can delete a task by swiping left-to-right or your can mark task as completed by swiping right-to-left. You can also undo a completed task by clicking on options menu where  it shows the list of all completed tasks there you can swipe right-to-left to undo the completed task

![](https://i.imgur.com/yU0gP1t.gif)

## Sorting
You can sort your task with date i.e today and next 7 days and also acoording to project and labels

![](https://i.imgur.com/wzou22S.gif)


