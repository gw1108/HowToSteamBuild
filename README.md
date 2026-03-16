# HowToSteamBuild

# Install steamworks_sdk_162:
https://partner.steamgames.com/doc/sdk

# Copy and paste scripts
Copy and paste the following scripts into steamworks_sdk_162\sdk\tools\ContentBuilder\scripts.

# Copy and paste files

Use the following folders for your primary content:

steamworks_sdk_162\sdk\tools\ContentBuilder\content\linux_content
steamworks_sdk_162\sdk\tools\ContentBuilder\content\windows64_content

# Build instructions
To build dungeon sweeper launch steamcmd.exe

login command.
login [STEAM_USERNAME] [PASSWORD]

command to upload build:

run_app_build C:\steamworks_sdk_162\sdk\tools\ContentBuilder\scripts\app_build_4109840.vdf

command to upload steam demo build:

run_app_build C:\steamworks_sdk_162\sdk\tools\ContentBuilder\scripts\app_build_4200300.vdf
