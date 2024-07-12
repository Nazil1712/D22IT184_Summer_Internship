# Summer Internship 2024 - D22IT184

Welcome to my Summer Internship 2024 repository! This repository contains all the work and projects I completed during my internship at **ScaleCapacity**.

<center>
<img src="./logo.png" style="margin-top:15px; margin-bottom:15px;" width="800px"/>
</center>


## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [Week1](#week-1)
- [Week2](#week-2)
- [Week3](#week-3)
- [Week4](#week-4)


## Introduction

This repository documents the progress and outcomes of my summer internship in 2024 at [ScaleCapacity](https://www.scalecapacity.com/). My roll number is **D22IT184**. Throughout this internship, I engaged in various tasks to enhance my skills and contribute to meaningful work.

## Projects

### Project 1: KEMS ( KnightScope Emergency Management System )
- **Objective:** To manage all emergency devices and their functionalities.
- **Technologies Used:** HTML, CSS, JS, PostgreSQL, jQuery.
- **Status:** Currently in progress, with ongoing tasks and updates being handled as instructed by my senior colleague.
- **Description:** The KEMS (Knight Scope Emergency System) project at ScaleCapacity focuses on enhancing emergency response through the deployment of callboxes worldwide. A callbox is a device used by individuals to report accidents or emergencies, ensuring swift assistance. The project involves mapping callbox locations, monitoring their status, integrating cameras, and generating comprehensive reports, such as monthly active callbox reports and system availability history. An admin panel is also developed to manage these callboxes efficiently. My role includes completing tasks and implementing changes as directed by my senior colleague.

<center>
<img src="./kemsLogo.png" style="margin-top:15px; margin-bottom:15px; text-align:center;" />
</center>


## Technologies Used

- Programming Languages:  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white), 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white), 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
- Frameworks: ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=flat&logo=bootstrap&logoColor=white), ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=flat&logo=jquery&logoColor=white), ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat&logo=Sequelize&logoColor=white)
- Tools:  <img src="./vscode.png" width="15px"/> VScode, ![GIT](https://img.shields.io/badge/Git-fc6d26?style=flat&logo=git&logoColor=white)
- Platforms: ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white), ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)


## Start Of Internship 

### Week-1
- **Induction :** 
    - My internship at ScaleCapacity began with an induction meeting where Maulik Sir provided a brief overview of the company. 
    - During this meeting, I, along with other selected students, introduced ourselves. Maulik Sir also shared essential information and guidelines necessary for our successful integration into the company. 
    - This initial session set the foundation for the work and collaboration that would follow in the subsequent weeks.


- **Setup & Installation :** 
    - Following the induction, I received an AWS account from the company and logged in. I then cloned the project repository from AWS. To set up my development environment, I installed 
    - XAMPP, <img src="./xampp.png" width="55px"/>
    - PostgreSQL  ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
    - pgAdmin. 

    - This setup was crucial for managing and interacting with the database and running the local development server.



### Week-2
- **Database Import and running project :**
    - In the second week, I focused on setting up the project environment and resolving initial issues. 
    - I imported the project database and learned how to run the project locally using the 
    command 
    ```bash
     sls offline start --stage local
    ```
    - This involved understanding and working with Serverless (sls). During this process, I encountered and solved various errors and issues related to the Serverless framework, which helped me gain practical troubleshooting experience.


    -  I have set up specific branches to facilitate organized development and feature implementation based on instructions from my senior colleague. Here is an overview of the branch setup:


    1. To check current branch
    ```bash
        git branch
    ```

    2. To create a new branch
    ```bash
        git checkout -b <branch-name>
    ```

    3. To navigate to respective branch
    ```bash
        git checkout <branch-name>
    ```

- **Task: Adding and Managing a New Attribute in the Database**

    - **Description:** 
        - Learned that How we can add  a new column (attribute) to the database in Admin > Region section. This involved updating the database schema, providing options to add and edit the new attribute, and ensuring it is displayed in the user interface.

    - **Action Taken:**
        - **Database Schema Update:**
        Added a new column (attribute) to the existing database table that stores information of added tuple.

        - **Adding New Attribute:**
        Updated the admin interface to include an option for adding the new attribute when creating a new region.

        - **Displaying the Attribute:**
        Updated the UI to display the newly added attribute in the Admin > Region section.
        Verified that the new attribute is correctly shown in the region list and details view.

### Week-3

- **Task: Enhancing Actions and Functionality in Admin > Callbox**

    - **Description:** 
        - Modified the admin interface for managing callboxes to ensure consistent functionality across active, inactive, and deleted filters. 
        - Specifically, added actions such as edit and see live location to the deleted filter and implemented logic to hide the save button when editing a deleted callbox using jQuery.

    - **Actions Taken:**

        - **Updated Filters:** Enhanced the deleted filter to include actions like edit and see live location, previously available only in the active filter.
        - **jQuery Implementation:** Utilized jQuery to dynamically hide the save button when editing a callbox marked as deleted, ensuring consistent user experience and preventing unintended changes.


- **Task:  Implementing Select2 for Region Selection**

    - **Description:** 
        - Integrated Select2 functionality across project pages where region selection is required to filter callboxes. 
        - Select2 enhances user experience by providing a searchable dropdown for selecting regions, simplifying the process of filtering callboxes based on regions.

    - **Actions Taken:**

        - **Learning Select2:** Studied and understood the functionality of Select2 to facilitate region selection with enhanced search capabilities within dropdowns.
        - **Implementation:** Implemented Select2 across project pages to replace standard dropdowns with searchable ones for region selection. This enhancement aimed to improve usability and efficiency in filtering callboxes by regions.


### Week-4

- **Task: Implementing Select2 for ANI Selection**

    - **Description:**
        -  Integrated Select2 functionality to enhance ANI (Unique ID for Call Box) selection across the project. When a specific region is selected, all ANIs associated with call boxes in that region are displayed in the Select2 dropdown. 
        - This allows users to search for ANIs or select them from the dropdown menu, streamlining the selection process.

    - **Actions Taken:**

        - **Select2 Implementation:** Implemented Select2 for a searchable interface for ANI selection.
        - **User Interface Enhancement:** Enhanced user interaction by providing a user-friendly method to search and select ANIs, thereby improving overall usability and efficiency.


- **Task: Calculating Averages for Voice Calls and Call Time**

    **1. Average Voice Calls Per Day:**

    - Formula: 
    ```
    Avg Voice Call per day = Total Call Voice / Number of days in month
    ```
    - This calculation provides the average number of voice calls made each day.

    **2. Average Voice Call Time Per Day:**
    - Formula: 
    ```
    Avg Voice Call Time per day = Total Call Time in sec / Number of days in month
    ```
    - Steps:
    1. Convert call time period into seconds.
    2. Apply the formula to get the average call time per day in seconds.
    3. Convert the result from seconds to minutes for easier interpretation.


    **3. Average Voice Calls Per Call Box:**
    - Formula: 
    ```
    Avg Voice Call Per Call Box = Total Call Voice / Total Call Boxes
    ```
    - This calculation provides the average number of voice calls per call box.


    **4. Average Voice Call Time Per Call Box:**
    - Formula: 
    ```
    Avg Voice Call Time per Call Box = Total Call Time in seconds / Total Call Boxes
    ```
    - This calculation provides the average call time per call box in seconds.
