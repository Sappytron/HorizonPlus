# HorizonPlus
A UI project for Forza Horizon 5 and Forza Horizon 6, aiming to improve the existing framework with a plethora of new information for maximum detail and tools to improve your racing.

HorizonPlus is designed to enhance and augment the existing UI with new features and additions for players of all disciplines.
The latest version of SimHub is required for the overlay to function.

INSTRUCTIONS:
- Install SimHub: https://www.simhubdash.com/download-2/ (A restart will be required to finish install.)
- Unzip all files into a folder.
- LOADING THE DASH MODULES:
	- Included with HorizonPlus is the modules themselves, denoted by the SimHub icon and .simhubdash file extension.
	- Double clicking these files will bring a pop-up window to install the modules. Install all bundled modules.
	- Ensure that "Install Fonts" is ticked, before clicking "Import into SimHub Library".
- Copy the 'OverlayLayouts' folder contents into your SimHub install folder of the same name.
  - Alpha/Beta Testers: When upgrading, be sure to click "Replace Files". Delete legacy files for the optimal experience.
- Configure the game: Go to Game Settings > HUD and Gameplay:
  - Turn on 'Data IP Out'.
  - Set "Data IP Out Address" to 127.0.0.1.
	- If on Xbox, set it to your PC's IPv4 - more info below.
  - Set "Data IP Out Port" to 8000.
- Start the Overlay in Dash Studio > Overlays > (HorizonPlus [Target Resolution])
- You're done! If the overlay doesn't show up initially, restart the game and SimHub after setting up.

INSTRUCTIONS - XBOX USERS:
- Find your PC's IPv4 address. For further information, head here: https://support.microsoft.com/en-us/windows/find-your-ip-address-in-windows-f21a9bbc-c582-55cd-35e0-73431160a1b9
- Set your PC's IPv4 address as the "Data IP Out Address".
- Start the dedicated dashboard in Dash Studio > Dashboards > "HorizonPlus Xbox Companion" and clicking the thumbnail.
  - For sending the dashboard to a mobile device, press Start > 'On Phone or Tablet' and follow the on-screen instructions.

FEATURES:
- Live Player Inputs: 
   - Throttle
   - Braking
   - Clutch
   - Steering
   - Handbrake

- Additional Readouts:
   - Per-Lap Delta (2 Variants)
   - Last Lap
   - Peak Speed
   - Boost Pressure Gauge (PSI by default - This can be switched to BAR in the Gauge's settings.)
   - Accelerometer
   - G-Forces
   - Suspension Compression Model
   - Slim Version of Lap / Race Position UI

- Visual Per-Tire Model:
   - Temperature Average
   - Grip / Wheelspin
   - Water Indicator

IMPORTANT INFORMATION:
- Pausing / Rewinding internally resets the session, meaning Delta will be incorrect for the following lap and Peak Speed data will reset.
- If you are making overlay adjustments, it is recommended to set 'Pause on Focus Lost' to 'Disabled' in the 'HUD & Gameplay' tab. Tabbing out will allow you to keep UI on screen for easy placement.
- The overlay is compiled of modules that you can swap and change to your personal preference. Find the right setup for you.
- HorizonPlus comes with 1080p, 1440p and 4K presets. Other resolutions, playing on non-primary monitors and changing UI Scale / safezones will require adjusting of the UI.
- HorizonPlus is calibrated for the default UI scale and safezones. Any adjustments to this will require manual adjustment.
- Users running V-Sync and G-SYNC/FreeSync simultaneously may experience issues due to SimHub's hook process.
- The tire heat model is tuned for Semi-Slicks. These values can be changed in the Dash Editor using the provided data table for different compounds.
- It is recommended to switch to SimHub's HTML rendering engine for improved performance in GPU-limited scenarios.

HorizonPlus was created by Sappytron.

Special thanks to the following community members & teams for helping to test, develop or otherwise support the FH6 project throughout it's development:
- The FIDA Team
- The ForzaDash Team
- Minero
- HokiHoshi
- (In memory of) ChimiChungo
- YoYoGavri
