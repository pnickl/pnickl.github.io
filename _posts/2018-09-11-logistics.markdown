---
layout: post
title: "Integrated Truck and Manpower Scheduling in Cross-docks – Design and Analysis of a Heuristic Algorithm"
date:   2018-11-23 23:59:59 +00:00
image: /images/logistics.png
categories: thesis
author: "Peter Nickl"
venue: "Research thesis, BOSCH-Chair of Global Supply Chain Management, Sino-German College for Postgraduate Studies, Tongji University, China"
link: https://drive.google.com/file/d/1yIaqrm25w2AFVthQ5k7Shvuv11LUAVg1/view
excerpt: We design and implement a heuristic algorithm in C&#43;&#43; for solving a mixed-integer linear program targeted at scheduling problems in logistics.
abstract: We design and implement a heuristic algorithm for solving a mixed-integer linear program (MILP) for a scheduling problem in logistics. Cross-docking warehouses distribute goods from suppliers to customers with a storage time of only a few hours. Due to the permanent flow of incoming and outgoing trucks, it is very difficult for managers to schedule the trucks to available gates and to allocate the staff without overlapping assignments or long idle times. Exact methods like branch and bound are computationally restrictive when	 solving large MILP. In this project we (1) conduct a literature survey on metaheuristics, (2) design a heuristic algorithm to solve the problem efficiently, (3) prototype the algorithm in MATLAB, (4) create an efficient implementation in C++ and (5) evaluate the performance and run-time of the algorithm on test cases. The heuristic algorithm consists of the following elements. (1) A representation for encoding feasible solutions, (2) a fitness function for evaluating solutions, (3) construction of initial solutions, and (4) local search operators to find good solutions in the neighborhood of feasible solutions. The outcome is a heuristic algorithm tailored to the problem and an efficient C&#43;&#43; implementation.
---
