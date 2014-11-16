6.4x Kerbol System for RSS
==========================
For Real Solar System.  Scales the stock Kerbin system up by a multiplier of 6.4

This is a bit more of a "gamey" RSS config.  When used with select Realism Overhaul (ROV) mods it will end up feeling a lot like stock KSP while giving you the RSS-style gameplay.  You'll need roughly 7.5km/s to get to Kerbin orbit.

Updated by Raptor831. Original work by regex. Additional work done by Paul Kingtiger. Includes Kerbin PQS adjustments by Lack and tweaks to KSC's position by White Owl.

This mod is public domain.


Installation Instructions
--------------------------------------------------------------------------------
1. Install RealSolarSystem.
2. Install RemoteTech if you want to use that mod
3. Copy the folders in this archive into the <KSP root>/GameData/ directory, allowing overwrite.
4. If you wish to use a 6-hour day or a 24-hour day, overwrite the RealSolarSystem.cfg with the file found in those folders. Discard them otherwise.

You should have overwritten 3 files in the RealSolarSystem folder and one file in the RemoteTech folder. They control the settings for scaling everything up to 6.4 times stock. The /64x/ folder contains ModuleManager configs to adjust other mods' settings to scale with 6.4x Kerbol System.


Recommended Mods:
--------------------------------------------------------------------------------
Deadly Reentry Continued
Ferram Aerospace Research
Real Fuels + Stockalike Engine Configs
Procedural Parts


Notes:
--------------------------------------------------------------------------------
- Kerbol is modelled after a K-type main sequence star (0.64sm, 0.84sr).
- Jool uses the density of Jupiter but is otherwise unchanged in physical characteristics (aside from upscaling).
- Every other body has its density fine-tuned to arrive at the gravity values of the stock game.
- Orbital period has been calculated from the orbital values of the bodies and will significantly differ from stock.
- Rotational period is calculated using tidal locking values or through some bullshit.  Kerbin has a 12-hour day.
- Any body with an atmosphere has its scale height and maximum altitude increased by 32%.
- Flying threshold for science is based on either the max atmospheric height or the radius of the body.
- Space threshold for science is based on the body's radius and whether it is a moon of another body.
- For the purposes of this file a moon is any body with an SMA < 5,000,000,000m.
- PQSMod_VertexHeightMap values are 1.5 times larger in deformity with offsets fudged to make oceans look proper.

Acknowledgements
--------------------------------------------------------------------------------
- This config was created by regex. I consider myself caretaker, so credit should go to regex, Lack, and White Owl.
- Paul Kingtiger, with his 64x package, updated this mod while I was away for a bit. Big thank you for that.
