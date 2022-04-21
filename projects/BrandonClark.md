---
layout: project
studentName: "Brandon Clark"
supervisorName: "Dr Jacky Visser"
projectTitle: "Development of a self-contained environment mapping artefact"
projectImage: "Environment_mapper.jpg"

---


## Project Description
With the world being connected more every day, wireless technologies are becoming a crutch for many devices. This became the caveat for the project. The aim of this device  was to create a fully self contained handheld artefact that will map a room with attention to an environmental factor. This makes mapping in areas such a mines or crypts where network connectivity isn’t possible, achievable.

### Requirements
- Handheld
- No required wireless connection
- Intuitive processed data  

## Project Findings
To achieve a level of localisation, an IMU was used. This approach isn’t without its flaw. IMUs experience drift due to gravity which means all axes became very imprecise very quickly especially with lower quality parts. This presents an issue but with some work arounds, acceptable results are achievable.

What has been created is a lightweight, handheld SLAM based room mapping device for use with a monopod and a gimbal mount. This device is expandable and modular with use of better or different sensors to be used in different use cases. 
Also included is an extension of the DP-SLAM software to include overlays of the chosen sensor (Humidity & Temperature) and export a PNG.



## Project Media
Attached is a playlist of tests at different stages of development 

<iframe width=100% height="500" src="https://www.youtube.com/embed/videoseries?list=PL_u1CSI3fmsWf8zcTtAbwi56pIwcae1B1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


