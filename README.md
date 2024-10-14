# calendarAPI
Writen by Jitske Bos
Last update 14 october 2024 11:16

## Introduction
In this manual you will learn how to import data from Google Calendar in Arduino IDE and trigger actions based on upcoming events

Items needed for this manual:
- bla
- bla

## Step 1: Create a new feed in Adafruit
Go to the [Adafruit website](https://io.adafruit.com)

**Create an account on Adafruit** if you don't have one alrady

*If you already have an account, log into Adafruit*

### Create a feed

On the homepage, click on **Feeds**

<img width="678" alt="Scherm­afbeelding 2024-10-13 om 19 52 57" src="https://github.com/user-attachments/assets/1847ddfe-a859-4d7c-bbb0-e3555d8f9bd6">

You're now on the feed page

To create a new feed click **Need Feed**

In this manual we will use the name ***"activity"*** <sub>because I don't need to extract something specific</sub>

You can name your feed anything, as long as it is simple and recognizable name  

Click on **Create** to create the feed

<img width="640" alt="Scherm­afbeelding 2024-10-13 om 20 11 15" src="https://github.com/user-attachments/assets/35f9bbf2-5afd-40af-bcc1-025728e5988b">

**Open the feed** you just created by clicking on the blue name

It will be empty for now, until we send data to it using Zapier

<img width="373" alt="Scherm­afbeelding 2024-10-13 om 20 22 09" src="https://github.com/user-attachments/assets/6474c8e3-8eb0-477a-8eab-57e4025ceeb2">

## Step 2: Create a new zap in Zapier
Go to the [Zapier website](https://zapier.com)

**Create an account on Zapier** if you don't have one alrady

*If you already have an account, log into Zapier*

### Make a Zap
We are going to make a connection between Google Calendar and Adafruit, this is called a **Zap**

On the homepage, click on **Zap** on the left side of your screen

<img width="290" alt="Scherm­afbeelding 2024-10-13 om 20 36 26" src="https://github.com/user-attachments/assets/716564ab-ce9a-41f6-8b1b-a35a68d04ef2">

You're now on the zaps page

To create a new Zap click **Create Zap**

<img width="625" alt="Scherm­afbeelding 2024-10-13 om 20 38 15" src="https://github.com/user-attachments/assets/6d8123c9-4d60-4f5e-a74c-c9a2fe7870df">

## Step 3: Connect your Google Calendar
Click on the **trigger** part of the Zap

<img width="1001" alt="Scherm­afbeelding 2024-10-13 om 20 43 43" src="https://github.com/user-attachments/assets/e1e94978-8fac-4dee-b64c-53750a14f228">

This will lead you to a list of apps and tools

Click on **Google Calendar**

<img width="555" alt="Scherm­afbeelding 2024-10-13 om 20 47 14" src="https://github.com/user-attachments/assets/0fd9c1f1-c59b-420b-9221-d717e4af8548">

From here you will build the connection

Under *Trigger Event* choose **Event Start**

<img width="803" alt="Scherm­afbeelding 2024-10-13 om 20 52 20" src="https://github.com/user-attachments/assets/c69cbf37-0e1e-4fe2-a083-3df1ede19fa7">

Click on **Connect Google Calendar** 

Sign in using your Google Account

![Scherm­afbeelding 2024-10-14 om 11 18 03](https://github.com/user-attachments/assets/160a5e75-e51d-4215-8397-ed0dfae38c3d)

## Stap 4: Customise Calendar

**Choose the calendar** in your account that you would like to use

Set the time before you want Zapier to trigger
