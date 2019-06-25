# SUCC -- Shitty Unelegant Cross-group Communication

## What is this?

This is a stupid simple AI script for Arma 3 that makes the AI call for backup from nearby squads when engaged in combat. I wrote it years ago and decided that I should put it here before I lose it forever.

## Usage

1. Drop this poc in your mission folder
2. Edit initSucc.sqf to your tastes (the few things you should change are at the top)
3. Run initSucc.sqf in your mission, by eg. putting this in init.sqf: execVM "initSucc.sqf";
4. If you have units that are created after initSucc.sqf gets ran and want SUCC to work on them, you'll have to run `[this] execVM "succ.sqf"` on one of the group members (but never more than one!?)
5. Observe as your AI groups now (shittily) "communicate" with each other
