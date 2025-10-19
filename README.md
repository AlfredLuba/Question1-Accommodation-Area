# Speke Apartments Accommodation Manager

 ### Project Overview

This is a simple Java console application designed to manage and monitor the status of two communal accommodation areas at Speke Apartments: the Gym and the Swimming Pool.

The application allows an Estate Manager to:

Switch between the active areas.

Track the number of occupants in each area.

Control the status of three lights (ON/OFF) in the active area.

Generate a real-time status report.

### Prerequisites

This program requires a Java Development Kit (JDK) installed and configured on your system. It is designed to run within the NetBeans IDE environment.

## How to Run in NetBeans

Ensure all four required source files (AccommodationManager.java, GymArea.java, SwimmingArea.java, and the AccommodationArea interface) are placed within the spekeapartments package.

Right-click the project folder.

Go to Properties $\rightarrow$ Run.

Set the Main Class to: spekeapartments.AccommodationManager.

Click the Run Project button ($\text{F6}$) and interact with the menu system in the NetBeans Output window.

## Key Features

Command

Functionality

S

Select Area: Switches the active area between the Gym and the Swimming Pool.

W/X

Occupants: Adds (W) or removes (X) a specified number of occupants from the active area.

Y/Z

Lights: Switches a specified light (1, 2, or 3) ON (Y) or OFF (Z).

R

Report: Displays the current occupant count and light status for the active area.

Q

Quit: Exits the application.
