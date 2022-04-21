---
layout: project
studentName: "Tadas Saltenis"
supervisorName: "Dr Iain Martin"
projectTitle: "Spacecraft Mission Visualiser"
projectImage: "lunar_surface.png"

---

## Project Description
Simulating vision-guided spacecraft landing with physical mock-ups is expensive,
inflexible and difficult to get right in terms of realistic lighting and
atmosphere conditions. Because of this, virtual simulations are a very powerful
tool for testing and verifying such future missions.

PANGU is a powerful toolset for making models and surfaces of planetary bodies
and asteroids using real and artificial data. It has various features focusing
on generating images for off-line and closed-loop simulations, including
planetary landings. The method of generating the simulations, however is not
very interactive, requiring the user to wait for the whole simulation to finish
before viewing its results.

The aim of the project was to design an application that would help with
producing PANGU spacecraft flight simulations, making the process more intuitive
and interactive compared to the existing solution.

## Technologies
The technologies used to implement the application were C++ as the main
programming language, the Qt framework as the GUI platform, Git for source code
versioning, GitHub for hosting the source code and project management, KDE's
breeze-icons as the main icon pack and Doxygen for generating documentation.

## Results
During the project, most of the features initially sought out to be in the
application were implemented, with some additional features and changes as
requested in user feedback.

The final product is a desktop application for Microsoft Windows and Linux
platforms that serves as an intermediary between the user and the PANGU Viewer,
allowing easier spacecraft flight/landing simulation production. This was
achieved by providing a way to immediately see and debug results of flight file
commands, view visualisations of flight trajectories, control the simulation
in multiple ways, as well as various settings and customisation to fit different
workflows and preferences.

## Screenshots of the user interface
<img style="max-width:100%" src="/project_images/SpaceMissionSimVis.png" alt="A screenshot of the default interface">

---

<img style="max-width:100%" src="/project_images/SpaceMissionSimVis_floating.png" alt="A screenshot of the default interface with adjustments made by the user">

---

<img style="max-width:100%" src="/project_images/SpaceMissionSimVis_settings.png" alt="A screenshot of one of the settings pages">