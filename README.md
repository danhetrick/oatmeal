# oatmeal 0.51

*OpenArena Toolkit & Mod Environment for All*

For documentation regarding running or making mods for *OATMEAL*, please see [the manual](https://github.com/danhetrick/oatmeal/blob/master/bin/docs/oatmeal-0.51-manual.pdf).  This is a PDF file, and will require an external reader, such as "Adobe Acrobat Reader" for Windows, or "xpdf" for Linux.

**OATMEAL IS OPEN SOURCE**

*OATMEAL* is an open source modification for OpenArena.  The code is released under the GNU Public License v2 (just like OpenArena).  A copy of the GPL v2 can be found in "docs/LICENSE".

*OATMEAL* was originally written for Openarena 0.8.1.  It won't compile with the current version of Openarena 0.8.8.  Implementing the mod into the current version of OA shouldn't be too hard, I just don't really have the motivation to do it myself.

All code (unless otherwise noted) was written by Dan Hetrick.

Exceptions:

	Function:	G_LocationDamage()
	File:		g_combat.c
	Author:		Calrathan (calrathan@planetquake.com)
	Source:		Code3Arena

	Function:	homing_missile_think()
	File:		g_missile.c
	Author:		Chris Hilton (chris@dctank.com)
	Source:		Code3Arena

	Functions:	plasma_vortex_think()
			rocket_vortex_think()
			grenade_vortex_think()
			bfg_vortex_think()
			nailgun_vortex_think()
			proximity_mine_vortex_think()
	File:		g_missile.c
	Author:		AssKicka (email unknown)
	Source:		Code3Arena

	Function:	findradius()
	File:		g_utils.c
	Author:		Unknown
	Source:		Code3Arena
