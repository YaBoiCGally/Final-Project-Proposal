# Final-Project-Proposal
Proposal Docs for a SRD5 Battle Simulator project, Final Project for CIS3296, Fall 2020

Cameron Gallagher | 14 Sept 2020 | Professor Dominic Letarte

### Project Description

In this project, I intend to implement a reduced ruleset presented in the [SRD5](https://media.wizards.com/2016/downloads/DND/SRD-OGL_V5.1.pdf), as presented by Wizard's of the Coast, making use of their Open Game License and Fan Content Policy.  The project will be coded entirely in Java, utilizing the flexibility of class and interface implementations, and inheritence and polymorphism. The project will utilize a GUI to represent a gridded battle map, with elements including PCs, monsters, areas of effect, and terrain modifiers.

Within the console, the user will be able to configure different units (PCs and monsters), implementing all of their stats, abiliites, and graphical representation.  After the creation a unit, its stats will be saved to an external file, or database, dependent on project group's preference.  The program will then be able to call back the files in subsequent executions, allowing the user to modify the unit and present it to the GUI.  PCs will make use of the various classes, races, and subclasses presented in the SRD5, and will be able to level up as the user needs.

As part of the initial implementation, there will be a number of built in PCs and monsters.  Each PC and monster will be able to make use of one of the hard coded AIs for behavior, which details the usage of actions, bonus actions and reactions on their turn.  The program will then automatically execute a full battle, determining the winner based on the preset conditions.

### Educational Goals

