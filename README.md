# ODS West 2022 - Workshop

Hey there, and welcome to Building a GPT-3 Powered FAQ Bot for Discord. In this tutorial, you’ll get a brief example of what we’ll be covering in the associated hands-on workshop at the Open Data Science (ODS) West conference at the [Venue], in San Francisco, on Wednesday, November 3, 2022.

While we’ll be going into more depth at the conference, this tutorial will introduce you to the technologies and core ideas covered in the workshop. We’ll start with a quick overview of the project we’ll be working on and a brief introduction to the technologies we’ll be using.

## What we’ll be building

We’re going to be building a GPT-3 powered bot that can answer questions from users through Discord. If you’re not familiar with Discord, it’s a chat platform, similar to Slack, WhatsApp, or Facebook Messenger. Users will be able to ask the bot questions that the bot will answer using OpenAI’s GPT-3.

The technologies we’ll be using

There are four services/technologies we’ll be using: Discord, Fly.io, the OpenAI API, and GitHub. As mentioned, Discord is a chat platform and we’ll be using it for our user interface. Discord will call a custom API that will act as a proxy or wrapper for the OpenAI API. The custom API will be created in NodeJS/Javascript and hosted via Fly.io. However, all of the heavy-lifting, in terms of the functionality will mostly be done by GPT-3 via the OpenAI API. Finally, we’ll be using GitHub to edit and store our code.

### General architecture

[Discord] ←→ [Fly.io] ←→ [OpenAI]

## Getting started

To begin you’ll need to create accounts for the following services if you don’t have one already. Each of the services has a free-tier and that’s all you need for this tutorial. 

- [Discord](https://discord.com)
- [Fly.io](https://fly.io)
- [OpenAI](https://openai.com)
- [GitHub](https://github.com)

We’ll be using a web-based code editor provided by GitHub. Of course, you could use just about any code editor but we’ll be using the GitHub code editor because it’s web-based and easy to get started with.
Setting up a GitHub repository

After creating a GitHub account, complete the following steps to create a new repository:

- Sign in at github.com
- Click the + button and then New Repository
- In the address bar, change .com to .dev to open the web-based code editor

At this point, you should see see the GitHub code IDE open. We'll come back to this so open a new browser tab to move on and setup a Discord server.

## Setting up a Discord server





Resources:

https://fly.io/
https://render.com/
https://discord.com/developers/docs/resources/webhook
https://github.com/dabblelab/gpt3-powered-discord-bot
https://help.openai.com/en/articles/6233728-answers-transition-guide
