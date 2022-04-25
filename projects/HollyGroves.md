---
layout: project
studentName: "Holly Groves"
supervisorName: "Dr Daniel Rough"
projectTitle: "Alexa Skill Development for Energy-Saving Practices"
projectImage: "AlexaIcon_hg.png"

---

## Project Description
Climate change is a problem for everyone. In order the help the environment, everyone should be doing what they can to reduce their carbon footprint. An ideal way for an individual to do so is reducing the amount of energy they consume, however not everyone has the knowledge of how this can be done.

Amazon’s Alexa devices are in people’s homes, where they consume their energy, and are part of the user’s every-day life. This creates a chance for an Alexa skill to provide energy-saving tips and persuade the users to act on the recommendations given.

The aim of the project is to develop such skill by researching into persuasive techniques voice use interfaces can use. The skill will also store information provided by the user on their energy consumption to assist the feedback given.

## Project Findings
### Research
Research was conducted into three areas before development began, these areas were; eco feedback, voice user interfaces and persuasive technology. The project links these three ideas together by creating an Alexa skill to give feedback on energy usage to persuade users to become more energy efficient. 

From the background research, an Alexa skill would be suited to this as it can provide real-time feedback in locations where household energy is most likely to be consumed. Meaning users would only need to speak commands to interact with the skill, requiring minimal effort.

### Development
The Alexa skill developed, entitiled 'Energy Log', provides the following functionalities/information to encourage energy-saving practices. Each bulletpoint represents an intent within the Alexa skill:

- Adding appliances: this allows users to add appliances they have used to the skill, to keep track of where and when their energy is being consumed. Currently, it is only possible to add a limitted number of different appliances to the skill. In future, with the use of smart technology, this can be avoiding by appliances automatically providing their energy usage and when they were used to the skill.

- Total energy usage: the total energy usage, which is calculated based off of user information proivded to the skill along with average energy consumptions, can be provided by day, week, month or year. Total energy usage is presented as a cost, rather than more technical kilowatt hours, simillar to a smart metre.

- Energy usage for specific appliances: similar to total energy usage, the energy usage for a specific appliance can be provided using the user inputted information and average energy consumptions. This is also presented as a cost and can be provided by day, week, month or year.

- Appliance with the highest usage: this provides the appliance that consumed the most energy over a given time frame. This can be for a certain day, week, month or year.

- When the peak energy usage occurs: the peak hour in a day, or peak day in a week can be provided. The 'peak' refers to when the most energy was used for that day or week. Allowing users to see when their energy usage is the highest.

- Comparison between different time frames: a comparison between differet days, weeks, months or years can is also available to users. This states which time frame had the highest associated costs, and how much more it cost. For example, you could say 'which week used more energy, last week or this week?' and the skill would respond with 'last week was the highest, you used £X.XX more than this week'.

- Provide recommendations: feasible energy-saving tips/recommendations are also available to motivate users into reducing their energy consumption. A general recommendation can be provided, which would give a randmo recommendation from the full list. Or there is the option for a specific recommendation, this calculates the user's highest appliance from the last week and gives a random energy recommendation for that device, if there is one available. If no specific recommendations are available, then a general one is given instead. 

- Add user specific energy tariff: the skill uses the average UK energy tariff (28p p/kwh) to calculate the cost of energy consumed. There is also an option for the user to add their own tariff, to make the information the skill provides more accurate and personal to them. 

- Add user specific time zone: as the skill associates the user's energy usage with a date and time, it is important that the user's time zone is correct. So there is functionality for the user to add their time zone when the first open the skill. If they wish to update their time zone at a later date, they can also do so.

