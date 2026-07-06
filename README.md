Catch Fleet

Collect the invisible world.

The sky above you is full of voices. Every airliner crossing your horizon
announces itself on 1090 MHz, to anyone who cares to listen. Catch Fleet is
a collection game about listening: you plug in a software-defined radio, run
a small Listener next to your decoder, and every aircraft your own antenna
catches fills your Dex.

It is deliberately not a flight tracker. Trackers show you everything,
instantly, and nothing feels earned. Here, only your own reception counts.
Every aircraft in your Dex physically flew through your sky, and your
station caught it.

🎟️ Alpha is open, seats limited: playcatchfleet.com
👀 Browse a live Dex from a real station: playcatchfleet.com/sedergine/dex
📖 Flight Manual (setup, honest requirements): playcatchfleet.com/manual

The repositories

RepoWhat it isgameThe open side of the game: design docs, catalog review decisions, type content, roadmap, and the public issue trackerlistenerThe small open-source bridge between your local ADS-B decoder (SBS1) and your Dex

Principles we build by


Real signal first. No manual catches, no trading, no pay-to-win.
Artificial progress never replaces real reception.
Honest uncertainty. Every identification carries a confidence label,
a source and a reason. Unknown aircraft become mystery signals, not
errors, and can resolve later without losing your catch.
Privacy by design. Raw frames never leave your machine; only bounded,
summarized observations are posted. Station coordinates are never public.
Hardware is part of the game. A ~$30 RTL-SDR with its stock antenna is
a perfectly good starting station, and upgrading your setup shows up
honestly in your collection.


Built in the open, by one ham and a lot of AI

Catch Fleet is designed and run by Meriç, TA3DIY,
an amateur radio operator, not a professional developer. The application code
is written almost entirely by AI coding agents and lives in a private
repository; what we keep open here is everything that shapes it — the design
notes, the milestone plans, the catalog review data with a documented
decision for every aircraft — plus the full source of the Listener that runs
on your machine. The game design and every product decision are human. Judge
for yourself.


73, and happy catching.
