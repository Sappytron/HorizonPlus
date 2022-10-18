# HorizonPlus
A UI project for Forza Horizon 5, aiming to improve the existing framework with a plethora of new information for maximum detail and tools to improve your racing.

DEV NOTE: 1.1 is currently delayed. One of the planned fixes is hiding the UI when in Festivals / Homes, however the game does not provide an 'inGarage' flag. As a result I am having to develop a 'coordinate matrix' which is taking a lot of time.
1.0.2 is now out with some of the planned updates / fixes for that release while I take my time on the bigger stuff.

HorizonPlus is designed to enhance and augment the existing UI with new features and additions for players of all disciplines.
SimHub is required to be installed for the overlay to function.

INSTRUCTIONS:
- Install SimHub: https://www.simhubdash.com/download-2/ (A restart will be required to finish install.)
- Unzip all files into a folder.
- Install the .simhubdash files with a double click, and confirming the popup. 
- Copy the 'OverlayLayouts' folder contents into your SimHub install folder of the same name.
  - Alpha/Beta Testers: When upgrading, be sure to click "Replace Files". Delete legacy files for the optimal experience.
- Configure the game: Go to Game Settings > HUD and Gameplay:
  - Turn on 'Data IP Out'.
  - Set "Data IP Out Address" to 127.0.0.1.
  - Set "Data IP Out Port" to 8000.
- Start the Overlay in Dash Studio > Overlays > (HorizonPlus [Target Resolution])
- You're done! If the overlay doesn't show up initially, restart the game and SimHub after setting up.

FEATURES:
- Live Player Inputs: 
   - Throttle
   - Braking
   - Clutch
   - Steering
   - Handbrake

- Additional Readouts:
   - Per-Lap Delta
   - Last Lap
   - Peak Speed
   - Boost Pressure Gauge (Psi by default - Alternate 'Bar' version is packaged / requires manual addition.)
   - Accelerometer
   - G-Forces
   - Suspension Compression Model
   - Slim Version of Lap / Race Position UI

- Visual Per-Tire Model:
   - Temperature Average
   - Grip / Wheelspin
   - Standing Water Indicator
   - Drivetrain Detection
   - Tyre Data Table (For Swapping Values - Switcher coming soon)

IMPORTANT INFORMATION:
- Pausing / Rewinding internally resets the session, meaning Delta will be incorrect for the following lap and Peak Speed data will reset.
- The overlay is compiled of modules that you can swap and change to your personal preference. Find the right setup for you.
- HorizonPlus comes with 1080p, 1440p and 4K presets. Other resolutions, playing on non-primary monitors and changing UI Scale / safezones will require adjusting of the UI.
- Users running V-Sync and G-SYNC/FreeSync simultaneously may experience issues due to SimHub's hook process.
- The tire heat model is tuned for Semi-Slicks.

HorizonPlus was created by Sappytron.

Special thanks to the following community members & teams for helping to test, develop or otherwise support the project throughout it's development:
- The 1 Hour of Racing Team
- The FIDA Team
- Scarshe
- Saeenu
- Forzurda
- URAF6 Genji
- Carat
- SWR Quackula
- ChimiChungo
- YoYoGavri
- ATK Mang0
- The Hand of God
- gRg WildCard
- Azhbruh
- KawzNova
- peel
