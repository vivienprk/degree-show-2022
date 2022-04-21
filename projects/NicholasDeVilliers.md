---
layout: project
studentName: "Nick De Villiers"
supervisorName: "Dr Michael Crabb"
projectTitle: "Television Viewing in the Multiverse"
projectImage: "nicholasdevilliers.jpg"
---

## Project Description
For the most part, live sports are viewed on a single screen. This model seemed to work before everyone had cellphones, tablets and laptops. Nowadays, people are constantly using second screen devices in their living room while watching television, and in the case of live sports, these devices are often used in conjunction with the broadcast feed. For Formula One, people often enjoy looking at the live telemetry screens alongside the broadcast feed, as well as browsing social media and seeing what people are saying during the course of a session.

We wanted to create a web-based multi-screen experience that can tie together these aspects of watching Formula One, and hopefully be able to apply this technology to the viewing of other live sports in the future.

## How it was made
The three key things needed in order to make this program work is:
-A Formula One broadcast feed
-Telemetry Data
-Reddit comments from during a session
The broadcast feed can actually be obtained through Formula One's own API, provided you have the right subscription level on your account. A link can be retrieved to an HLS stream - the idea was to have this played in the browser through a media player, however due to security policies enforced by Formula One we were forced to instead ask users to open the stream in VLC media player. However, we were still able to retrieve the link for them automatically. Telemetry data was fetched with the FastF1 Python Library, which accesses a database of telemetry data going back to the start of 2018. This data can be parsed and then displayed in our webpage. For Reddit comments, Pushshift.io grants easy access to a large archive of reddit comments, which is updated in near real time. This allowed us to fetch old comments from old race megathreads on r/formulaone, and display them to the user as if they were being posted in real time.

For our stack, we decided to use a Django backend (since our telemetry was coming from a Python library), paired with a React frontend. These tools allowed us to create a complex multi-page website with a database that stores session data for viewing sessions.
