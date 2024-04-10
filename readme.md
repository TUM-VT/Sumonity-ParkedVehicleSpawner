# Vehicle in the Parking Spaces 

## Overview
This repository provides a Unity-based simulation for adding various types of vehicles to parking spaces with customizable occupancy rates from 0% to 100%.

## Setup Instructions

1. **Clone the Repository:** Start by cloning this repository to your local machine or download the ZIP file and extract it in your project's Assets directory. The path should look like this: `Assets\ParkedVehicleSpawner`

2. **Create StreamingAssets Folder:** In your project's Assets directory, create a new folder named `StreamingAssets`. The path should look like this: `Assets\StreamingAssets`.

3. **Copy OpenDrive File:**
   - Navigate to the `Assets\3d_model` directory.
   - Locate the `tum_main.xodr` file.
   - Copy the `tum_main.xodr` file into the `Assets\StreamingAssets` folder you created earlier. The final path should be: `Assets\StreamingAssets\tum_main.xodr`.

## Usage
After setting up the project, you can adjust the occupancy rate and vehicle types directly within the Unity editor. Make sure to save your changes and run the simulation to see the effects in real-time.

## Notes
- When adding or changing vehicle prefabs, always check their heights to ensure they fit within the designated parking spots.
- Ensure the `tum_main.xodr` file is correctly placed in the `StreamingAssets` folder for the simulation to run properly.

