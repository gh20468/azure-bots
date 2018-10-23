# Azure Bots

Global Trace Co is a new technology venture that tracks global movement of shipments and containers thourgh GPS and RFID Tracking. They have developed a bot which enables operators to start job traces and enable global tracking of movement of items with GPS and RFID Tracking. The bot simply allows an agent to inform that a job has been started and that it the Job is complete.

## Technology

The company wishes to prove that they can wrap this in a continous delivery pipeline ready for the vast amount of dev work that is going to be required to manage all the subsidary RFID notifications and the GPS trackers.

## Getting Started

1. Download and install the emulator from [here](https://aka.ms/bot-framework-F5-download-emulator)
1. Clone or download this repository
1. Open `src/ProactiveBot.sln` in Visual Studio 2017
1. Build the project to restore your references
1. `F5` to run
1. Open the Bot Emulator and load the .bot file from `src\Proactivebot\`

## Goal

Build a CI/CD pipeline that will build, test and deploy the solution in a safe and repeatable way. The pipleline should:

- Be triggered by source control or an event
- Execute a unit test (to be coded)
- Publish to a UAT environment
- Once UAT sign off is received, release changes to Production environment

## Change Scenario

- Change the greeting message to identify the System as Global Trace Tracker. 
- Alternatively, challenge yourself to a more interesting change, including new responses, etc.
