---
title: "Proto.Actor Documentation"
date: 2020-05-28T16:34:24+02:00
draft: false
tags: [protoactor, docs]
---

# Proto.Actor Framework

## TLDR; Just show me the code!

* [Hello World](hello-world.md)
* [Getting Started](getting-started.md)

## Introduction

* [What is Proto.Actor?](what-is-protoactor.md)
* [Why Proto.Actor](why-protoactor.md)
* [Design Principles](design-principles.md)
* [Features](features.md)

## Proto.Actor Concepts

* [What is an Actor?](actors.md)
* [What is a Message?](messages.md)
* [Terminology, Concepts](terminology.md)
* [Supervision and Monitoring](supervision.md)
* [Actor lifecycle](life-cycle.md)
* [Location Transparency](location-transparency.md)
* [Message Delivery Reliability](durability.md)

## Building Blocks

* [Actor](actors.md) - What are actors?
    * [Props](props.md) - How do I configure actors?
    * [Spawning Actors](spawn.md) - How do I instantiate actors?
    * [PID](pid.md) - How do I communicate with actors?
    * [Mailboxes](mailboxes.md) - How does the actor process messages?
    * [Deadletter](deadletter.md) - What happens to lost messages?
    * [Router](routers.md) - How do I forward messages to to pools or groups of workers?
    * [Eventstream](eventstream.md) - How are infrastructure events managed?
    * [Behaviors](behaviors.md) - How do I build state machines with actors?
    * [Middleware](middleware.md) - How do I intercept or observe messages between actors?
    * [Receive Timeout](receive-timeout.md) - How do I trigger code when actors go idle?
* [Persistence](persistence.md) - How do I persist state for actors?
* [Remote](remote.md) - How do I communicate with actors on other nodes?
    * [Remote Deployment](remote-deploy-md) - How do I spawn actors on other nodes?
* [Cluster](cluster.md) - How do I build clusters of actor nodes?
* [SimpleScheduler](scheduling.md) - How do I send messages on a timer?

## Useful Patterns

* [Message Throttling](throttling.md)
* [Work Pulling Pattern](work-pulling.md)
* [Limit Concurrency](limit-concurrency.md)
* [Scheduling Periodic Messages](scheduling.md)

## Additional Information

* [Books](books.md)

