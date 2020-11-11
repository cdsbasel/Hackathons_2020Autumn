---
layout: page
title: Flying Less Visualization Hackathon

---

<a href="https://unibas.zoom.us/j/92667698354?pwd=Q095Rmk5UVJBc0V1Rk96SUVVWVMwQT09"><img src="https://dwulff.github.io/NLP_2020Autumn/assets/img/zoom.png"></a>

## Background
The University of Basel is committed to reducing academic business travel by plane by at least 30% in the next few years. The Sustainability office is responsible for coordinating and supporting faculties and other institutional bodies at the University of Basel to achieve this reduction. The hackathon is the result of a partnership between the Sustainability Office of the University of Basel and the Center for Cognitive and Decision Sciences (CDS) with the goal of generating insights from existing data about academic business travel to help make informed decisions about flying and/or raise awareness about academic business travel. For this purpose, the Sustainability Office has made available a set of anonymized data concerning the flights taken by staff and students of the University of Basel in the past years.  

## Learning Goals and Structure
The hackathon uses the principles of problem-based learning to train your skills in data analysis and visualization. The hackathon consists of two events. A first 1-hour planning session and a 4-hour hackathon event.

## Sessions  
#### Planning Session: November 10, 12:00-13:00
The goal of the planning session is to help you familiarize yourself with the dataset and define a set of potential questions and visualizations. We aim to identify at least 2 questions and respective data visualizations that can be implemented during the hackathon event.

#### Hackathon: November 11, 14:00-18:00
The hackathon will be dedicated to using R to prepare the 2 data visualizations identified in the planning session. Each team’s results will be shared in a short, timed presentation that showcases the 2 data visualizations and a conclusion (3 slides, 1 minute per slide). The hackathon schedule:
14:00 - Welcome and forming team (4 teams of 2-4 people)
14:15 - Team work
15:15 - Plenary: Troubleshooting and discussion
15:30 - BREAK
16:00 - Team work
17:00 - Presentations and Discussion
17:50 - Wrap-up

## Assignment
Your assignment is to function as a data analyst to identify a course of action, including developing a specific analysis plan and communication strategy using the data available. You are challenged to answer a number of questions, including: What type of questions can we answer about academic business travel at the University of Basel using the data set supplied by the Sustainability office? What data visualization techniques can be used to generate insights and for which audiences? How should such analyses be conducted, interpreted, and communicated?

## Data

<h4><a href="https://www.dropbox.com/sh/zs50cji9k5hk6a4/AADWV7-WvwV_p7NJm9xb7Xqoa?dl=0">Download Data & Materials</a></h4>

The dataset consists of information concerning about 20.000 flights paid by the University of Basel between 2017 and 2019. Each flight is described by a number of variables, including date information, departure and arrival airports, price, and an estimate of the CO2 emissions associated with each flight, among others. See table of variables below.

<style>
td {
  align: left;
}
</style>

<table cellspacing="0" cellpadding="0">
<tr>
  <td><b>Label</b></td>
  <td><b>Description</b></td>
</tr>
<tr>
  <td>trip</td>
  <td>unique identifier for each trip or event (e.g., workshop)</td>
</tr>
<tr>
  <td>leg</td>
  <td>leg indicator (e.g., 1, 2, …)</td>
</tr>
<tr>
  <td>chf_trip</td>
  <td>total price for trip in CHF</td>
</tr>
<tr>
  <td>chf_leg</td>
  <td>total price / number of legs</td>
</tr>
<tr>
  <td>departure</td>
  <td>departure airport IATA 3-letter code</td>
</tr>
<tr>
  <td>destination</td>
  <td>destination airport IATA 3-letter code</td>
</tr>
<tr>
  <td>date</td>
  <td>date of flight</td>
</tr>
<tr>
  <td>year</td>
  <td>year</td>
</tr>
<tr>
  <td>co2</td>
  <td>CO2 [t] including radiative forcing index</td>
</tr>
<tr>
  <td>km</td>
  <td>total distance in km</td>
</tr>
<tr>
  <td>dep_municipality</td>
  <td>municipality of departure airport</td>
</tr>
<tr>
  <td>dep_country</td>
  <td>country of departure airport (2-letter ISO 3166 code)</td>
</tr>
<tr>
  <td>dep_continent</td>
  <td>continent of departure airport</td>
</tr>
<tr>
  <td>dep_lon</td>
  <td>longitude of departure airport</td>
</tr>
<tr>
  <td>dep_lat</td>
  <td>latitude of departure airport</td>
</tr>
<tr>
  <td>des_municipality</td>
  <td>municipality of destination airport</td>
</tr>
<tr>
  <td>des_country</td>
  <td>country of destination airport (2-letter ISO 3166 code)</td>
</tr>
<tr>
  <td>des_continent</td>
  <td>continent of destination airport</td>
</tr>
<tr>
  <td>des_lon</td>
  <td>longitude of destination airport</td>
</tr>
<tr>
  <td>des_lat</td>
  <td>latitude of destination airport</td>
</tr>
</table>

## Background Readings

<a href="http://doi.org/10.3390/su11010080">Ciers, J., Mandic, A., Toth, L. D., & Veld, G. O. T. (2018). Carbon footprint of academic air travel: A case study in Switzerland. Sustainability, 11(1), 80.</a

Knaflic, C. N. (2015). Storytelling with data: A data visualization guide for business professionals.Hoboken, New Jersey: John Wiley & Sons, Inc. (For a summary see Chapter 8)
