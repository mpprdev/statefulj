---
layout: page
title: Introduction
weight: 0
---

## What is StatefulJ?

[StatefulJ](http://www.statefulj.org) is a lightweight, open source Java [*Event Driven Finite State Machine(FSM)*](http://en.wikipedia.org/wiki/Event-driven_finite-state_machine) and a complete [*Spring Data*](http://projects.spring.io/spring-data/) based framework which lets you easily define and integrate State Machines into your Applications.

## What is a Finite State Machine?

I won't go into detail here as there is [a lot already written about them](http://en.wikipedia.org/wiki/Finite-state_machine).  But the important thing is that an FSM allows you to *model all your Domain events and State transitions into a coherent and testable package* instead of writing a scattershot of boolean flags and if-then statements. 

## Why should I use StatefulJ?

Applications have to manage and orchestrate [synchronous and asynchronous requests and events](http://www.reactivemanifesto.org/) from many sources: REST and SOAP APIs, Web Page requests, Message Queues, Internal Application Events, etc...  Handling concurrency and reliably updating Application state becomes a major challenge without the proper framework.  

By making it easy to integrate State Machines into your Application, *StatefulJ* provides you the ability to meet these challenges by creating *State Models* instead of writing ad-hoc code.

## What does StatefulJ provide?

StatefulJ provides the following "packages":

* [**StatefulJ Framework:**](/framework) A framework built off [*StatefulJ FSM*](/fsm), [*StatefulJ Persistence*](/persistence/) and [Spring Data](http://projects.spring.io/spring-data/) to easily integrate State Machines into your Application.
* [**StatefulJ FSM:**](/fsm) A dependency free, Finite State Machine implementation with support for non-determinstic Transitions.
* [**StatefulJ Persistence:**](/persistence/) A set of persistence support (JPA and Mongo) which works with the FSM library to persist your Stateful objects.

## How do I get started?

If you just want the [StatefulJ FSM package, then follow these instructions](/fsm)

If you want to integrate the [StatefulJ Framework, then follow these instructions](/framework)
