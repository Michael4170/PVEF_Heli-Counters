<img width="1920" height="1080" alt="PVEF_Heli_Counters_1920x1080" src="https://github.com/user-attachments/assets/72455dbc-4ee0-4207-b521-18b6890a16f5" />

Armed USSR helicopter counter-attacks, designed for PVEF. Vehicles can be setup in the server Json. Built as a companion to PVEF - PvE Framework.

ALPHA, for testing.

TWO TRIGGERS, EACH WITH ITS OWN CHANCE
- When the player faction starts capturing a base.
- When a base changes hands to them.
- Per-base overrides, so a base can be a certainty and another can stay quiet.

IT FLIES IN, THEN STAYS
- Spawns 1500-2500 m out, towards enemy ground. Never within 400 m of a player.
- Flies to the base marker and patrols a circuit over it.
- A gunner is added to the Mi-8MT's turret seat and engages players with its machine gun.
- Removed when its lifetime runs out.

ONE CONFIG FILE
- Written to your server profile on first run.
- Helicopter list with pick weights and per-trigger eligibility. Ships with the vanilla Mi-8MT armed gunship.
- Chances, delays, per-base cooldown, spawn distances, altitudes, patrol and engage radius, lifetime.

IT KNOWS WHEN TO SAY NO
- A cap on live helicopters.
- Skips while the server is near its AI limit.
- HQs are never targeted.
- Every skip is logged with the reason.

REQUIRED DEPENDENCY: REAPER_AiHelicopters - WCS by r34p3r. It supplies the AI pilot that flies the helicopter. Without it nothing flies. Thank you to r34p3r.
