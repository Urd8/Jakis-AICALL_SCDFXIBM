## Team Description
Hello Judges. We are the Jakis. The team consists of the following:

* Alfred - Temasek Polytechnic (Team Leader)
* Kin - Temasek Polytechnic
* Sherman - Temasek Polytechnic
* Iqbal - Temasek Polytechnic
* Juraimi - Temasek Polytechnic

We are Year 3 Students from the Diploma of Cybersecurity and Digital Forensics, and although the scope of the competition is a little outside of what we learnt, we were very excited to participate in this Call for Code Challenge.


## Problem Statement
From the problem statement, the problem we wanted to tackle was the "Integrating with a Smart Environment". As Singapore gets more and more developed, there are more IOT Devices available. SCDF's Resources are limited, and they cannot be deployed to everywhere at once, so how do we better priorotise the delegation of the SCDF Resources? Well, we can use the ever increasing number of IOT Devices to help us out with that.

## Solution
What our team proposes is an AI Assistant that will be answering 995 calls together with the SCDF Operator. How the AI Assistant works is that as the call progresses, it will take in and analyse different datasets, such as tone of voice, images of the incident at the location etc, in order to determine the severity of the incident. The AI Assistant will then output the results to the Operator's Workstation, and will then determine whether the incident is severe or not, as well as showing the key evidences that show whether it is severe or not. The SCDF Operator can then decide whether it is suitable to delegate Precious SCDF Resources or the Community First Responders (MyResponder) for less severe incidents.

## Pitch Video
The following is a link to our Pitch Video
https://www.youtube.com/watch?v=Si-FEZ7vTlU&feature=youtu.be

## Architecture of Proposed Soulution
Our Soultion will be mainly based on a React Webapp, with calls to the IBM Visual Recognition API and the IBM Voice Recognition Module.

## Detailed Solution
https://pastebin.com/WHDuPPZM

## Getting Started
For this example, we have used the React Webapp that can be found from the IBM Tutorial Series on Visual Recognition. The following are instructions to start the React WebApp

## Setup
`git clone` the repo and `cd` into the downloaded repo

Run the following command to install the required node modules
### `npm install`

> **Note: You’ll need to have Node 8.10.0 or later on your local development machine.** You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

## Run the App
### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

##What we used to build
We used the IBM Watson Studio, Machine Learning Service and the Visual Recognition Module
