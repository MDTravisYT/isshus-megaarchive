# Isshu's MegaArchive
A project aiming to compile every build of Pokémon Black &amp; White for every day of its development. All of these builds has been compiled by MDTravis, and will be actively updated as more gets done. Special thanks to starfrost and the TCRF Discord server!
## How to get things
You will need: 
- `wbmirror.tar.gz` or `swanmirror.tar.gz`
- A way to look into an SVN repository
- 7-Zip
- A way to patch a file using xdelta
1. Go to r2875, and obtain `effecteditor.srl` from `trunk/tools/effecteditor`.
2. (skip if doing Aug or Sep 2008) Choose the folder of the month you want to look at, and use 7-Zip to extract the **first** file to get the xdelta patch.
3. Using xdelta, use the patch file on `effecteditor.srl`.
4. Use 7-Zip to open up the newly patched file as an archive. You should see all the ROMs of the month you selected in that archive. **BEWARE!** They can extract to several GBs large!

An `.srl` file is identical to an `.nds` file, so emulators can open them up just fine. If your emulator isn't detecting it, rename the extension to `.nds`.
## Progress
- [ ] April 2008 builds (TBD)
- [ ] May 2008 builds (TBD)
- [ ] June 2008 builds (TBD)
- [ ] July 2008 builds (r1193 to r1227)
- [x] August 2008 builds (r1232 to r1344)
- [x] September 2008 builds (r1391 to r1493)
- [x] October 2008 builds (r1504 to r1670)
- [x] November 2008 builds (r1671 to r2037)
- [x] December 2008 builds (r2055 to r2319)
- [x] January 2009 builds (r2320 to r2523)
- [x] February 2009 builds (r2524 to r2752)
- [x] March 2009 builds (r2761 to r3145)
- [x] April 2009 builds (r3154 to r3470)
- [x] May 2009 builds (r3481 to r4467)
- [x] June 2009 builds (r4471 to r4822)
- [x] July 2009 builds (r4843 to r6610)
- [x] August 2009 builds (r6611 to r7253)
- [x] September 2009 builds (r7277 to r8390)
- [x] October 2009 builds (r8463 to r11254)
- [ ] November 2009 builds (r11256 to r13200)
- [ ] December 2009 builds (r13307 to r16466)
- [ ] January 2010 builds (r16475 to r18683)
- [ ] February 2010 builds (r18775 to r22602)
- [ ] March 2010 builds (r22727 to r27579)
- [ ] April 2010 builds (r27668 to r32672)
- [ ] May 2010 builds (r32817 to r38692)
- [ ] June 2010 builds (r38923 to r43729)
- [ ] July 2010 builds (r43838 to r44645)
- [ ] August 2010 builds (r44646 to r44688)
- [ ] September 2010 builds (r44689 to r44799)
