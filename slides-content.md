Slide 1. OpenClaw Workshop

From zero to your first working AI agent

This workshop is designed for beginners.
You do not need programming experience.
You do not need to understand servers in advance.

By the end of this session, you will:

understand what an AI agent is
understand the basic system behind it
set up OpenClaw
launch a simple working agent

The goal today is not mastery.
The goal is to leave with a working foundation.

Slide 2. About Me

Why I am running this workshop

My name is Aram. I am the founder of Empy.
I work on AI products and practical systems that help people use AI in real workflows, not just as a chatbot.

This workshop is built for people who want to move from curiosity to action:

not just "learn about agents"
but actually run one

Today I will guide you through the simplest path from zero to a working setup.

Slide 3. About Agentic EVN

A community for people building with agents

Agentic EVN is a community for people exploring and building with AI agents.

The idea is simple:

learn by doing
build in public
help each other get unstuck
turn curiosity into working systems

This workshop is part of that mission.
It is not just a one-time event.
It is a starting point for people who want to keep building after today.

Slide 4. What You Will Have by the End

The outcome of today's workshop

By the end of this workshop, you should have:

a server running in the cloud
OpenClaw installed on that server
a basic interface working
a simple agent connected and responding

Just as important, you should leave with a mental model of how the system works:

what the server does
what OpenClaw does
where the AI model fits in
how your agent becomes usable in practice

Slide 5. What Is an AI Agent?

More than a chatbot

An AI agent is a system that does more than generate text.

A normal chatbot responds to a prompt.
An agent can be given a role, a goal, and access to tools.

That means an agent can:

follow instructions
use external systems
perform actions
return results in a structured way

In simple words:
a chatbot talks, an agent works.

Slide 6. Agent vs ChatGPT

Why this is a different category

A chatbot is usually reactive.
You ask something, it answers.

An agent is closer to a worker or assistant:

it gets a task
it follows a process
it may use tools
it may produce an output beyond just text

Examples:

a chatbot can help draft a message
an agent can draft the message, organize it, and send it through a connected channel

This difference matters because it changes what AI can do for real work.

Slide 7. Where Agents Are Useful

Real examples, not hype

Agents are useful when work has some structure and repetition.

Examples:

a Telegram assistant that helps you think and reply faster
a research assistant that summarizes information
a personal workflow assistant that helps organize tasks
a business assistant that follows a defined role and process

You do not need a huge system to start.
A small agent with one useful job is often much better than a complex system with no clear use case.

Slide 8. The Use Case We Will Build Today

A simple first agent

Today we are not building a complex autonomous system.

We are building a simple first version:

an agent you can interact with
with a clear role
through a usable interface
connected to a real channel such as Telegram

Why this use case:

simple enough for beginners
concrete enough to feel real
useful enough to understand the value

The goal is to get your first win, not to impress people with complexity.

Slide 9. How the System Works

The simplest mental model

Here is the system in plain English:

You give instructions
The server is the remote computer where the system runs
OpenClaw manages the agent environment
The AI model provides reasoning and language capability
The channel lets you interact with the agent

So the flow looks like this:

You → Channel / Interface → OpenClaw → Model / Tools → Response

If you understand this, the rest becomes much easier.

Slide 10. What Is a Server?

A computer on the internet

A server is just a computer that runs somewhere else.

Instead of using your laptop as the main machine, you rent a remote computer in the cloud.

Why use a server:

it stays online
it can run 24/7
it gives your agent a stable home
it separates your working setup from your personal laptop

For today, you can think of a server as:
the place where your agent lives

Slide 11. What OpenClaw Does

The operating environment for agents

OpenClaw is not "the intelligence itself."
It is the system that helps you run and manage agents.

In practice, OpenClaw helps with things like:

configuration
agent setup
channels
runtime management
connecting your agent to models and tools

A useful way to think about it:

the AI model is the brain
OpenClaw is the environment that makes that brain usable

Slide 12. Where the Intelligence Comes From

OpenClaw is not the model

This point is important.

OpenClaw does not replace models like Claude or OpenAI.
It works with them.

That means:

OpenClaw gives structure and execution
the model provides language understanding and reasoning

So when your agent responds intelligently, that is usually because:

a model is connected
OpenClaw is routing the work properly
your instructions define the role and behavior

This is why setup matters.
A good agent is not only about the model.
It is also about the system around it.

Slide 13. What We Will Do Today

The workshop roadmap

Today's workshop has a simple sequence:

understand what an agent is
understand the basic architecture
create a server
connect to the server
install OpenClaw
complete onboarding
test the interface
connect a channel
launch a simple agent

We will go step by step.
You do not need to rush.
Progress matters more than speed.

Slide 14. Safety Basics

Do not give more access than necessary

AI agents can become useful very quickly.
That also means they can become risky if configured carelessly.

Basic safety rules:

do not paste secrets where you do not understand the context
do not grant permissions you do not actually need
use separate tokens and test accounts when possible
understand what the agent is connected to
if something feels unclear, stop and ask

A simple rule:
start with minimal access, then expand carefully

Slide 15. Before We Start

What you need right now

Before setup begins, make sure you have:

a laptop
internet access
email access
a Telegram account
a payment method if needed for the server provider
the ability to copy and paste commands

