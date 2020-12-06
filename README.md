# Quadratic Assignment Problem

A mathematical model proposed by Koopmans and Beckmann thats models the real-life problem:  

>  There are a set of *n* facilities and a set of *n* locations. For each pair of locations, a *distance* is specified and for each pair of facilities a *weight* or *flow* is specified (e.g., the amount of supplies transported between the two facilities). The problem is to assign all facilities to different locations with the goal of minimizing the sum of the distances multiplied by the corresponding flows.

This project is an attempt to explore different algorithms to find a solution to a Qudratic Assignment Problem defined as following: 

In the Quadratic Assignment Problem (QAP) we are given a set F of n facilities and a set L of n locations. The goal of the QAP is to assign all facilities to locations such that each facility is assigned to exactly one location and the flow weighted sum of the distances is minimized. Assume the company LuneLog decides to start assembling furniture. The board of directors preselected 5 places in Germany as locations for 5 new facilities to be built. These locations are marked with letters A to E in green circles in Figure 1. Furthermore, they decided which facility will perform each task and determined the flow between the facilities given by Table 1. Distances between the preselected locations are given in Table 2.

![loc](../loc.png)