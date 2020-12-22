---
title: What in the world is Docker and is it important? 
date: "2020-12-22T22:12:03.284Z"
description: "In recent times, you might've heard the term 'Container' and might've wondered what exactly is it and why does it even exist? Let me answer that for you."
---

Hey buddy.

Hope you are doing `super();`

In recent times, you might've heard the term **Container** and might've wondered what exactly is it and why does it even exist?

Let me answer that for you.

## What is a container?

> A container is an instance of an image that is created using a tool called Docker. This instance is isolated from other such instances and your local system.


Simple, right?

Maybe not.

Let me explain that in a much easier way. But first, let's understand the need for a Docker Container.

Have you ever used two different installations of your operating system or two separate PCs to get around the problem of dependency versions for your projects because one project needs one version and the other one requires another?

You might've also solved this problem by virtualization using something like VMware.

Let's be honest. These workarounds solve the problem but not in a very efficient way.

The resources required to pull something off like this is very high. You have to install a brand new operating system!

What if we have 5 separate projects and we need 5 different versions of a dependency for these 5 projects?

Not a pretty picture, right?

This approach isn't scalable. So, what's a good solution?

Enter **Docker**.

Docker solves this problem in an efficient way.

Unlike our traditional VMs, it's blazing fast!

It lets us create several instances of an image (a file system snapshot of the programs needed to run your project/app).

We can use this image to create containers and run them!

Containers are like an operating system in themselves! Like a VM or a PC. They consume resources from your local PC. But resource utilization is very less.

As one container is isolated from other containers, we can create multiple containers with different versions of our dependency in each container and they'll all run without problems!

## Why does a container consume fewer resources as compared to a VM?

Docker uses one *Kernel* for running all the containers.
This results in lesser resource usage and better performance.

### What is the Kernel?

The Kernel is a computer program that is present at the very core of your computer's operating system. It controls each and everything in your system.

We can share the images with other people and they will have the same container as yours. They will be able to run the program in the same way as you intended it to run.

Gone are the days when people used to say.

> It's running on my system. There must be a problem with your system.

All of this is exciting!

Why don't you spin a new Docker container?
