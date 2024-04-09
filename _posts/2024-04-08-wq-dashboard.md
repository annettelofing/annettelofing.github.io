---
layout: post
title:  "Dashboard Report for Patient Scheduling Team Work Queues"
date:   2024-04-08 08:10:39 -0700
categories: [Excel, Health Data, Work Project, Dashboard, Project]
tags: [excel,work,project,portfolio,analytics,analysis,health,data,healthcare,exploritory,evaluation,insights,self-directed] #always lowercase for tag names
image: 
    path: /assets/images/wq-dashboard/WQ Dashboard Project.png"
    alt: Dashboard Report for Team Work Queues in Excel
--- 

I created an Excel Dashboard to report weekly workqueue numbers to our team and supervisor. 

## Overview: 
**Project:** Dashboard Report for Tracking Team Workqueue Numbers  
**Software:** Excel: Pivot Tables, Pivot Charts
**Skills:** Combining and Cleaning Data, Data Visualization with Excel 

### Problem: 
Our team was looking at raw data on a week-to-week basis, struggling to identify and comprehend how the numbers relate to each other across multiple tables in an excel sheet. 

### Solution: 
I created one dashboard that displays all of the workqueue information we have been tracking. On the dashboard I use a combination of pivot tables and pivot charts, to display the data in a way that is easy to navigate and interpret. 

## Why was this dashboard *desperately* needed? 

**The raw data in the previous excel spreadsheet was...**
- Difficult to interpret and digest into understandable comparisons 
- Difficult for the viewing user to gain actionable insights from the data
- Hard to see how the data has changed over time 
- - There were multiple tables and multiple sheets of data leading to eyes darting around to make sense of what the number was previously 

<p>
Additionally, our team leader would get asked periodically to explain where the team was at, and how we were doing with our numbers but there was no actionable insight we could easily gain from the previous spreadsheet. 
</p>


## The Old Data Tracking Spreadsheet 
### What was being used previously 

<img src="/assets/images/wq-dashboard/Old-DataReporting-WQ-Spreadsheet-01.png" alt="Old Data Reporting Work Sheet" class="">

<img src="/assets/images/wq-dashboard/Old-DataReporting-WQ-Spreadsheet-02.png" alt="Old Data Reporting Work Sheet" class="">

## Compared to the New Data Tracking Spreadsheet 

<img src="/assets/images/wq-dashboard/WQ-Dashboard-2-Iteration.png" alt="New Dashboard for Reporting Workqueue Numbers" class="">

This dashboard, in my humble opinion, is much easier to read, understand, and take insights away from. 

## The Methodology of Design 
### More information on why I chose this design layout

Using the **date reviewed** column on the left side, you can easily switch between the weeks looking at the most recent data, or the data that was reported 5 weeks ago. As we add more data into our table, the column will grow with future dates, so we can easily switch back and forth to examine the data.

<img src="/assets/images/wq-dashboard/01-WQ.png" alt="Step 1 in creating the dashboard" class="">


Since we read left to right, I started with the largest metrics we measure weekly, which is our **total number of appointment requests** in our active, canceled, and deferred work queues. 

<img src="/assets/images/wq-dashboard/02-WQ.png" alt="Step 2 in creating the dashboard" class="">

From there, I decided to show the **Medical Oncology (Med Onc) Appointments** next because everyone on our scheduling team schedules Med Onc Appointments, and our providers and their patients are central to our oncology center. 

<img src="/assets/images/wq-dashboard/03-WQ.png" alt="Step 3 in creating the dashboard" class="">

Next I chose to display **Infusion Numbers** because we have a lot of patients, both oncology and outside patients that receive treatment in our infusion center. 

<img src="/assets/images/wq-dashboard/04-WQ.png" alt="Step 4 in creating the dashboard" class="">

For our **Imaging Work Queue** - in our scheduling team, we only schedule Imaging (CT’s, MRI’s, Ultrasounds, Mammograms, etc.) for our patients, which is continuing to narrow the focus for the dashboard. 

<img src="/assets/images/wq-dashboard/05-WQ.png" alt="Step 5 in creating the dashboard" class="">

I chose to display a **Table of Misc. Appointments**, because we have a blood disorder clinic (BDC), two gynecologist oncologists, palliative care, and radiation oncology providers which the numbers for are standalone and are not easily compared to anything else. 

<img src="/assets/images/wq-dashboard/06-WQ.png" alt="Step 6 in creating the dashboard" class="">

## First Iteration

This was my first iteration of the project, except I had the lab and port picc care appointments in the Table of Misc. Appointments. 

<img src="/assets/images/wq-dashboard/WQ-Dashboard-1-Iteration.png" alt="Iteration 1 of Work Queue Dashboard" class="">

<p>
<i>Disclaimer: I did not get a screenshot of this, but it was exactly the same as below except for the lab and port/picc care appointment being in that misc. table </i>
</p>
<p>
Once I finished this stage of the project, I asked for feedback from my team leader Hallie and supervisor Vanessa, and Vanessa mentioned that she would like to see the lab and port/picc appointment requests with the infusion numbers. 
</p>

## Second Iteration 
### Improved existing dashboard with supervisor’s feedback

<img src="/assets/images/wq-dashboard/WQ-Dashboard-2-Iteration.png" alt="Iteration 2 of Work Queue Dashboard" class="">

<p>
We have a stand alone lab with its own appointments, along with our infusion center and since lab appointments <> (do not equal) infusion appointments, I decided to make Lab Appointments its own chart. 
</p>

<img src="/assets/images/wq-dashboard/07-WQ.png" alt="Step 7 in creating the dashboard" class="">

<p>
For those who have access to the dashboard spreadsheet, they can manipulate the filter on their computer and see how the data changes over time and across the different appointment types. 
</p> 

<img src="/assets/images/wq-dashboard/08-WQ.png" alt="Step 8 in creating the dashboard" class="">

<p>
I had also asked my team leader Hallie if she would be interested to see how the numbers changed over time. She said yes, and I made the <b>Appointments Over Time</b> line graph with filtered data from Number 8 - to the left of the line chart. 
</p>

<img src="/assets/images/wq-dashboard/09-WQ.png" alt="Step 9 in creating the dashboard" class="">

<p>
<i>Note: 4/10/24 is listed as 0 in this data chart because I have made the rows for this date, but I made this spreadsheet on 4/08/24 and at the time the data for 4/10/24 had not been entered. </i>
</p>

## Secure the Data 
### Hopefully nobody knows where the ctrl + alt + delete buttons are… 

<p>
While it’s not likely someone in our team would tamper with the data, or accidentally delete it… I went ahead and locked the data part of the spreadsheet from being edited from anyone except myself, my team leader, or my supervisor. 
</p>

<p> 
This makes sure that nobody is editing the data that doesn't need to be editing it. 
</p>

## Feedback That I Heard 
### For improving our data tracking and reporting with this dashboard 

- It’s so much easier for me to understand! 
- My brain understands and works much better this way (in pictures and charts) than with numbers in a table 
- I LOVE THIS! 

## Conclusion 
<p>
I believe this project was a huge success for our data reporting and understanding needs for our work queues that we manage as a team. 
</p>

<p>
My team leader and supervisor asked if they could start implementing it right away (even after just the first iteration). 
</p> 
