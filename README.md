# KoboldAI Horde Overseer

KoboldAI Horde Overseer is a web UI for viewing every text worker and model on the [AI Horde](https://aihorde.net/), and for managing your own workers. This fork restyles the app in the UwU brand and adds a few fixes on top of the original.

**[Live version](https://horde.uwutismxd.uk/)** · [GitHub](https://github.com/UwUtismXD/KoboldHordeOverseer)

## What's new in this fork
- UwU look: deep space background, glass cards, the cyan → violet → pink gradient, and Space Grotesk / Inter / JetBrains Mono type. The theme is dark-only, so the old Dark/Light switch is gone.
- Your workers are highlighted in violet with a "Yours" badge on the worker grid once your API key is saved in Options.
- Manage Workers no longer repeats your workers each time it is opened and closed.
- All requests go to `aihorde.net`.

## Features
- User details (enter your API key in Options)
	- Kudos balance
	- Fulfilled requests
	- Contributed tokens
	- Online workers
- Horde totals
	- Total workers online
	- Total queued requests and tokens
	- Tokens requested in the past minute
- Individual worker details
	- Model
	- Max length and max context length
	- Requests fulfilled
	- Performance
	- Kudos rewarded, from generation and from uptime
	- Worker info
	- Trusted and maintenance status
- Models table with count, ETA, jobs, queue and tokens/s
- Kudos leaderboard (top 10)
- Sort workers alphabetically or by kudos, uptime, requests, context length or length
- Manage your workers
	- Edit worker info
	- Toggle maintenance mode
	- Delete a worker

## Running locally
It is a static site with no build step. Serve the folder with any web server, for example `python3 -m http.server`, and open `index.html`.

## Credits
- aqualxx for the original version.
- blazerrat for the repurposed version.
- [Logicism](https://github.com/LogicismDev/KoboldHordeOverseer) for the redesigned version this fork is based on.
- Henk717 and the KoboldAI Community.
- UwU restyle and fixes by [UwUtismXD](https://github.com/UwUtismXD).
