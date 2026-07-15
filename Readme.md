Truice (AtherothCore)
=============

Truice is a database editor specifically made for TrinityCore. It is a fork of Quice, which was made for MaNGoS.

You can edit quests, creatures, gameobjects, items, loot, SmartAI (smart_scripts), conditions and some minor things.

It is written in Delphi, source on github compiled using Embarcadero Delphi 11 and the source is available under 
old https://github.com/Faq/Truice
fork https://github.com/chaosua/Truice
and precompiled binaries under 
Old https://github.com/Faq/Truice/releases
this fork updates https://github.com/chaosua/Truice/releases

**How To run:**
1. choose 32 bit or 64 and copy "libmysql.dll" and "Truice.exe" outside folder (where are all other folders: CSV, Lang etc.);
2. run "Truice.exe"
3. dll files are from MySQL v5.7.42 x32
4. if You got it right, then it should be like this:

<img src="images/torun.png" width="120" height="100">

**To compile use:** 
Delphi XE2+, current free Embarcadero® Delphi 12 CE:
Community Edition of Delphi what is completely free https://www.embarcadero.com/products/delphi/starter

and these additional components:

A) JEDI Visual Component Library 3.50
http://jvcl.delphi-jedi.org/
http://jvcl.sourceforge.net/daily/
http://github.com/project-jedi/jvcl

B) JEDI Code Library 2.8.0.5677
http://sourceforge.net/projects/jcl/
http://jcl.sourceforge.net/daily/
http://github.com/project-jedi/jcl

C) Droping ZeosLib to use Delphi internal db component FireDAC (from 22.08.2018).
ZeosDBO 7.3 from testing branch (SVN rev4068) (last commit with ZeosLib https://github.com/Faq/Truice/commit/3e74ac4aececd7b4c55b607ca9c3b63eb85f3a17)
http://sourceforge.net/projects/zeoslib/ (new link)
http://svn.code.sf.net/p/zeoslib/code-0

Installation not sure in order (package or installer first):
1.Install Delphi 12 CE
2.Download JCl/JVCL package JVCL350CompleteJCL28-Build9330.zip from https://github.com/project-jedi/jvcl/releases

3 Compile JCL packages and Installer
3.1 Run Delphi 12, and open from menu File-Open Project-> Navigate
 \JVCL350CompleteJCL28-Build9330\jcl\install\JediInstaller.dpoj
3.2 Build JCL Installer and Run it
3.3 Close Delphi 12 IDE, Accept MPL1.1 license, press Install button (JCL for Delphi 12 32/64bit)

3.4 Run Delphi 12, and open from menu File-Open Project-> Navigate 
\JVCL350CompleteJCL28-Build9330\jcl\packages\JclPackagesD290.groupproj
3.5 Select all folders in project tab , and right click menu - Build all
3.6 Select only "green ones" in project tab and right click menu - Install

4 Compile JVCL packages and Installer
4.1 Run Delphi 12, and open from menu File-Open Project-> Navigate
 \JVCL350CompleteJCL28-Build9330\jvcl\install\JVCLInstall\JVCLInstall.dproj
4.2 Build JCL Installer and Run it
4.3 Close Delphi 12 IDE, Accept MPL1.1 license, press Install button (JCL for Delphi 12 32/64bit)

4.4 Run Delphi 12, and open from menu File-Open Project-> Navigate 
 \JVCL350CompleteJCL28-Build9330\jvcl\packages\D29 Packages.groupproj 
(or D29_x64 Packages.groupproj for  x64 support aplications)
4.5 Select all folders in project tab , and right click menu - Build all
4.6 Select only "green ones" in project tab and right click menu - Install

**Original topic on AC forum:**
https://github.com/azerothcore/azerothcore-wotlk/discussions/18241

**Truice Download:**
https://github.com/chaosua/Truice/releases

<img src="images/creaturetemplate.png" width="200" height="200">
<img src="images/quest.png" width="200" height="200">
<img src="images/smartai.png" width="200" height="200">

Author: Faq, chaosua