Today's setup is beginner-friendly, but it still depends on basic readiness.
The fastest workshops are the ones where this is checked before installation begins.

Slide 16. Step 1: Create a Server

Your first infrastructure step

The first practical step is creating a VPS, a virtual private server.

What happens in this step:

you choose a provider
you create a server instance
you choose the operating system
you receive an IP address

The key output of this step is simple:
you now have your own remote machine

That machine is where OpenClaw will be installed.

Slide 17. Checkpoint: You Have a Server

What success looks like

At this point, you should have:

a created server
access credentials
the server IP address

If you have those three things, you are on track.

If not, this is the moment to fix it.
It is much easier to solve problems here than later.

Slide 18. Step 2: Connect with SSH

Entering your remote machine

SSH is the standard way to access your server from your laptop.

You can think of it as:

opening a terminal
entering the remote machine
gaining control over that server

Why this matters:
before you install OpenClaw, you need to be inside the server environment.

This is usually the first moment that feels technical to beginners.
But conceptually it is simple:
you are just logging into another computer

Slide 19. Checkpoint: You Are Inside the Server

What success looks like

At this stage, success means:

you opened your terminal
you connected through SSH
you now see the server prompt

That means your laptop is talking to your remote machine correctly.

If this works, you have crossed one of the biggest beginner barriers.

Slide 20. Step 3: Install OpenClaw

Turning the server into an agent system

Now that you are inside the server, you can install OpenClaw.

This is the moment where your plain remote machine becomes a machine prepared for running agents.

The installation step usually:

downloads the required components
sets up the environment
prepares the system for onboarding

The key idea here:
you are not "doing server engineering"
you are preparing a runtime for your future agent

Slide 21. Checkpoint: Installation Finished

What success looks like

At this point, the installation should complete successfully.

What that means:

the required components are in place
the system is ready for the next setup stage
you can move into onboarding

If something failed here, do not improvise randomly.
This is a normal point for troubleshooting.

Slide 22. Step 4: Onboarding

Initial system configuration

Onboarding is the step where OpenClaw asks for the information it needs to become usable.

This can include:

setup values
tokens
configuration choices
channel-related settings

For beginners, onboarding often feels harder than installation because the system starts asking questions.

The important thing to remember:
this is normal.
You are moving from "software installed" to "system configured."

Slide 23. What Is Happening During Onboarding

Why this step matters

Installation alone does not give you a working agent system.

Onboarding is the step that:

creates the base configuration
connects important pieces
makes the system actually usable

In other words:
installation puts the parts on the machine
onboarding turns those parts into a working setup

That is why this step matters so much.

Slide 24. Checkpoint: OpenClaw Is Running

What success looks like

At this stage, success means:

OpenClaw is initialized
the core system is active
you are ready to test access and interface

This is the moment where your setup stops being theoretical.
You now have a live system.

Slide 25. Step 5: Check the Interface

See the system, not just the terminal

Until now, much of the work has happened in the terminal.

Now we check the interface so you can confirm:

the system is alive
the service is reachable
you can interact with it more comfortably

This is important for confidence.
A visible interface makes the system feel real.

Slide 26. Checkpoint: The UI Works

What success looks like

If the interface opens and responds, you have already completed most of the hard part.

That means:

your server is live
OpenClaw is reachable
your setup is structurally working

You are no longer "trying to set something up."
You already have a working system base.

Slide 27. Step 6: Connect Telegram

Give your agent a real communication channel

An agent becomes much more useful when you can interact with it through a real channel.

Telegram is a good first channel because it is:

familiar
easy to use
practical for testing

In this step, you create or connect a Telegram bot and attach it to your setup.

This turns your agent from "something on a server" into "something you can actually talk to."

Slide 28. Step 7: Create the First Agent

The simplest useful version

Now we define the first agent.

This usually means:

giving it a role
giving it basic behavior
testing the first interaction

Important principle:
do not try to make the perfect agent today.

Your first goal is much smaller:
make one agent that works

That is enough to unlock understanding.

Slide 29. First Result

Your agent responds

This is the key milestone of the workshop.

If your agent responds through the system you set up today, then you have done something important:

you created infrastructure
you installed the platform
you configured the environment
you launched a working agent

That is not theory.
That is a real build.

Slide 30. If Something Breaks

Troubleshooting is part of the process

If something does not work, that does not mean you failed.

In systems like this, common issues happen around:

server creation
SSH access
configuration
tokens
channels

The right response is not panic.
The right response is structured troubleshooting.

This is normal for real technical work.

Slide 31. What You Have Now

Your new foundation

By this point, you have more than just "an app installed."

You now have:

a server
a running agent environment
a working interface
a first connected channel
a basic agent

This is enough to start learning by iteration instead of theory alone.

Slide 32. What To Do After the Workshop

The first next steps

The best next step is not "build something huge."

It is:

improve your first prompt
test one useful use case
change the role of your agent
try one real workflow
keep the setup alive and interact with it

Small iteration beats big ambition at this stage.

Slide 33. Agentic EVN: What Comes Next

Do not stop at the first setup

This workshop is the starting point, not the finish line.

If you want to keep going:

stay in the community
ask questions
share what you built
keep testing use cases
build confidence by repetition

The people who get value from this space are usually not the smartest people in the room.
They are the ones who keep building after the first workshop.
