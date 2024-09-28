# Infinite ID
Infinite ID is the original relationship journaling program series created in 2017. It features macro statistics about the friends you associate with, how your social group is changing, and more.

Development of this program ended in the early stages because at the time, I was questioning the viability of this type of journaling.

The latest in the relationship journaling lineage of programs is here: [Constantine-INGRID-Polariscope](https://github.com/CKhamis/Constantine-INGRID-Polariscope).

## Friend View
You are able to view basic information about each person you entered into the data file. Some of this information is a note, grade met, and age met.

## CSV Based Data
This program uses D3.JS to parse and analyze data given to it. This is because at the time, I did not have much experience working with databases. Additionally, I had been keeping a Constantine [IN]GRID like Excel document that I originally used to keep track of friends I invited to my parties.

This is the very first of all my projects to handle data storage in a significant way.

## Component-Based UI
Like [Robotics-Website-Milestone-3](https://github.com/CKhamis/Robotics-Website-Milestone-3), this uses my basic implementation of a component based user interface. Various components were stored as separate HTML files and added into pages using iframe elements to centralize and unify the codebase.

## How to Run
In order for this program to run, you must provide a data.csv file inside the /Data directory. This file must contain specific table headers in order for the information to be processed correctly. Additionally, you need to run this as a web server and not as a collection of HTML files. Recommended to use Adobe Dreamweaver.