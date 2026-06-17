Starlink & SpaceX Data Dataset
205 launches, rocket specs & 3526 Starlink satellites with mission data

About Dataset
Complete SpaceX dataset including all 205 orbital launches with success/failure tracking, 4 rocket specifications, and 3526 Starlink satellite positions. Covers launch history, reusability analysis, payload data, and constellation mapping.



📁 Files
File	Rows	Description
spacex_launches.csv	205	All orbital launches with success and reusability data
spacex_rockets.csv	4	Rocket specifications and statistics
spacex_starlink.csv	3526	Starlink satellite orbital positions
📊 Launches columns
Column	Description
flight_number	Sequential flight number
name	Mission name
date_utc	Launch date and time (UTC)
rocket_id	Rocket ID
rocket_name	Rocket name (Falcon 9, Falcon Heavy, Starship)
launchpad_id	Launchpad ID
launchpad_name	Launchpad name (CCAFS, Boca Chica, etc.)
success	1 if launch succeeded, 0 otherwise
failures	Number of failures during launch
details	Mission details description
crew_count	Number of crew members
payloads_count	Number of payloads
cores_reused	Number of reused rocket cores
landing_success	1 if booster landing succeeded, 0 otherwise
landing_type	Landing type (RTLS, ASDS, Ocean, etc.)
📊 Rockets columns
Column	Description
id	Rocket ID
name	Rocket name
type	Rocket type (rocket, heavy-lift, super-heavy-lift)
active	1 if active, 0 if retired
stages	Number of stages
cost_per_launch	Cost per launch in USD
success_rate	Success rate percentage
first_flight	Date of first flight
height_m	Rocket height in meters
diameter_m	Rocket diameter in meters
mass_kg	Dry mass in kg
description	Technical description
📊 Starlink columns
Column	Description
id	Starlink satellite ID
spacetrack_id	NORAD spacetrack object ID
version	Starlink version/generation
launch_date	Launch date
longitude	Current orbital longitude
latitude	Current orbital latitude
height_km	Orbital height in km
velocity_kms	Orbital velocity in km/s
🔥 Ideas to Explore
🚀 Launch success prediction — what factors predict launch success?
♻️ Reusability analysis — how often are cores reused? Cost savings?
📈 Success rate trends — improving reliability over time?
💰 Cost analysis — historical cost trends and payload mass correlations
🎯 Booster landing success — which launchpads have best success rates?
🛰️ Starlink constellation analysis — orbital distribution and coverage?
📊 Rocket evolution — Falcon 9 upgrades and performance improvements
🌍 Launchpad utilization — which pads are most active?
👨‍🚀 Crew mission analysis — crewed vs uncrewed flight profiles
🎬 Mission timeline — gaps between launches, launch cadence
📦 Data Source
SpaceX API v4 — complete launch and vehicle data
Community-maintained, frequently updated
Data sourced from SpaceX official sources