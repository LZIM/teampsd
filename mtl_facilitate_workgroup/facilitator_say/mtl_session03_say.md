---
title: "MTL Session 3 - Facilitator Say"
author: "Team PSD"
date: "September 2018"
output: 
  github_document: default
  html_document: default
  pdf_document: default
  word_document: default
  ioslides_presentation: default
  slidy_presentation: default
  powerpoint_presentation: default
---

<img src = "https://github.com/lzim/teampsd/blob/master/resources/logos/mtl_live_sq_sm.png"
     height = "175" width = "290">  

# [MTL Live Session 03](https://github.com/lzim/teampsd/blob/master/mtl_facilitate_workgroup/mtl_live_guide/mtl_live_session03_see.Rmd "MTL Live Session 03")

# Today we're modeling to learn how to produce team data for simulation.  

Hello! I'm __________ and I'm __________ [Co-facilitators introduce themselves]. Today we're modeling to learn how to produce team data for simulation.

### As you see in the Done/Do table of the Learner See Guide at mtl.how:

## Done and Do (15 minutes)
<!-- Do/Done Tables -->
| <img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/done.png" height = "80" width = "80"> **Done** | <img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/do.png" height = "90" width = "90"> **Do** |
| --- | --- | 
| [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) We reviewed the HF, Diag, Enc and SP tabs in Team Data to find a patient and a team trend. We logged in to mtl.how/data and looked at the two team folders: data UI and team data. | [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_data_sm.png" height = "75" width = "110">](http://mtl.how/data) We will produce team data for the _MTL_ simulation user-interface (sim UI)| 

### After this session you will be able to:

<!-- Learning Objectives Icon --> 
<img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/learning_objectives.png" height = "90" width = "90" style ="display: inline-block"/> 

## Learning Objectives

1. Describe your team trends over the last two years based on the estimates in the team data table.
2. Test out your understanding of how the team data is estimated through review of the descriptions and definitions.
3. Apply your clinical expertise to consider the team trends in the data UI and team data table to identify team priorities for learning.

## Let's get started!

As the graphic illustrates, we use the data UI to look back at team trends over the past two years - *what is*; and we will use the sim UI to look at team trends 2 years into the future to answer *what if* questions about different decisions the team could make.

## In-session Exercise (30 minutes): Team data for simulation
<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/illustrations/data_ui_sim_ui.png">

### Navigate to the data UI at mtl.how/data. 
Remember that this is on the VA's secure SharePoint site, so it works best with Internet Explorer.

You'll log in with your VA credentials and you should have all the same permissions here as you do in general for your role in the VA.

Navigate to your facility as we did last time, or when you've done it a few times, it will automatically go to the facility that you're working with.

Scroll down to the team folder. You will (probably) have just one file there, called "data UI". We will click on that folder and open the Excel file. Then we will use the second "Get Team Data" button to create a second data file for use by the sim UI.

### Clicking the "Get Team Data Table for Sim UI" button produces a table of descriptive team data.

a. This is a different table from the one you generated last time by selecting the clinics that make up your team and then clicking "Get *Patient Level* Data." 

b. Data in this file are means, medians and percentages of key variables likely to influence the team's priorities for learning from *Modeling to Learn*. Later on, we will upload this file to the sim UI so that it can *read in* these data, or parameters.

c. There are team data produced for each module of *Modeling to Learn*, each stored in its own tab:
  + Care Coordination (CC) - tab title *CCParams*
  + Medication Management (MM) - tab title *MMParams*
  + Psychotherapy (PSY) - tab title *PSYParams*
  + Aggregate team services (AGG) - tab title *AggParams*
  + Measurement-based stepped care for suicide prevention (SP) - tab title *SPParams*

### 1. Let's select a module for review - to show what data are used to tailor each *MTL* module to your team.
[Choose a module]

   - *CCParams*: Key variables of interest in CC may include median engagement in weeks, appointment supply in appointments per week, return visit interval in weeks, starting rate in patients per week, and new patient wait times.

   - *MMParams*: Key variables of interest in MM may include median engagement in weeks, appointment supply in appointments per week, return visit interval in weeks, starting rate in patients per week, and appointment slots with an X waiver as a percentage of the total and Slots Allocation percent for those with and without an X waiver.

   - *PSYParams*: Key variables that can be explored in PSY include median engagement duration and engagement after 3 months measured in weeks, appointment supply by service type (AUD, DEP, OUD, PTSD) within 3 months, and return visit interval after 3 months in weeks.

   - *AggParams*: Key variables in AGG are median engagement in weeks, appointment supply by service type, return visit interval in weeks, new patient start rate (mean), and service proportions from team data.

   - *SPParams*: In Suicide Prevention, key variables of interest may include high risk flag rates, engagement times before ending treatment in a specific setting, engagement time before stepping down or up between care settings, wait times, and the ratio of high to low symptom patients in each setting.

Check out the different modules that are highlighted in the team data on the screen. As we review, we will use the mouse to highlight key team data variables.

a. Find a variable that is important to your team. Look at how the variable is estimated in the table. Notice the units.

b. Where can you find even more detailed information about your team data? In each of these Params tabs, you can find more detailed information about your team data. 

c. For example, check out the two columns to the right of the numerical data [show with mouse]. Let’s explore these two columns.
	This column [highlight column] gives the description or definition of the variable. 
	This column [highlight column] contains additional details about how individual patient data are extracted and used to calculate your team’s historical trends.

### 2. Let’s select a second module for review.

a. Check out the last 2 columns, to the right of the numerical data. 
	This column [highlight column] gives the description or definition of the variable. 
	This column [highlight column] contains additional details about how individual patient data are extracted and used to calculate your team’s historical trends.

b. Find a variable that is important to your team. How is it estimated in this table? What are its units?

c. Where can you find even more detailed information about your team data?
    + You can click on the “DataNotes” tab for a breakdown of how the patient cohort is defined, which CPT codes are used to define each service, and the patient engagement patterns (for the Psychotherapy module).

### 3. Are there any team data table values you would like to explore in the team data UI?

a. Which ones? Open the data UI to examine your question.

### 4. Do you see any team data values that differ a lot from what you would expect?

a. If so, what is it surprising? 

b. Does the estimation definition help you to interpret the variable value?  

### 5. Do you see any team data values that confirm your thoughts about high priority team needs?

a. What are you noticing? 

b. In what ways does the team data fit with your day-to-day experience?
  
### That's it for _Modeling to learn_ how to produce team data for simulation. Next is our Done/Do review.

## Done and Do (15 minutes)
<!-- Do/Done Tables -->
| <img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/done.png" height = "80" width = "80"> **Done** | <img src = "https://github.com/lzim/teampsd/blob/master/resources/icons/do.png" height = "90" width = "90"> **Do** |
| --- | --- | 
| [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_sim.png" height = "75" width = "110">](http://mtl.how/sim) We produced Team Data for the sim UI. |  [<img src = "https://raw.githubusercontent.com/lzim/teampsd/master/resources/logos/mtl_how_menu.png" height = "75" width = "110">](http://mtl.how/menu) Find something in the team data table and complete the mtl.how/menu. | 

### DO demo

1. We encourage you to look around in the team data table before next time. Test whether you can find a piece of data you decide to look for. Just take a minute, if you can, to become familiar with the format and content of the data table. Remember, you can click through the Params tabs, 1 for each module, to dig into the details of how each parameter is calculated in the text columns to the right of the numerical data.

2. The next thing we ask is that each member of the team fill out a short form that you'll find at mtl.how/menu. It will take about 12 minutes.

3. We will aggregate the responses and consider them together in the next session to help the team choose which *MTL* module we'll use for the next several sessions of *Modeling to Learn*.


## Until next time, thank you for *Modeling to Learn*!
