# Assetto-Timing-Issue-Tracker
Repository to report bugs and issues with Assetto Timing
Assetto-Timing is and will remain closed source. 

About AssettoTiming

Assetto Timing is a global leaderboard. It keeps track of all times captured and submitted via the corresponding mod. Unlike traditional leaderboards that are tied to specific servers or sessions, Assetto Timing allows you to submit lap times when playing in any server, session, online or single player. No manual submission or account is needed.
Contact me on discord for a beta invite.

Discord: doc.friday


FAQ
How does the leaderboard and mod work?
The mod captures lap times and uploads them to the leaderboard automatically.

How do I download and use the mod?
During the beta phase, the mod is online available privately to a limited number of testers. When it's publicly available, simply install the mod and start any session. You can play singleplayer (hotlap, practice, trackday, race e.t.c. ) or join any online server you wish. The mod will capture your lap time and upload it.

Are there any restrictions?
Yes. Lap times will only be submitted if penalties are enabled and the lap is valid. If your offline session or online server has penalties disabled, the lap will not be submitted or stored.

What about track, car conditions and settings?
Your lap time will be submitted with any conditions or settings enabled. While I do understand that this creates a disparity with fuel load, weather, assists, tire wear or slipstreaming online, the process to check and account for all these variables would be extremely invasive and I am currently not considering it. For now, anything goes. Whoever gets the fastest lap time

What game data are you collecting?
The mod collects all data related to your in-game performance such as throttle, brake, speed, lap times, sectors e.t.c. While telemetry data are currently collected, they are not processed or stored because doing so would result in too much server cost. You can view all the data being collected if you examine the mod's python file.

What user data are you collecting?
The mod only collects steam GUID via the Steam api to uniquely identify drivers and the driver's name to display. No other personal data are collected such as email, IP address, location e.t.c. Even analytics are turned off in the website. An account is not needed to use the mod or view the leaderboard.

Project details
Frontend: React + TypeScript
Bundler: Vite
Backend: Postgres and serverless typescript.
Mod: Python for capturing, C++ for validation and uploads.
