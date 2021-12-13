---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

<hr>

## A Dynamic Bandwidth Allocation Program in a Software-Defined Network

_June '20_
<br>

A Software Defined Network can be used to separate the data and control planes of networking components and to create a centralized control plane, called the SDN Controller which acts as the brain of the network. The controller governs the actions of the individual components of the network. It uses two types of API to communicate with the networking components, namely, northbound and southbound APIs. A southbound API is used by the controller to send configurations and flow-rules to the connected networking components. By taking advantage of these flow-rules, a network can be made more dynamic and software controlled. In the current networking scenario, users gain access to the internet via an ISP who allocates a fixed bandwidth to the user regardless of the bandwidth usage by the user. This is disadvantageous to both end user and the ISP as bandwidth is not conserved during idle times. By building such a network application working in an SDN environment, we allows users to request the controller for a fixed amount of bandwidth for a specified amount of time to any other host that is connected to the topology. The network application would built on top of an SDN controller, and would work by configuring QoS queues and flow-rules onto connected networking components with help of the southbound API Open Flow. The configured QoS queues would limit bandwidth to minimum & maximum values, and the flow-rules qould en-queue traffic from different hosts onto the created QoS queues. The client side of the network application may run on any node in the topology and is designed to send bandwidth requests to the controller. The controller would respond to the client-application with response codes representing the success/failure of bandwidth allocation. This project implements said network application in a scalable network topology deployed as an SDN.

[Link to the project](https://github.com/abhilash-venkatesh/SDNProject)

<hr>

# Undergraduate Coursework Projects

## 15CSE376 - Net Centric Programming

### A simplified course management system with assignments, quizzes, grading and attendance monitoring.

_Jun ’19 – Oct ’19_
<br>

<li>Tools: Javascript, HTML, CSS, Java</li>
<li> <a href='https://github.com/ShriRamaJeyam/NCP3'>[Link]</a> </li>
<li> Grade Obtained: 'O' (=10/10) </li>

## 15CSE313 - Software Engineering

### An event management system to simply the planning and hosting of events

_Dec ’18 – May ’19_
<br>

<li>Tools used: NodeJS, Web Development, JIRA, Selenium, Testing tools</li>
<li> <a href='https://github.com/uma-subbiah/EventIt'>[Link]</a> </li>
<li> Grade Obtained: 'A+' (=9/10) </li>

## 15CSE302 - Database Management System

### A portal to track the infant mortality rates across the Indian subcontinent

_Jun ’18 – Nov ’18_
<br>

<li>Tools used: SQL, Database design using ER diagrams, EER, Normalisation, Java Database Connectivity</li>
<!-- <li> <a href='https://github.com/uma-subbiah/EventIt'>[Link]</a> </li> -->
<li> Grade Obtained: 'A+' (=9/10) </li>

<hr>
