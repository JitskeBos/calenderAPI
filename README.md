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

<img width="412" alt="Scherm­afbeelding 2024-10-17 om 12 41 39" src="https://github.com/user-attachments/assets/8c01d53b-9a4b-4004-ad34-e6772d55a3d4">

## Stap 4: Customise Calendar

**Choose the calendar** in your account that you would like to use

Set the time before you want Zapier to trigger

Click on **Continue**

<img width="425" alt="Scherm­afbeelding 2024-10-17 om 12 44 00" src="https://github.com/user-attachments/assets/712f7629-4443-4f66-8353-97e0d89ff851">

Click **Test Trigger**

<img width="412" alt="Scherm­afbeelding 2024-10-17 om 13 07 49" src="https://github.com/user-attachments/assets/774db8ed-1fec-4394-9374-6a8e9997e386">

## Stap 5: Connect Adafruit

Click **Continue with selected record**

<img width="413" alt="Scherm­afbeelding 2024-10-17 om 13 27 46" src="https://github.com/user-attachments/assets/c38f6e94-b26f-45ea-a12a-3513fafd36ee">

Now you can connect an app to the event

Under *Search apps and tools*

Search **Adafruit** and select it by **clicking** on it

<img width="560" alt="Scherm­afbeelding 2024-10-17 om 14 31 47" src="https://github.com/user-attachments/assets/970bdcaa-47a6-4280-a63e-a646de872df6">

Under *Action event* choose **Create Feed Data**

<img width="799" alt="Scherm­afbeelding 2024-10-17 om 14 33 55" src="https://github.com/user-attachments/assets/67e77719-ff4b-4799-bbf6-ae0e0a8f5e21">

Click on **Connect Adafruit IO**

Sign in using your Adafruit account

### Doesn't it work?

Here are some reasons why connecting your Adafruit account isn't possible

- Make sure the privacy setting on your feed is public
<img width="233" alt="Scherm­afbeelding 2024-10-17 om 21 32 38" src="https://github.com/user-attachments/assets/8fe71b27-ce89-4202-83a6-4b1ed23c8a87">

To change this

Click on **Privacy**

Change *Private* to **Pubic** and click **Save**

<img width="638" alt="Scherm­afbeelding 2024-10-17 om 21 29 34" src="https://github.com/user-attachments/assets/3637b41b-6ada-4453-af4d-9bee1041b39d">

