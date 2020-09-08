//Gadn filter - version 18.0
////BASICS
//Gold
ItemDisplay[GOLD<100 CLVL<20]:
ItemDisplay[GOLD<1000 (CLVL>19 AND CLVL<65)]:
ItemDisplay[GOLD<4000 CLVL>64]:
//HP & MPs
ItemDisplay[rvl]: %PURPLE%R %WHITE%70%
ItemDisplay[rvs]: %PURPLE%r %WHITE%35%
ItemDisplay[hp5]: %RED%!%WHITE%HP%RED%!%WHITE%
ItemDisplay[mp4]: %BLUE%!%WHITE%MP%BLUE%!%WHITE%
ItemDisplay[mp5]: %BLUE%!%WHITE%Mana%BLUE%!%WHITE%
ItemDisplay[hp1 CLVL<16]: %RED%!%WHITE%Minor Heal
ItemDisplay[hp2 CLVL<19]: %RED%!%WHITE%Light Heal
ItemDisplay[hp3 CLVL<25]: %RED%!%WHITE%Healing
ItemDisplay[hp4 CLVL<61]: %RED%!%WHITE%HP
ItemDisplay[mp1 CLVL<16]: %BLUE%!%WHITE%Minor Mana
ItemDisplay[mp2 CLVL<21]: %BLUE%!%WHITE%Light Mana
ItemDisplay[mp3 CLVL<27]: %BLUE%!%WHITE%Mana
ItemDisplay[(hp1 OR hp2 OR hp3 OR hp4) CLVL>0]:
ItemDisplay[(mp1 OR mp2 OR mp3) CLVL>0]:
//Essences (Respec Token)
ItemDisplay[tes]: %GOLD%Suffering [Andariel]
ItemDisplay[ceh]: %GOLD%Hatred [Mephisto]
ItemDisplay[bet]: %GOLD%Terror [Diablo]
ItemDisplay[fed]: %GOLD%Destruction [Baal]
ItemDisplay[toa]: %GOLD%Token of Absolution
//PoD Items
ItemDisplay[std]: %NAME%
ItemDisplay[cx5]: %PURPLE%Orb of Corruption
ItemDisplay[cx6]: %PURPLE%%NAME%
ItemDisplay[cx7]: %PURPLE%¤¤¤¤ KEY OF CHAOS ¤¤¤¤
//Maps
ItemDisplay[ma1 !ID]: %PURPLE%¤¤¤ %WHITE%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma2 !ID]: %PURPLE%¤¤¤ %RED%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma3 !ID]: %PURPLE%¤¤¤ %NAME% %PURPLE%¤¤¤
ItemDisplay[ma4 !ID]: %PURPLE%¤¤¤ %YELLOW%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma5 !ID]: %PURPLE%¤¤¤ %WHITE%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma6 !ID]: %PURPLE%¤¤¤ %RED%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma7 !ID]: %PURPLE%¤¤¤ %RED%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma8 !ID]: %PURPLE%¤¤¤ %YELLOW%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma9 !ID]: %PURPLE%¤¤¤ %YELLOW%%NAME% %PURPLE%¤¤¤
ItemDisplay[ma10 !ID]: %PURPLE%¤¤¤ %NAME% %PURPLE%¤¤¤
//ItemDisplay[(ma1 OR ma3 OR maz)]: %NAME%
//Dclone relic?
ItemDisplay[maz]: %PURPLE%%NAME%
//Looking for codes
ItemDisplay[maa]: %PURPLE%%NAME% %GOLD%[Report %CODE% to Gadn]
ItemDisplay[mab]: %PURPLE%%NAME% %GOLD%[Report %CODE% to Gadn]
ItemDisplay[NMAG (WP7 OR WP8) CLVL<81 SOCK>3]: %NAME% [%SOCKETS%]
//Uber Keys
ItemDisplay[pk1]: %GOLD%Terror %PURPLE%¤%GOLD%Countess%PURPLE%¤
ItemDisplay[pk2]: %GOLD%Hate %RED%¤%GOLD%Summoner%RED%¤
ItemDisplay[pk3]: %GOLD%Destruction %GREEN%¤%GOLD%Nihlathak%GREEN%¤
ItemDisplay[dhn]: %GOLD%Diablo's Horn
ItemDisplay[bey]: %GOLD%Baal's Eye
ItemDisplay[mbr]: %GOLD%Mephisto's Brain
//Scrolls
ItemDisplay[tsc CLVL<41]: %GREEN%!%WHITE%TP
ItemDisplay[isc CLVL<41]: %GREEN%!%WHITE%ID
ItemDisplay[(tsc OR isc) CLVL>0]:
//Tomes
ItemDisplay[tbk]: %WHITE%Tome of Town Portal
ItemDisplay[ibk]: %WHITE%Tome of Identify
//Utility pots
ItemDisplay[wms CLVL<61]: %GREEN%!%WHITE%Thaw
ItemDisplay[yps]: %GREEN%!%WHITE%A%GREEN%!%WHITE%
ItemDisplay[(wms OR yps) CLVL>0]:
//Chest Keys
ItemDisplay[key CLVL<61]: %GRAY%Key%WHITE%
//Choking(gpm), Exploding(opm), Fulminating(opl), Oil(ops), Rancid(gps), Strangling(gpl), Stamina(vps)
ItemDisplay[opl CLVL<15]: %NAME%
ItemDisplay[gpl CLVL<15]: %NAME%
ItemDisplay[vps CLVL<23]: %GREEN%!%WHITE%Stam
ItemDisplay[vps CLVL>0]:
//Quivers & Bolts
ItemDisplay[(aq2 OR cq2) RARE]: %NAME%
ItemDisplay[(aq2 OR cq2) MAG ILVL>66]:
//Quest items
ItemDisplay[bbb]: %TAN%%NAME%
ItemDisplay[ass]: %TAN%%NAME%
ItemDisplay[bkd]: %TAN%%NAME%
ItemDisplay[bks]: %TAN%%NAME%
ItemDisplay[box]: %TAN%%NAME%
ItemDisplay[g34]: %TAN%%NAME%
ItemDisplay[j34]: %TAN%%NAME%
ItemDisplay[mss]: %TAN%%NAME%
ItemDisplay[qbr]: %TAN%%NAME%
ItemDisplay[qey]: %TAN%%NAME%
ItemDisplay[qhr]: %TAN%%NAME%
ItemDisplay[tr1]: %TAN%%NAME%
ItemDisplay[tr2]: %TAN%%NAME%
ItemDisplay[xyz]: %TAN%%NAME%
ItemDisplay[ice]: %TAN%%NAME%
//Misc
ItemDisplay[leg]: %NAME%
ItemDisplay[ear]: %ORANGE%%NAME%
//All norm 1sock
ItemDisplay[NMAG SOCK=1]:
////RUNES
ItemDisplay[r01]: %TAN%EL [1] 
ItemDisplay[r02]: %TAN%ELD [2] 
ItemDisplay[r03]: %TAN%TIR [3] 
ItemDisplay[r04]: %TAN%NEF [4]
ItemDisplay[r05]: %TAN%ETH [5]
ItemDisplay[r06]: %TAN%ITH [6]
ItemDisplay[r07]: %TAN%TAL [7]
ItemDisplay[r08]: %ORANGE%RAL [8]
ItemDisplay[r09]: %TAN%ORT [9]
ItemDisplay[r10]: %TAN%THUL [10]
ItemDisplay[r11]: %TAN%AMN [11]
ItemDisplay[r12]: %ORANGE%SOL [12]
ItemDisplay[r13]: %TAN%SHAEL [13] 
ItemDisplay[r14]: %TAN%DOL [14] 
ItemDisplay[r15]: %ORANGE%HEL [15]
ItemDisplay[r16]: %TAN%IO [16] 
ItemDisplay[r17]: %ORANGE%LUM [17]
ItemDisplay[r18]: %ORANGE%KO [18]
ItemDisplay[r19]: %PURPLE%¤ FAL ¤[19]
ItemDisplay[r20]: %PURPLE%¤¤¤¤¤ %GREEN%LEM %PURPLE%¤¤¤¤¤[20]
ItemDisplay[r21]: %PURPLE%¤¤¤ %GREEN%PUL %PURPLE%¤¤¤[21]
ItemDisplay[r22]: %PURPLE%¤¤¤¤¤ %GREEN%UM %PURPLE%¤¤¤¤¤[22]
ItemDisplay[r23]: %PURPLE%¤¤¤¤¤¤¤ %GREEN%MAL %PURPLE%¤¤¤¤¤¤¤[23]
ItemDisplay[r24]: %PURPLE%¤¤¤¤¤¤¤¤¤¤ %GREEN%IST %PURPLE%¤¤¤¤¤¤¤¤¤¤[24]
ItemDisplay[r25]: %PURPLE%¤¤¤¤¤¤¤¤¤¤¤ %GREEN%GUL %PURPLE%¤¤¤¤¤¤¤¤¤¤¤[25]
ItemDisplay[r26]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%VEX %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[26]
ItemDisplay[r27]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%OHM %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[27]
ItemDisplay[r28]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%LO %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[28]
ItemDisplay[r29]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%SUR %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[29]
ItemDisplay[r30]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%BER %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[30]
ItemDisplay[r31]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%JAH %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[31]
ItemDisplay[r32]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%CHAM %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[32]
ItemDisplay[r33]: %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤ %GREEN%ZOD %PURPLE%¤¤¤¤¤¤%GREEN%¤¤¤¤¤%PURPLE%¤¤¤¤¤¤[33]
////GEMS
//Chipped
ItemDisplay[gcv CLVL<81]: %ORANGE%chipped a
ItemDisplay[gcw CLVL<81]: %ORANGE%chipped d
ItemDisplay[gcg CLVL<81]: %ORANGE%chipped e
ItemDisplay[gcr CLVL<81]: %ORANGE%chipped r
ItemDisplay[gcb CLVL<81]: %ORANGE%chipped sa
ItemDisplay[gcy CLVL<81]: %ORANGE%chipped t
ItemDisplay[skc CLVL<81]: %ORANGE%chipped sk
//Flawed
ItemDisplay[gfv CLVL<36]: %ORANGE%flawed a
ItemDisplay[gfw CLVL<36]: %ORANGE%flawed d
ItemDisplay[gfg CLVL<36]: %ORANGE%flawed e
ItemDisplay[gfr CLVL<36]: %ORANGE%flawed r
ItemDisplay[gfb CLVL<36]: %ORANGE%flawed sa
ItemDisplay[gfy CLVL<36]: %ORANGE%flawed t
ItemDisplay[skf CLVL<36]: %ORANGE%flawed sk
//Normal
ItemDisplay[gsv CLVL<41]: %ORANGE%amethyst
ItemDisplay[gsw CLVL<41]: %ORANGE%diamond
ItemDisplay[gsg CLVL<41]: %ORANGE%emerald
ItemDisplay[gsr CLVL<41]: %ORANGE%ruby
ItemDisplay[gsb CLVL<41]: %ORANGE%sapphire
ItemDisplay[gsy CLVL<41]: %ORANGE%topaz
ItemDisplay[sku CLVL<41]: %ORANGE%skull
//Flawless
ItemDisplay[gzv]: %ORANGE%Amethyst
ItemDisplay[glw]: %ORANGE%Diamond
ItemDisplay[glg]: %ORANGE%Emerald
ItemDisplay[glr]: %ORANGE%Ruby
ItemDisplay[glb]: %ORANGE%Sapphire
ItemDisplay[gly]: %ORANGE%Topaz
ItemDisplay[skl]: %ORANGE%Skull
//Perfect
ItemDisplay[gpv]: %ORANGE%Amethyst+
ItemDisplay[gpw]: %ORANGE%Diamond+
ItemDisplay[gpg]: %ORANGE%Emerald+
ItemDisplay[gpr]: %ORANGE%Ruby+
ItemDisplay[gpb]: %ORANGE%Sapphire+
ItemDisplay[gpy]: %ORANGE%Topaz+
ItemDisplay[skz]: %ORANGE%Skull+
ItemDisplay[(gcv OR gcw OR gcg OR gcr OR gcb OR gcy OR skc) CLVL>0]:
ItemDisplay[(gfv OR gfw OR gfg OR gfr OR gfb OR gfy OR skf) CLVL>0]:
ItemDisplay[(gsv OR gsw OR gsg OR gsr OR gsb OR gsy OR sku) CLVL>0]:
////***CUSTOM ITEMS***
ItemDisplay[INF !RW !WP12 !CL4 !CL6]:
////RARES
//The worthy ones
ItemDisplay[(7p7 OR 7wa OR 9cr OR 7cr OR 7s8 OR 7wc) RARE !ETH !ID]: %YELLOW%%NAME%
ItemDisplay[(WP12 OR EQ4 OR EQ5 OR EQ6) RARE ETH !ID]: %GRAY%ETH %YELLOW%%NAME%
//Circlets,Amulets,Rings,Jewels
ItemDisplay[EQ7 RARE !ETH !ID]: %YELLOW%¤¤¤ %NAME% ¤¤¤
ItemDisplay[EQ7 RARE ETH !ID]: %YELLOW%¤ %GRAY%ETH %YELLOW%%NAME% ¤
ItemDisplay[amu RARE !ID]: %YELLOW%¤¤¤ %NAME% ¤¤¤
ItemDisplay[rin RARE !ID]: %YELLOW%¤¤¤ %NAME% ¤¤¤
ItemDisplay[jew RARE !ID]: %YELLOW%¤¤¤ %NAME% ¤¤¤
//Class Specific
ItemDisplay[CL3 RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[CL3 RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[CL3 RARE !ETH !ID CLVL>85]: %YELLOW%%NAME%
ItemDisplay[CL3 RARE ETH !ID CLVL>85]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[(CL1 OR CL2 OR CL4 OR CL5 OR CL6 OR CL7) RARE !ETH !ID]: %YELLOW%%NAME%
ItemDisplay[(CL1 OR CL2 OR CL4 OR CL5 OR CL6 OR CL7) RARE ETH !ID]: %GRAY%ETH %YELLOW%%NAME%
//Wands,Gloves,Boots,Belts
ItemDisplay[(WP12 OR EQ4 OR EQ5 OR EQ6) RARE !ETH !ID]: %YELLOW%%NAME%
ItemDisplay[(WP12 OR EQ4 OR EQ5 OR EQ6) RARE ETH !ID]: %GRAY%ETH %YELLOW%%NAME%
//Helms
//ItemDisplay[(uap OR uhm OR usk OR urn OR uh9 OR xhm OR xsk OR xrn OR xh9) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
//ItemDisplay[(uap OR uhm OR usk OR urn OR uh9 OR xhm OR xsk OR xrn OR xh9) RARE !ETH !ID CLVL>85]:
//Axes
ItemDisplay[(7wa OR 9wa OR wax) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[(7wa OR 9wa OR wax) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[(7wa OR 9wa OR wax) RARE !ETH !ID CLVL>85]:
ItemDisplay[(7wa OR 9wa OR wax) RARE ETH !ID CLVL>85]:
//Maces
ItemDisplay[(7fl OR 7wh OR 9fl OR 9wh OR fla OR whm) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[(7fl OR 7wh OR 9fl OR 9wh OR fla OR whm) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[(7fl OR 7wh OR 9fl OR 9wh OR fla OR whm) RARE !ETH !ID CLVL>85]:
ItemDisplay[(7fl OR 7wh OR 9fl OR 9wh OR fla OR whm) RARE ETH !ID CLVL>85]:
//Sword
ItemDisplay[(7cr OR 9cr OR crs OR 7ls) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[(7cr OR 9cr OR crs OR 7ls) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[(7cr OR 9cr OR crs OR 7ls) RARE !ETH !ID CLVL>85]:
ItemDisplay[(7cr OR 9cr OR crs OR 7ls) RARE ETH !ID CLVL>85]:
//Scepters
ItemDisplay[(7ws OR 9ws OR wsp) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[(7ws OR 9ws OR wsp) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
ItemDisplay[(7ws OR 9ws OR wsp) RARE !ETH !ID CLVL>85]:
ItemDisplay[(7ws OR 9ws OR wsp) RARE ETH !ID CLVL>85]:
//Spear
//ItemDisplay[(7p7 OR 9p9 OR pik) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
//ItemDisplay[(7p7 OR 9p9 OR pik) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
//ItemDisplay[(7p7 OR 9p9 OR pik) RARE !ETH !ID CLVL>85]:
//ItemDisplay[(7p7 OR 9p9 OR pik) RARE ETH !ID CLVL>85]:
//Bows
ItemDisplay[(6hb OR 6l7 OR 6lw OR 8hb OR 8l8 OR 8lw OR hbw OR lbb OR lwb) RARE !ID CLVL<86]: %YELLOW%%NAME%
ItemDisplay[(6hb OR 6l7 OR 6lw OR 8hb OR 8l8 OR 8lw OR hbw OR lbb OR lwb) RARE !ID CLVL>85]:
//Crossbows
//ItemDisplay[(6hx OR 6rx OR 8hx OR 8rx OR hxb OR rxb) RARE !ID CLVL<86]: %YELLOW%%NAME%
//ItemDisplay[(6hx OR 6rx OR 8hx OR 8rx OR hxb OR rxb) RARE !ID CLVL>85]:
//Javelins
//ItemDisplay[(7ja OR 9ja OR jav) RARE !ETH !ID]: %YELLOW%%NAME%
//ItemDisplay[(7ja OR 9ja OR jav) RARE ETH !ID]: %GRAY%ETH %YELLOW%%NAME%
//Throwing
//ItemDisplay[(7tk OR 7bk OR 9tk OR 9bk OR tkf OR bkf) RARE !ETH !ID CLVL<86]: %YELLOW%%NAME%
//ItemDisplay[(7tk OR 7bk OR 9tk OR 9bk OR tkf OR bkf) RARE ETH !ID CLVL<86]: %GRAY%ETH %YELLOW%%NAME%
//ItemDisplay[(7tk OR 7bk OR 9tk OR 9bk OR tkf OR bkf) RARE !ETH !ID CLVL>85]:
//ItemDisplay[(7tk OR 7bk OR 9tk OR 9bk OR tkf OR bkf) RARE ETH !ID CLVL>85]:
//Normal rares
ItemDisplay[(ARMOR OR WEAPON) NORM RARE ILVL>0 ILVL<44 !ID]: %NAME%
//UNID'd rares
ItemDisplay[RARE !ID]:
////CHARMS
//Unique Charms
ItemDisplay[cm1 UNI !ID]: %PURPLE%¤¤¤¤¤ %GOLD%Annihilus %PURPLE%¤¤¤¤¤
ItemDisplay[cm2 UNI !ID]: %PURPLE%¤¤¤¤¤ %GOLD%Hellfire Torch %PURPLE%¤¤¤¤¤
ItemDisplay[cm3 UNI !ID]: %PURPLE%¤¤¤ %GOLD%Gheed's Fortune %PURPLE%¤¤¤
//Grand
ItemDisplay[cm3 MAG !ID ILVL>77]: %BLUE%¤ %NAME% %ORANGE%[L%ILVL%]%BLUE% ¤
ItemDisplay[cm3 MAG ILVL>77]: %NAME% %ORANGE%[L%ILVL%]
ItemDisplay[cm3 MAG !ID ILVL<78 ILVL>49]: %BLUE%¤ %NAME% %WHITE%[L%ILVL%]%BLUE% ¤
//Small
ItemDisplay[cm1 MAG !ID ILVL>89]: %BLUE%¤ %NAME% %ORANGE%[L%ILVL%]%BLUE% ¤
ItemDisplay[cm1 MAG !ID ILVL<90 ILVL>47]: %BLUE%¤ %NAME% %WHITE%[L%ILVL%]%BLUE% ¤
ItemDisplay[cm1 MAG !ID ILVL=47]: %BLUE%¤ %NAME% %ORANGE%[L%ILVL%]%BLUE% ¤
ItemDisplay[cm1 MAG ILVL=47]: %NAME% %ORANGE%[L%ILVL%]
ItemDisplay[cm1 MAG ILVL>89]: %NAME% %ORANGE%[L%ILVL%]
//Large
ItemDisplay[cm2]:
//
ItemDisplay[!UNI (cm1 OR cm2 OR cm3)]: %NAME%%WHITE% [L%ILVL%]
//Amulets
ItemDisplay[amu MAG ILVL=88]: %BLUE%%NAME%%ORANGE% [CLVL 92+]
ItemDisplay[amu MAG ILVL=89]: %BLUE%%NAME%%ORANGE% [CLVL 92+]
ItemDisplay[amu MAG ILVL=90]: %BLUE%%NAME%%ORANGE% [CLVL 90+]
ItemDisplay[amu MAG ILVL=91]: %BLUE%%NAME%%ORANGE% [CLVL 90+]
ItemDisplay[amu MAG ILVL=92]: %BLUE%%NAME%%ORANGE% [CLVL 88+]
ItemDisplay[amu MAG ILVL=93]: %BLUE%%NAME%%ORANGE% [CLVL 88+]
ItemDisplay[amu MAG ILVL=94]: %BLUE%%NAME%%ORANGE% [CLVL 86+]
ItemDisplay[amu MAG ILVL=95]: %BLUE%%NAME%%ORANGE% [CLVL 86+]
ItemDisplay[amu MAG ILVL=96]: %BLUE%%NAME%%ORANGE% [CLVL 84+]
ItemDisplay[amu MAG ILVL=97]: %BLUE%%NAME%%ORANGE% [CLVL 84+]
ItemDisplay[amu MAG ILVL=98]: %BLUE%%NAME%%ORANGE% [CLVL 82+]
ItemDisplay[amu MAG ILVL=99]: %BLUE%%NAME%%ORANGE% [CLVL 82+]
ItemDisplay[amu MAG ILVL<88]: %BLUE%%NAME%%WHITE% [L%ILVL%]
//Rings
//ItemDisplay[rin MAG ILVL=86]: %BLUE%%NAME%%ORANGE% [CLVL 84+]
//ItemDisplay[rin MAG ILVL=87]: %BLUE%%NAME%%ORANGE% [CLVL 84+]
//ItemDisplay[rin MAG ILVL=88]: %BLUE%%NAME%%ORANGE% [CLVL 82+]
//ItemDisplay[rin MAG ILVL=89]: %BLUE%%NAME%%ORANGE% [CLVL 82+]
//ItemDisplay[rin MAG ILVL=90]: %BLUE%%NAME%%ORANGE% [CLVL 80+]
//ItemDisplay[rin MAG ILVL=91]: %BLUE%%NAME%%ORANGE% [CLVL 78+]
//ItemDisplay[rin MAG ILVL=92]: %BLUE%%NAME%%ORANGE% [CLVL 78+]
//ItemDisplay[rin MAG ILVL=93]: %BLUE%%NAME%%ORANGE% [CLVL 76+]
//ItemDisplay[rin MAG ILVL=94]: %BLUE%%NAME%%ORANGE% [CLVL 76+]
//ItemDisplay[rin MAG ILVL>94]: %BLUE%%NAME%%ORANGE% [CLVL 74+]
//ItemDisplay[rin MAG ILVL<86]: %BLUE%%NAME%%WHITE% [L%ILVL%]
//Jewels
ItemDisplay[MAG !ID jew]: %BLUE%¤ %NAME% ¤
ItemDisplay[MAG jew]: %BLUE%%NAME%%WHITE% [L%ILVL%]
////UNIQUE ITEMS
//EQ1/EQ7 HELMS+CIRCLETS
//Biggin's Bonnet
ItemDisplay[cap UNI !ID !ETH]: %TAN%Biggin's Bonnet
ItemDisplay[cap UNI !ID ETH]: %GRAY%ETH %TAN%Biggin's Bonnet
//Tarnhelm
ItemDisplay[skp UNI !ID !ETH]: %TAN%¤ Tarnhelm ¤
ItemDisplay[skp UNI !ID ETH]: %GRAY%ETH %TAN%Tarnhelm
//Coif of Glory
//ItemDisplay[hlm UNI !ID !ETH]: %TAN%Coif of Glory
//ItemDisplay[hlm UNI !ID ETH]: %GRAY%ETH %TAN%Coif of Glory
//Duskdeep
//ItemDisplay[fhl UNI !ID !ETH]: %TAN%Duskdeep
//ItemDisplay[fhl UNI !ID ETH]: %GRAY%ETH %TAN%Duskdeep
//Howltusk
//ItemDisplay[ghm UNI !ID !ETH]: %TAN%Howltusk
//ItemDisplay[ghm UNI !ID ETH]: %GRAY%ETH %TAN%Howltusk
//The Face of Horror
//ItemDisplay[msk UNI !ID !ETH]: %TAN%The Face of Horror
//ItemDisplay[msk UNI !ID ETH]: %GRAY%ETH %TAN%The Face of Horror
//Undead Crown
//ItemDisplay[crn UNI !ID !ETH]: %TAN%Undead Crown
//ItemDisplay[crn UNI !ID ETH]: %GRAY%ETH %TAN%Undead Crown
//Wormskull
//ItemDisplay[bhm UNI !ID !ETH]: %TAN%Wormskull
//ItemDisplay[bhm UNI !ID ETH]: %GRAY%ETH %TAN%Wormskull
//Peasant Crown
//ItemDisplay[xap UNI !ID !ETH]: %TAN%¤ Peasant Crown ¤
//ItemDisplay[xap UNI !ID ETH]: %GRAY%ETH %TAN%Peasant Crown
//Rockstopper
ItemDisplay[xkp UNI !ID !ETH]: %TAN%¤ Rockstopper ¤
ItemDisplay[xkp UNI !ID ETH]: %GRAY%ETH %TAN%¤ Rockstopper ¤
//Stealskull
//ItemDisplay[xlm UNI !ID !ETH]: %TAN%¤ Stealskull ¤
//ItemDisplay[xlm UNI !ID ETH]: %GRAY%ETH %TAN%Stealskull
//Darksight Helm
//ItemDisplay[xhl UNI !ID !ETH]: %TAN%Darksight Helm
//ItemDisplay[xhl UNI !ID ETH]: %GRAY%ETH %TAN%Darksight Helm
//Valkyrie Wing
ItemDisplay[xhm UNI !ID !ETH]: %TAN%¤ Valkyrie Wing ¤
ItemDisplay[xhm UNI !ID ETH]: %GRAY%ETH %TAN%Valkyrie Wing
//Blackhorn's Face
//ItemDisplay[xsk UNI !ID !ETH]: %TAN% Blackhorn's Face
//ItemDisplay[xsk UNI !ID ETH]: %GRAY%ETH %TAN%Blackhorn's Face
//Crown of Thieves
//ItemDisplay[xrn UNI !ID !ETH]: %TAN%¤ Crown of Thieves ¤
//ItemDisplay[xrn UNI !ID ETH]: %GRAY%ETH %RED%Crown of Thieves
//Vampire Gaze
ItemDisplay[xh9 UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Vampire Gaze %RED%¤¤¤
ItemDisplay[xh9 UNI !ID ETH]: %RED%¤¤¤ %GRAY%ETH %PURPLE%Vampire Gaze %RED%¤¤¤
//Shako
ItemDisplay[uap UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Shako %RED%¤¤¤
ItemDisplay[uap UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Shako ¤
//Steel Shade
ItemDisplay[ulm UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Steel Shade %RED%¤¤¤
ItemDisplay[ulm UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Steel Shade ¤
//Veil of Steel or Nightwing's Veil
ItemDisplay[uhm UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Veil of Steel or Nightwing's Veil %RED%¤¤¤
ItemDisplay[uhm UNI !ID ETH]: %GRAY%ETH %TAN%¤ Veil of Steel or %GRAY%ETH %TAN%Nightwing's Veil ¤
//Andariel's Visage
ItemDisplay[usk UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Andariel's Visage %RED%¤¤¤
ItemDisplay[usk UNI !ID ETH]: %RED%¤¤¤ %GRAY%ETH %PURPLE%Andariel's Visage %RED%¤¤¤
//Crown of Ages
ItemDisplay[urn UNI !ID !ETH]: %RED%¤¤ Crown of Ages ¤¤
ItemDisplay[urn UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Crown of Ages %RED%¤
//Giant Skull
ItemDisplay[uh9 UNI !ID !ETH]: %TAN%¤ Giant Skull ¤
ItemDisplay[uh9 UNI !ID ETH]: %GRAY%ETH %RED%Giant Skull
//Griffon's Eye
ItemDisplay[ci3 UNI !ID !ETH]: %RED%¤¤¤ %PURPLE% Griffon's Eye %RED%¤¤¤
ItemDisplay[ci3 UNI !ID ETH]: %GRAY%ETH %TAN%¤ Griffon's Eye ¤
//Kira's Guardian
ItemDisplay[ci2 UNI !ID !ETH]: %RED%¤¤ Kira's Guardian ¤¤
ItemDisplay[ci2 UNI !ID ETH]: %GRAY%ETH %RED%Kira's Guardian
////EQ2 ARMOR
//Greyform
//ItemDisplay[qui UNI !ID !ETH]: %TAN%Greyform
//ItemDisplay[qui UNI !ID ETH]: %GRAY%ETH %TAN%Greyform
//Blinkbat's Form
//ItemDisplay[lea UNI !ID !ETH]: %TAN%Blinkbat's Form
//ItemDisplay[lea UNI !ID ETH]: %GRAY%ETH %TAN%Blinkbat's Form
//The Centurion
//ItemDisplay[hla UNI !ID !ETH]: %TAN%The Centurion
//ItemDisplay[hla UNI !ID ETH]: %GRAY%ETH %TAN%The Centurion
//Twitchthroe
ItemDisplay[stu UNI !ID !ETH]: %TAN%Twitchthroe
ItemDisplay[stu UNI !ID ETH]: %GRAY%ETH %TAN%Twitchthroe
//Darkglow
//ItemDisplay[rng UNI !ID !ETH]: %TAN%Darkglow
//ItemDisplay[rng UNI !ID ETH]: %GRAY%ETH %TAN%Darkglow
//Hawkmail
//ItemDisplay[scl UNI !ID !ETH]: %TAN%Hawkmail
//ItemDisplay[scl UNI !ID ETH]: %GRAY%ETH %TAN%Hawkmail
//Venom Ward
//ItemDisplay[brs UNI !ID !ETH]: %TAN%Venom Ward
//ItemDisplay[brs UNI !ID ETH]: %GRAY%ETH %TAN%Venom Ward
//Sparking Mail
//ItemDisplay[chn UNI !ID !ETH]: %TAN%Sparking Mail
//ItemDisplay[chn UNI !ID ETH]: %GRAY%ETH %TAN%Sparking Mail
//Iceblink
//ItemDisplay[spl UNI !ID !ETH]: %TAN%Iceblink
//ItemDisplay[spl UNI !ID ETH]: %GRAY%ETH %TAN%Iceblink
//Heavenly Garb
//ItemDisplay[ltp UNI !ID !ETH]: %TAN%Heavenly Garb
//ItemDisplay[ltp UNI !ID ETH]: %GRAY%ETH %TAN%Heavenly Garb
//Rockfleece
//ItemDisplay[fld UNI !ID !ETH]: %TAN%Rockfleece
//ItemDisplay[fld UNI !ID ETH]: %GRAY%ETH %TAN%Rockfleece
//Boneflesh
//ItemDisplay[plt UNI !ID !ETH]: %TAN%Boneflesh
//ItemDisplay[plt UNI !ID ETH]: %GRAY%ETH %TAN%Boneflesh
//Rattlecage
//ItemDisplay[gth UNI !ID !ETH]: %TAN%Rattlecage
//ItemDisplay[gth UNI !ID ETH]: %GRAY%ETH %TAN%Rattlecage
//Goldskin
//ItemDisplay[ful UNI !ID !ETH]: %TAN%Goldskin
//ItemDisplay[ful UNI !ID ETH]: %GRAY%ETH %TAN%Goldskin
//Silks of the Victor
//ItemDisplay[aar UNI !ID !ETH]: %TAN%Silks of the Victor
//ItemDisplay[aar UNI !ID ETH]: %GRAY%ETH %TAN%Silks of the Victor
//The Spirit Shroud
//ItemDisplay[xui UNI !ID !ETH]: %TAN%The Spirit Shroud
//ItemDisplay[xui UNI !ID ETH]: %GRAY%ETH %TAN%The Spirit Shroud
//Skin of the Vipermagi
ItemDisplay[xea UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Skin of the Vipermagi %RED%¤¤¤
ItemDisplay[xea UNI !ID ETH]: %GRAY%ETH %PURPLE%Skin of the Vipermagi
//Skin of the Flayed One
//ItemDisplay[xla UNI !ID !ETH]: %TAN%Skin of the Flayed One
//ItemDisplay[xla UNI !ID ETH]: %GRAY%ETH %TAN%Skin of the Flayed One
//Iron Pelt
//ItemDisplay[xtu UNI !ID !ETH]: %TAN%Iron Pelt
//ItemDisplay[xtu UNI !ID ETH]: %GRAY%ETH %TAN%Iron Pelt
//Crow Caw
//ItemDisplay[xcl UNI !ID !ETH]: %TAN%Crow Caw
//ItemDisplay[xcl UNI !ID ETH]: %GRAY%ETH %TAN%Crow Caw
//Spirit Forge
//ItemDisplay[xng UNI !ID !ETH]: %TAN%Spirit Forge
//ItemDisplay[xng UNI !ID ETH]: %GRAY%ETH %TAN%Spirit Forge
//Duriel's Shell
ItemDisplay[xrs UNI !ID !ETH]: %RED%¤ Duriel's Shell ¤
ItemDisplay[xrs UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Duriel's Shell ¤
//Shaftstop 
ItemDisplay[xhn UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Shaftstop %RED%¤¤¤
ItemDisplay[xhn UNI !ID ETH]: %RED%¤¤¤ %GRAY%ETH %PURPLE%Shaftstop %RED%¤¤¤
//Skullder's Ire
ItemDisplay[xpl UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Skullder's Ire %RED%¤¤¤
ItemDisplay[xpl UNI !ID ETH]: %RED%¤¤¤ %GRAY%ETH %PURPLE%Skullder's Ire %RED%¤¤¤
//Que-Hegan's Wisdom
//ItemDisplay[xtp UNI !ID !ETH]: %RED%¤¤ Que-Hegan's Wisdom ¤¤
//ItemDisplay[xtp UNI !ID ETH]: %GRAY%ETH %RED%Que-Hegan's Wisdom
//Toothrow
//ItemDisplay[xld UNI !ID !ETH]: %TAN%Toothrow
//ItemDisplay[xld UNI !ID ETH]: %GRAY%ETH %TAN%Toothrow
//Guardian Angel
ItemDisplay[xlt UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Guardian Angel %RED%¤¤¤
ItemDisplay[xlt UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Guardian Angel ¤
//Atma's Wail
//ItemDisplay[xth UNI !ID !ETH]: %TAN%Atma's Wail
//ItemDisplay[xth UNI !ID ETH]: %GRAY%ETH %TAN%Atma's Wail
//Black Hades
//ItemDisplay[xul UNI !ID !ETH]: %TAN%Black Hades
//ItemDisplay[xul UNI !ID ETH]: %GRAY%ETH %TAN%Black Hades
//Corpsemourn
//ItemDisplay[xar UNI !ID !ETH]: %TAN%Corpsemourn
//ItemDisplay[xar UNI !ID ETH]: %GRAY%ETH %TAN%Corpsemourn
//Ormus' Robes
ItemDisplay[uui UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Ormus' Robes %RED%¤¤¤
ItemDisplay[uui UNI !ID ETH]: %GRAY%ETH %RED%Ormus' Robes
//The Gladiator's Bane
ItemDisplay[utu UNI !ID !ETH]: %TAN%¤ The Gladiator's Bane ¤
ItemDisplay[utu UNI !ID ETH]: %GRAY%ETH %TAN%¤ The Gladiator's Bane ¤
//Arkaine's Valor
ItemDisplay[upl UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Arkaine's Valor %RED%¤¤¤
ItemDisplay[upl UNI !ID ETH]: %GRAY%ETH %RED%Arkaine's Valor
//Leviathan
ItemDisplay[uld UNI !ID !ETH]: %RED%¤ Leviathan ¤
ItemDisplay[uld UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Leviathan ¤
//Steel Carapace
ItemDisplay[uul UNI !ID !ETH]: %TAN%Steel Carapace
ItemDisplay[uul UNI !ID ETH]: %GRAY%ETH %TAN%Steel Carapace
//Tyrael's Might
ItemDisplay[uar UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Tyrael's Might or Templar's Might %RED%¤¤¤
ItemDisplay[uar UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %PURPLE%Tyrael's Might or Templar's Might %RED%¤¤
////EQ3 SHIELDS
//Pelta Lunata
//ItemDisplay[buc UNI !ID !ETH]: %TAN%Pelta Lunata
//ItemDisplay[buc UNI !ID ETH]: %GRAY%ETH %TAN%Pelta Lunata
//Umbral Disk
//ItemDisplay[sml UNI !ID !ETH]: %TAN%Umbral Disk
//ItemDisplay[sml UNI !ID ETH]: %GRAY%ETH %TAN%Umbral Disk
//Stormguild
//ItemDisplay[lrg UNI !ID !ETH]: %TAN%Stormguild
//ItemDisplay[lrg UNI !ID ETH]: %GRAY%ETH %TAN%Stormguild
//Steelclash
//ItemDisplay[kit UNI !ID !ETH]: %TAN%Steelclash
//ItemDisplay[kit UNI !ID ETH]: %GRAY%ETH %TAN%Steelclash
//Swordback Hold
//ItemDisplay[spk UNI !ID !ETH]: %TAN%Swordback Hold
//ItemDisplay[spk UNI !ID ETH]: %GRAY%ETH %TAN%Swordback Hold
//Bverrit Keep
//ItemDisplay[tow UNI !ID !ETH]: %TAN%Bverrit Keep
//ItemDisplay[tow UNI !ID ETH]: %GRAY%ETH %TAN%Bverrit Keep
//Wall of the Eyeless
//ItemDisplay[bsh UNI !ID !ETH]: %TAN%Wall of the Eyeless
//ItemDisplay[bsh UNI !ID ETH]: %GRAY%ETH %TAN%Wall of the Eyeless
//The Ward
//ItemDisplay[gts UNI !ID !ETH]: %TAN%¤ The Ward ¤
//ItemDisplay[gts UNI !ID ETH]: %GRAY%ETH %TAN%The Ward
//Visceratuant
//ItemDisplay[xuc UNI !ID !ETH]: %TAN%Visceratuant
//ItemDisplay[xuc UNI !ID ETH]: %GRAY%ETH %TAN%Visceratuant
//Moser's Blessed Circle
ItemDisplay[xml UNI !ID !ETH]: %TAN%¤ Moser's Blessed Circle ¤
ItemDisplay[xml UNI !ID ETH]: %GRAY%ETH %TAN%Moser's Blessed Circle
//Stormchaser
//ItemDisplay[xrg UNI !ID !ETH]: %TAN%Stormchaser
//ItemDisplay[xrg UNI !ID ETH]: %GRAY%ETH %TAN%Stormchaser
//Tiamat's Rebuke
//ItemDisplay[xit UNI !ID !ETH]: %TAN%Tiamat's Rebuke
//ItemDisplay[xit UNI !ID ETH]: %GRAY%ETH %TAN%Tiamat's Rebuke
//Lance Guard
//ItemDisplay[xpk UNI !ID !ETH]: %TAN%Lance Guard
//ItemDisplay[xpk UNI !ID ETH]: %GRAY%ETH %TAN%Lance Guard
//Gerke's Sanctuary
//ItemDisplay[xow UNI !ID !ETH]: %TAN%¤ Gerke's Sanctuary ¤
//ItemDisplay[xow UNI !ID ETH]: %GRAY%ETH %TAN%Gerke's Sanctuary
//Lidless Wall
ItemDisplay[xsh UNI !ID !ETH]: %RED%¤ Lidless Wall ¤
ItemDisplay[xsh UNI !ID ETH]: %GRAY%ETH %TAN%Lidless Wall
//Radament's Sphere
ItemDisplay[xts UNI !ID !ETH]: %RED%¤ Radament's Sphere ¤
ItemDisplay[xts UNI !ID ETH]: %GRAY%ETH %TAN%Radament's Sphere
//Blackoak Shield
//ItemDisplay[uml UNI !ID !ETH]: %TAN%Blackoak Shield
//ItemDisplay[uml UNI !ID ETH]: %GRAY%ETH %TAN%Blackoak Shield
//Stormshield
ItemDisplay[uit UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Stormshield %RED%¤¤¤
ItemDisplay[uit UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %PURPLE%Stormshield %RED%¤¤
//Spike Thorn
//ItemDisplay[upk UNI !ID !ETH]: %TAN%Spike Thorn
//ItemDisplay[upk UNI !ID ETH]: %GRAY%ETH %TAN%Spike Thorn
//Medusa's Gaze
ItemDisplay[uow UNI !ID !ETH]: %RED%¤¤¤ Medusa's Gaze %RED%¤¤¤
ItemDisplay[uow UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Medusa's Gaze ¤
//Head Hunter's Glory
ItemDisplay[ush UNI !ID !ETH]: %TAN%¤ Head Hunter's Glory ¤
ItemDisplay[ush UNI !ID ETH]: %GRAY%ETH %TAN%Head Hunter's Glory
//Spirit Ward
ItemDisplay[uts UNI !ID !ETH]: %TAN%Spirit Ward
ItemDisplay[uts UNI !ID ETH]: %GRAY%ETH %TAN%Spirit Ward
////EQ4 GLOVES
//The Hand of Broc
//ItemDisplay[lgl UNI !ID !ETH]: %TAN%The Hand of Broc
//ItemDisplay[lgl UNI !ID ETH]: %GRAY%ETH %TAN%The Hand of Broc
//Bloodfist
//ItemDisplay[vgl UNI !ID !ETH]: %TAN%¤ Bloodfist ¤
//ItemDisplay[vgl UNI !ID ETH]: %GRAY%ETH %TAN%Bloodfist
//Chance Guards
//ItemDisplay[mgl UNI !ID !ETH]: %RED%¤ Chance Guards ¤
//ItemDisplay[mgl UNI !ID ETH]: %GRAY%ETH %TAN%Chance Guards
//Magefist
ItemDisplay[tgl UNI !ID !ETH]: %RED%¤¤ Magefist ¤¤
ItemDisplay[tgl UNI !ID ETH]: %GRAY%ETH %TAN%Magefist
//Frostburn
ItemDisplay[hgl UNI !ID !ETH]: %RED%¤¤ Frostburn ¤¤
ItemDisplay[hgl UNI !ID ETH]: %GRAY%ETH %TAN%Frostburn
//Venom Grip
//ItemDisplay[xlg UNI !ID !ETH]: %TAN%Venom Grip
//ItemDisplay[xlg UNI !ID ETH]: %GRAY%ETH %TAN%Venom Grip
//Gravepalm
//ItemDisplay[xvg UNI !ID !ETH]: %TAN%Gravepalm
//ItemDisplay[xvg UNI !ID ETH]: %GRAY%ETH %TAN%Gravepalm
//Ghoulhide
//ItemDisplay[xmg UNI !ID !ETH]: %TAN%Ghoulhide
//ItemDisplay[xmg UNI !ID ETH]: %GRAY%ETH %TAN%Ghoulhide
//Lava Gout
ItemDisplay[xtg UNI !ID !ETH]: %TAN%Lava Gout
ItemDisplay[xtg UNI !ID ETH]: %GRAY%ETH %TAN%Lava Gout
//Hellmouth
//ItemDisplay[xhg UNI !ID !ETH]: %TAN%Hellmouth
//ItemDisplay[xhg UNI !ID ETH]: %GRAY%ETH %TAN%Hellmouth
//Dracul's Grasp
ItemDisplay[uvg UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Dracul's Grasp %RED%¤¤¤
ItemDisplay[uvg UNI !ID ETH]: %GRAY%ETH %PURPLE%Dracul's Grasp
//Soul Drainer
ItemDisplay[umg UNI !ID !ETH]: %TAN%¤ Soul Drainer
ItemDisplay[umg UNI !ID ETH]: %GRAY%ETH %TAN%Soul Drainer
//Steelrend
ItemDisplay[uhg UNI !ID !ETH]: %TAN%¤ Steelrend ¤
ItemDisplay[uhg UNI !ID ETH]: %GRAY%ETH %TAN%Steelrend
////EQ5 BOOTS
//Hotspur
ItemDisplay[lbt UNI !ID !ETH]: %TAN%¤ Hotspur ¤
ItemDisplay[lbt UNI !ID ETH]: %GRAY%ETH %TAN%Hotspur
//Gorefoot
//ItemDisplay[vbt UNI !ID !ETH]: %TAN%Gorefoot
//ItemDisplay[vbt UNI !ID ETH]: %GRAY%ETH %TAN%Gorefoot
//Treads of Cthon
//ItemDisplay[mbt UNI !ID !ETH]: %TAN%Treads of Cthon
//ItemDisplay[mbt UNI !ID ETH]: %GRAY%ETH %TAN%Treads of Cthon
//Goblin Toe
//ItemDisplay[tbt UNI !ID !ETH]: %TAN%Goblin Toe
//ItemDisplay[tbt UNI !ID ETH]: %GRAY%ETH %TAN%Goblin Toe
//Tearhaunch
//ItemDisplay[hbt UNI !ID !ETH]: %TAN%Tearhaunch
//ItemDisplay[hbt UNI !ID ETH]: %GRAY%ETH %TAN%Tearhaunch
//Infernostride
//ItemDisplay[xlb UNI !ID !ETH]: %TAN%Infernostride
//ItemDisplay[xlb UNI !ID ETH]: %GRAY%ETH %TAN%Infernostride
//Waterwalk
ItemDisplay[xvb UNI !ID !ETH]: %RED%¤¤ Waterwalk ¤¤
ItemDisplay[xvb UNI !ID ETH]: %GRAY%ETH %TAN%Waterwalk
//Silkweave
ItemDisplay[xmb UNI !ID !ETH]: %RED%¤¤ %PURPLE%Silkweave %RED%¤¤
ItemDisplay[xmb UNI !ID ETH]: %GRAY%ETH %TAN%Silkweave
//War Traveler
ItemDisplay[xtb UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%War Traveler %RED%¤¤¤
ItemDisplay[xtb UNI !ID ETH]: %GRAY%ETH %PURPLE%War Traveler
//Gore Rider
ItemDisplay[xhb UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Gore Rider %RED%¤¤¤
ItemDisplay[xhb UNI !ID ETH]: %GRAY%ETH %TAN%Gore Rider
//Sandstorm Trek
ItemDisplay[uvb UNI !ID !ETH]: %RED%¤¤ Sandstorm Trek ¤¤
ItemDisplay[uvb UNI !ID ETH]: %GRAY%ETH %RED%Sandstorm Trek
//Marrowwalk
//ItemDisplay[umb UNI !ID !ETH]: %RED%¤¤ Marrowwalk ¤¤
//ItemDisplay[umb UNI !ID ETH]: %GRAY%ETH %TAN%Marrowwalk
//Shadow Dancer
ItemDisplay[uhb UNI !ID !ETH]: %RED%¤¤ Shadow Dancer ¤¤
ItemDisplay[uhb UNI !ID ETH]: %GRAY%ETH %TAN%Shadow Dancer
////EQ6 BELTS
//Lenymo
ItemDisplay[lbl UNI !ID !ETH]: %TAN%Lenymo %RED%¤
ItemDisplay[lbl UNI !ID ETH]: %GRAY%ETH %TAN%Lenymo
//Snakecord
//ItemDisplay[vbl UNI !ID !ETH]: %TAN%Snakecord
//ItemDisplay[vbl UNI !ID ETH]: %GRAY%ETH %TAN%Snakecord
//Nightsmoke
//ItemDisplay[mbl UNI !ID !ETH]: %TAN%Nightsmoke
//ItemDisplay[mbl UNI !ID ETH]: %GRAY%ETH %TAN%Nightsmoke
//Goldwrap
//ItemDisplay[tbl UNI !ID !ETH]: %TAN%¤ Goldwrap ¤
//ItemDisplay[tbl UNI !ID ETH]: %GRAY%ETH %TAN%Goldwrap
//Bladebuckle
//ItemDisplay[hbl UNI !ID !ETH]: %TAN%Bladebuckle
//ItemDisplay[hbl UNI !ID ETH]: %GRAY%ETH %TAN%Bladebuckle
//String of Ears
ItemDisplay[zlb UNI !ID !ETH]: %RED%¤¤ String of Ears ¤¤
ItemDisplay[zlb UNI !ID ETH]: %GRAY%ETH %RED%String of Ears
//Razortail
ItemDisplay[zvb UNI !ID !ETH]: %RED%¤¤ Razortail ¤¤
ItemDisplay[zvb UNI !ID ETH]: %GRAY%ETH %RED%Razortail
//Gloom's Trap
//ItemDisplay[zmb UNI !ID !ETH]: %TAN%¤ Gloom's Trap ¤
//ItemDisplay[zmb UNI !ID ETH]: %GRAY%ETH %TAN%Gloom's Trap
//Snowclash
//ItemDisplay[ztb UNI !ID !ETH]: %TAN%¤ Snowclash ¤
//ItemDisplay[ztb UNI !ID ETH]: %GRAY%ETH %RED%Snowclash
//Thundergod's Vigor
ItemDisplay[zhb UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Thundergod's Vigor %RED%¤¤¤
ItemDisplay[zhb UNI !ID ETH]: %GRAY%ETH %PURPLE%Thundergod's Vigor
//Arachnid Mesh
ItemDisplay[ulc UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Arachnid Mesh %RED%¤¤¤
ItemDisplay[ulc UNI !ID ETH]: %GRAY%ETH %PURPLE%Arachnid Mesh
//Nosferatu's Coil
//ItemDisplay[uvc UNI !ID !ETH]: %TAN%Nosferatu's Coil
//ItemDisplay[uvc UNI !ID ETH]: %GRAY%ETH %TAN%Nosferatu's Coil
//Verdungo's Hearty Cord
ItemDisplay[umc UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Verdungo's Hearty Cord %RED%¤¤¤
ItemDisplay[umc UNI !ID ETH]: %GRAY%ETH %PURPLE%Verdungo's Hearty Cord
////UNIQUE WEAPONS
///WP1 AXES
//The Gnasher
//ItemDisplay[hax UNI !ID !ETH]: %TAN%The Gnasher
//ItemDisplay[hax UNI !ID ETH]: %GRAY%ETH %TAN%The Gnasher
//Deathspade
//ItemDisplay[axe UNI !ID !ETH]: %TAN%Deathspade
//ItemDisplay[axe UNI !ID ETH]: %GRAY%ETH %TAN%Deathspade
//Bladebone
//ItemDisplay[2ax UNI !ID !ETH]: %TAN%Bladebone
//ItemDisplay[2ax UNI !ID ETH]: %GRAY%ETH %TAN%Bladebone
//Skull Splitter
//ItemDisplay[mpi UNI !ID !ETH]: %TAN%Skull Splitter
//ItemDisplay[mpi UNI !ID ETH]: %GRAY%ETH %TAN%Skull Splitter
//Rakescar
//ItemDisplay[wax UNI !ID !ETH]: %TAN%Rakescar
//ItemDisplay[wax UNI !ID ETH]: %GRAY%ETH %TAN%Rakescar
//Axe of Feckmar
//ItemDisplay[lax UNI !ID !ETH]: %TAN%Axe of Feckmar
//ItemDisplay[lax UNI !ID ETH]: %GRAY%ETH %TAN%Axe of Feckmar
//Goreshovel
//ItemDisplay[bax UNI !ID !ETH]: %TAN%Goreshovel
//ItemDisplay[bax UNI !ID ETH]: %GRAY%ETH %TAN%Goreshovel
//The Chieftain
//ItemDisplay[btx UNI !ID !ETH]: %TAN%The Chieftain
//ItemDisplay[btx UNI !ID ETH]: %GRAY%ETH %TAN%The Chieftain
//Brainhew
//ItemDisplay[gax UNI !ID !ETH]: %TAN%Brainhew
//ItemDisplay[gax UNI !ID ETH]: %GRAY%ETH %TAN%Brainhew
//Humongous
//ItemDisplay[gix UNI !ID !ETH]: %TAN%Humongous
//ItemDisplay[gix UNI !ID ETH]: %GRAY%ETH %TAN%Humongous
//Coldkill
//ItemDisplay[9ha UNI !ID !ETH]: %TAN%Coldkill
//ItemDisplay[9ha UNI !ID ETH]: %GRAY%ETH %TAN%Coldkill
//Butcher's Pupil
//ItemDisplay[9ax UNI !ID !ETH]: %TAN%Butcher's Pupil
//ItemDisplay[9ax UNI !ID ETH]: %GRAY%ETH %RED%Butcher's Pupil
//Islestrike
//ItemDisplay[92a UNI !ID !ETH]: %TAN%Islestrike
//ItemDisplay[92a UNI !ID ETH]: %GRAY%ETH %TAN%Islestrike
//Pompeii's Wrath
//ItemDisplay[9mp UNI !ID !ETH]: %TAN%¤¤ Pompeii's Wrath ¤¤
//ItemDisplay[9mp UNI !ID ETH]: %GRAY%ETH %TAN%Pompeii's Wrath
//Guardian Naga
//ItemDisplay[9wa UNI !ID !ETH]: %TAN%Guardian Naga
//ItemDisplay[9wa UNI !ID ETH]: %GRAY%ETH %TAN%Guardian Naga
//Warlord's Trust
//ItemDisplay[9la UNI !ID !ETH]: %TAN%Warlord's Trust
//ItemDisplay[9la UNI !ID ETH]: %GRAY%ETH %TAN%Warlord's Trust
//Spellsteel
//ItemDisplay[9ba UNI !ID !ETH]: %RED%Spellsteel ¤
//ItemDisplay[9ba UNI !ID ETH]: %GRAY%ETH %TAN%Spellsteel
//Stormrider
ItemDisplay[9bt UNI !ID !ETH]: %TAN%Stormrider
ItemDisplay[9bt UNI !ID ETH]: %GRAY%ETH %TAN%Stormrider
//Boneslayer Blade
ItemDisplay[9ga UNI !ID !ETH]: %TAN%Boneslayer Blade
ItemDisplay[9ga UNI !ID ETH]: %GRAY%ETH %TAN%Boneslayer Blade
//The Minotaur
ItemDisplay[9gi UNI !ID !ETH]: %TAN%The Minotaur
ItemDisplay[9gi UNI !ID ETH]: %GRAY%ETH %TAN%The Minotaur
//Razor's Edge
ItemDisplay[7ha UNI !ID !ETH]: %TAN%Razor's Edge
ItemDisplay[7ha UNI !ID ETH]: %GRAY%ETH %TAN%Razor's Edge
//Rune Master
ItemDisplay[72a UNI !ID !ETH]: %TAN%Rune Master
ItemDisplay[72a UNI !ID ETH]: %GRAY%ETH %RED%Rune Master
//Cranebeak
ItemDisplay[7mp UNI !ID !ETH]: %TAN%Cranebeak
ItemDisplay[7mp UNI !ID ETH]: %GRAY%ETH %TAN%Cranebeak
//Death Cleaver
ItemDisplay[7wa UNI !ID !ETH]: %RED%¤¤¤ %PURPLE% Death Cleaver %RED%¤¤¤
ItemDisplay[7wa UNI !ID ETH]: %GRAY%ETH %PURPLE%Death Cleaver
//Ethereal Edge (always Eth)
ItemDisplay[7ba UNI !ID ETH]: %TAN%ETH Ethereal Edge
//Hellslayer
ItemDisplay[7bt UNI !ID !ETH]: %TAN%Hellslayer
ItemDisplay[7bt UNI !ID ETH]: %GRAY%ETH %TAN%Hellslayer
//Messerschmidt's Reaver
ItemDisplay[7ga UNI !ID !ETH]: %TAN%Messerschmidt's Reaver
ItemDisplay[7ga UNI !ID ETH]: %GRAY%ETH %TAN%Messerschmidt's Reaver
//Executioner's Justice
ItemDisplay[7gi UNI !ID !ETH]: %RED%¤ Executioner's Justice ¤
ItemDisplay[7gi UNI !ID ETH]: %GRAY%ETH %RED%Executioner's Justice
////WP2 MACES
//Felloak
//ItemDisplay[clb UNI !ID !ETH]: %TAN%Felloak
//ItemDisplay[clb UNI !ID ETH]: %GRAY%ETH %TAN%Felloak
//Stoutnail
//ItemDisplay[spc UNI !ID !ETH]: %TAN%Stoutnail
//ItemDisplay[spc UNI !ID ETH]: %GRAY%ETH %TAN%Stoutnail
//Crushflange
//ItemDisplay[mac UNI !ID !ETH]: %TAN%Crushflange
//ItemDisplay[mac UNI !ID ETH]: %GRAY%ETH %TAN%Crushflange
//Bloodrise
//ItemDisplay[mst UNI !ID !ETH]: %TAN%Bloodrise
//ItemDisplay[mst UNI !ID ETH]: %GRAY%ETH %TAN%Bloodrise
//The General's Tan Do Li Ga
//ItemDisplay[fla UNI !ID !ETH]: %TAN%The General's Tan Do Li Ga
//ItemDisplay[fla UNI !ID ETH]: %GRAY%ETH %TAN%The General's Tan Do Li Ga
//Ironstone
//ItemDisplay[whm UNI !ID !ETH]: %TAN%Ironstone
//ItemDisplay[whm UNI !ID ETH]: %GRAY%ETH %TAN%Ironstone
//Bonesnap
//ItemDisplay[mau UNI !ID !ETH]: %TAN%¤ Bonesnap ¤
//ItemDisplay[mau UNI !ID ETH]: %GRAY%ETH %TAN%Bonesnap
//Steeldriver
//ItemDisplay[gma UNI !ID !ETH]: %TAN%Steeldriver
//ItemDisplay[gma UNI !ID ETH]: %GRAY%ETH %TAN%Steeldriver
//Dark Clan Crusher
//ItemDisplay[9cl UNI !ID !ETH]: %TAN%Dark Clan Crusher
//ItemDisplay[9cl UNI !ID ETH]: %GRAY%ETH %TAN%Dark Clan Crusher
//Fleshrender
//ItemDisplay[9sp UNI !ID !ETH]: %TAN%Fleshrender
//ItemDisplay[9sp UNI !ID ETH]: %GRAY%ETH %TAN%Fleshrender
//Sureshrill Frost
//ItemDisplay[9ma UNI !ID !ETH]: %TAN%Sureshrill Frost
//ItemDisplay[9ma UNI !ID ETH]: %GRAY%ETH %TAN%Sureshrill Frost
//Moonfall
//ItemDisplay[9mt UNI !ID !ETH]: %TAN%Moonfall
//ItemDisplay[9mt UNI !ID ETH]: %GRAY%ETH %TAN%Moonfall
//Baezil's Vortex
//ItemDisplay[9fl UNI !ID !ETH]: %TAN%Baezil's Vortex
//ItemDisplay[9fl UNI !ID ETH]: %GRAY%ETH %TAN%Baezil's Vortex
//Earthshaker
//ItemDisplay[9wh UNI !ID !ETH]: %TAN%Earthshaker
//ItemDisplay[9wh UNI !ID ETH]: %GRAY%ETH %TAN%Earthshaker
//Bloodtree Stump
//ItemDisplay[9m9 UNI !ID !ETH]: %TAN%Bloodtree Stump
//ItemDisplay[9m9 UNI !ID ETH]: %GRAY%ETH %TAN%Bloodtree Stump
//The Gavel of Pain
//ItemDisplay[9gm UNI !ID !ETH]: %TAN%The Gavel of Pain
//ItemDisplay[9gm UNI !ID ETH]: %GRAY%ETH %RED%The Gavel of Pain
//Nord's Tenderizer
//ItemDisplay[7cl UNI !ID !ETH]: %TAN%Nord's Tenderizer
//ItemDisplay[7cl UNI !ID ETH]: %GRAY%ETH %TAN%Nord's Tenderizer
//Demon Limb
//ItemDisplay[7sp UNI !ID !ETH]: %RED%Demon Limb ¤
//ItemDisplay[7sp UNI !ID ETH]: %GRAY%ETH %RED%Demon Limb
//Baranar's Star
//ItemDisplay[7mt UNI !ID !ETH]: %TAN%Baranar's Star
//ItemDisplay[7mt UNI !ID ETH]: %GRAY%ETH %TAN%Baranar's Star
//Horizon's Tornado or Stormlash
ItemDisplay[7fl UNI !ID !ETH]: %RED%¤¤ Horizon's Tornado or Stormlash ¤¤
ItemDisplay[7fl UNI !ID ETH]: %GRAY%ETH %RED%Horizon's Tornado or %GRAY%ETH %RED%Stormlash
//Stone Crusher or Schaefer's Hammer
ItemDisplay[7wh UNI !ID !ETH]: %RED%¤¤ Stone Crusher or Schaefer's Hammer ¤¤
ItemDisplay[7wh UNI !ID ETH]: %GRAY%ETH %RED%Stone Crusher or %GRAY%ETH %RED%Schaefer's Hammer
//Windhammer
ItemDisplay[7m7 UNI !ID !ETH]: %TAN%Windhammer
ItemDisplay[7m7 UNI !ID ETH]: %GRAY%ETH %TAN%Windhammer
//Earth Shifter or The Cranium Basher
//ItemDisplay[7gm UNI !ID !ETH]: %RED%¤¤¤ %PURPLE% Earth Shifter or The Cranium Basher %RED%¤¤¤
//ItemDisplay[7gm UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %PURPLE%Earth Shifter or %GRAY%ETH %PURPLE%The Cranium Basher %RED%¤¤
ItemDisplay[7gm UNI !ID !ETH]: %RED%¤¤¤ %PURPLE% Senpai Needs Cranium Bashers %RED%¤¤¤
ItemDisplay[7gm UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %PURPLE%Senpai Needs Cranium Bashers %RED%¤¤
////WP3 SWORDS
//Rixot's Keen
//ItemDisplay[ssd UNI !ID !ETH]: %TAN%Rixot's Keen
//ItemDisplay[ssd UNI !ID ETH]: %GRAY%ETH %TAN%Rixot's Keen
//Blood Crescent
//ItemDisplay[scm UNI !ID !ETH]: %TAN%Blood Crescent
//ItemDisplay[scm UNI !ID ETH]: %GRAY%ETH %TAN%Blood Crescent
//Skewer of Krintiz
//ItemDisplay[sbr UNI !ID !ETH]: %TAN%Skewer of Krintiz
//ItemDisplay[sbr UNI !ID ETH]: %GRAY%ETH %TAN%Skewer of Krintiz
//Gleamscythe
//ItemDisplay[flc UNI !ID !ETH]: %TAN%Gleamscythe
//ItemDisplay[flc UNI !ID ETH]: %GRAY%ETH %TAN%Gleamscythe
//Griswold's Edge
//ItemDisplay[bsd UNI !ID !ETH]: %TAN%Griswold's Edge
//ItemDisplay[bsd UNI !ID ETH]: %GRAY%ETH %TAN%Griswold's Edge
//Hellplague
//ItemDisplay[lsd UNI !ID !ETH]: %TAN%Hellplague
//ItemDisplay[lsd UNI !ID ETH]: %GRAY%ETH %TAN%Hellplague
//Culwen's Point
//ItemDisplay[wsd UNI !ID !ETH]: %TAN%Culwen's Point
//ItemDisplay[wsd UNI !ID ETH]: %GRAY%ETH %TAN%Culwen's Point
//Shadowfang
//ItemDisplay[2hs UNI !ID !ETH]: %TAN%Shadowfang
//ItemDisplay[2hs UNI !ID ETH]: %GRAY%ETH %TAN%Shadowfang
//Soulflay
//ItemDisplay[clm UNI !ID !ETH]: %TAN%Soulflay
//ItemDisplay[clm UNI !ID ETH]: %GRAY%ETH %TAN%Soulflay
//Kinemil's Awl
//ItemDisplay[gis UNI !ID !ETH]: %TAN%Kinemil's Awl
//ItemDisplay[gis UNI !ID ETH]: %GRAY%ETH %TAN%Kinemil's Awl
//Blacktongue
//ItemDisplay[bsw UNI !ID !ETH]: %TAN%Blacktongue
//ItemDisplay[bsw UNI !ID ETH]: %GRAY%ETH %TAN%Blacktongue
//Ripsaw
//ItemDisplay[flb UNI !ID !ETH]: %TAN%Ripsaw
//ItemDisplay[flb UNI !ID ETH]: %GRAY%ETH %TAN%Ripsaw
//The Patriarch
//ItemDisplay[gsd UNI !ID !ETH]: %TAN%The Patriarch
//ItemDisplay[gsd UNI !ID ETH]: %GRAY%ETH %TAN%The Patriarch
//Bloodletter
//ItemDisplay[9ss UNI !ID !ETH]: %TAN%Bloodletter
//ItemDisplay[9ss UNI !ID ETH]: %GRAY%ETH %TAN%Bloodletter
//Coldsteel Eye
//ItemDisplay[9sm UNI !ID !ETH]: %TAN%Coldsteel Eye
//ItemDisplay[9sm UNI !ID ETH]: %GRAY%ETH %TAN%Coldsteel Eye
//Hexfire
//ItemDisplay[9sb UNI !ID !ETH]: %TAN%¤ Hexfire ¤
//ItemDisplay[9sb UNI !ID ETH]: %TAN%¤ %GRAY%ETH %TAN%Hexfire ¤
//Blade of Ali Baba
//ItemDisplay[9fc UNI !ID !ETH]: %RED%¤ Blade of Ali Baba ¤
//ItemDisplay[9fc UNI !ID ETH]: %GRAY%ETH %TAN%Blade of Ali Baba
//Ginther's Rift
//ItemDisplay[9cr UNI !ID !ETH]: %TAN%Ginther's Rift
//ItemDisplay[9cr UNI !ID ETH]: %GRAY%ETH %RED%Ginther's Rift
//Headstriker
ItemDisplay[9bs UNI !ID !ETH]: %RED%¤ Headstriker %RED%¤
ItemDisplay[9bs UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Headstriker ¤
//Plague Bearer
//ItemDisplay[9ls UNI !ID !ETH]: %TAN%¤ Plague Bearer ¤
//ItemDisplay[9ls UNI !ID ETH]: %GRAY%ETH %TAN%Plague Bearer
//The Atlantean
//ItemDisplay[9wd UNI !ID !ETH]: %TAN%The Atlantean
//ItemDisplay[9wd UNI !ID ETH]: %GRAY%ETH %TAN%The Atlantean
//Crainte Vomir
//ItemDisplay[92h UNI !ID !ETH]: %TAN%Crainte Vomir
//ItemDisplay[92h UNI !ID ETH]: %GRAY%ETH %TAN%Crainte Vomir
//Bing Sz Wang
//ItemDisplay[9cm UNI !ID !ETH]: %RED%Bing Sz Wang
//ItemDisplay[9cm UNI !ID ETH]: %GRAY%ETH %TAN%Bing Sz Wang
//The Vile Husk
//ItemDisplay[9gs UNI !ID !ETH]: %TAN%The Vile Husk
//ItemDisplay[9gs UNI !ID ETH]: %GRAY%ETH %TAN%The Vile Husk
//Cloudcrack
//ItemDisplay[9b9 UNI !ID !ETH]: %TAN%Cloudcrack
//ItemDisplay[9b9 UNI !ID ETH]: %GRAY%ETH %TAN%Cloudcrack
//Todesfaelle Flamme
//ItemDisplay[9fb UNI !ID !ETH]: %TAN%Todesfaelle Flamme
//ItemDisplay[9fb UNI !ID ETH]: %GRAY%ETH %TAN%Todesfaelle Flamme
//Swordguard
//ItemDisplay[9gd UNI !ID !ETH]: %TAN%Swordguard
//ItemDisplay[9gd UNI !ID ETH]: %GRAY%ETH %TAN%Swordguard
//Djinn Slayer
//ItemDisplay[7sm UNI !ID !ETH]: %TAN%Djinn Slayer
//ItemDisplay[7sm UNI !ID ETH]: %GRAY%ETH %TAN%Djinn Slayer
//Bloodmoon
//ItemDisplay[7sb UNI !ID !ETH]: %TAN%Bloodmoon
//ItemDisplay[7sb UNI !ID ETH]: %GRAY%ETH %TAN%Bloodmoon
//Lightsabre or Azurewrath
ItemDisplay[7cr UNI !ID]: %RED%¤¤¤ %PURPLE%Lightsabre or Azurewrath %RED%¤¤¤
//Frostwind
ItemDisplay[7ls UNI !ID !ETH]: %TAN%Frostwind
ItemDisplay[7ls UNI !ID ETH]: %GRAY%ETH %TAN%Frostwind
//Flamebellow
//ItemDisplay[7gs UNI !ID !ETH]: %TAN%Flamebellow
//ItemDisplay[7gs UNI !ID ETH]: %GRAY%ETH %TAN%Flamebellow
//Doombringer
//ItemDisplay[7b7 UNI !ID !ETH]: %TAN%Doombringer
//ItemDisplay[7b7 UNI !ID ETH]: %GRAY%ETH %TAN%Doombringer
//The Grandfather
ItemDisplay[7gd UNI !ID !ETH]: %RED%¤¤ The Grandfather ¤¤
ItemDisplay[7gd UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%The Grandfather ¤
////WP4 DAGGERS
//Gull
ItemDisplay[dgr UNI !ID !ETH]: %RED%¤ Gull ¤
ItemDisplay[dgr UNI !ID ETH]: %GRAY%ETH %TAN%Gull
//The Diggler
//ItemDisplay[dir UNI !ID !ETH]: %TAN%The Diggler
//ItemDisplay[dir UNI !ID ETH]: %GRAY%ETH %TAN%The Diggler
//The Jade Tan Do
//ItemDisplay[kri UNI !ID !ETH]: %TAN%The Jade Tan Do
//ItemDisplay[kri UNI !ID ETH]: %GRAY%ETH %TAN%The Jade Tan Do
//Spectral Shard
//ItemDisplay[bld UNI !ID !ETH]: %TAN%Spectral Shard
//ItemDisplay[bld UNI !ID ETH]: %GRAY%ETH %TAN%Spectral Shard
//Spineripper
//ItemDisplay[9dg UNI !ID !ETH]: %TAN%Spineripper
//ItemDisplay[9dg UNI !ID ETH]: %GRAY%ETH %TAN%Spineripper
//Heart Carver
//ItemDisplay[9di UNI !ID !ETH]: %TAN%Heart Carver
//ItemDisplay[9di UNI !ID ETH]: %GRAY%ETH %TAN%Heart Carver
//Blackbog's Sharp
//ItemDisplay[9kr UNI !ID !ETH]: %TAN%Blackbog's Sharp
//ItemDisplay[9kr UNI !ID ETH]: %GRAY%ETH %TAN%Blackbog's Sharp
//Stormspike
//ItemDisplay[9bl UNI !ID !ETH]: %TAN%Stormspike
//ItemDisplay[9bl UNI !ID ETH]: %GRAY%ETH %TAN%Stormspike
//Wizardspike
//ItemDisplay[7dg UNI !ID !ETH]: %TAN%¤ Wizardspike ¤
//ItemDisplay[7dg UNI !ID ETH]: %TAN%¤ %GRAY%ETH %TAN%Wizardspike ¤
//Fleshripper
ItemDisplay[7kr UNI !ID !ETH]: %RED%¤¤ Fleshripper ¤¤
ItemDisplay[7kr UNI !ID ETH]: %GRAY%ETH %RED%Fleshripper
//ETH Ghostflame (always eth)
ItemDisplay[7bl UNI !ID ETH]: %TAN%Ghostflame
////WP5 THROWING WEAPONS
//Deathbit
//ItemDisplay[9tk UNI !ID !ETH]: %TAN%Deathbit
//ItemDisplay[9tk UNI !ID ETH]: %RED%¤ %GRAY%ETH Deathbit %RED%¤
//The Scalper
//ItemDisplay[9ta UNI !ID !ETH]: %TAN%The Scalper
//ItemDisplay[9ta UNI !ID ETH]: %RED%¤ %GRAY%ETH The Scalper %RED%¤
//Warshrike
ItemDisplay[7bk UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Warshrike %RED%¤¤¤
ItemDisplay[7bk UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Warshrike %RED%¤
//Gimmershred
//ItemDisplay[7ta UNI !ID !ETH]: %TAN%Gimmershred
//ItemDisplay[7ta UNI !ID ETH]: %GRAY%ETH %TAN%Gimmershred
//Lacerator
//ItemDisplay[7b8 UNI !ID !ETH]: %RED%¤ Lacerator ¤
//ItemDisplay[7b8 UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Lacerator %RED%¤
////WP6 JAVELINS
//Demon's Arch
//ItemDisplay[7s7 UNI !ID !ETH]: %TAN%Demon's Arch
//ItemDisplay[7s7 UNI !ID ETH]: %GRAY%ETH %TAN% Demon's Arch
//Wraith Flight (always ETH)
//ItemDisplay[7gl UNI !ID ETH]: %GRAY%ETH %TAN%Wraith Flight
//Gargoyle's Bite
//ItemDisplay[7ts UNI !ID !ETH]: %TAN%Gargoyle's Bite
//ItemDisplay[7ts UNI !ID ETH]: %GRAY%ETH %TAN%Gargoyle's Bite
////WP7 SPEARS
//The Dragon Chang
//ItemDisplay[spr UNI !ID !ETH]: %TAN%The Dragon Chang
//ItemDisplay[spr UNI !ID ETH]: %GRAY%ETH %TAN%The Dragon Chang
//Razortine
//ItemDisplay[tri UNI !ID !ETH]: %TAN%Razortine
//ItemDisplay[tri UNI !ID ETH]: %GRAY%ETH %TAN%Razortine
//Bloodthief
//ItemDisplay[brn UNI !ID !ETH]: %TAN%Bloodthief
//ItemDisplay[brn UNI !ID ETH]: %GRAY%ETH %TAN%Bloodthief
//Lance of Yaggai
//ItemDisplay[spt UNI !ID !ETH]: %TAN%Lance of Yaggai
//ItemDisplay[spt UNI !ID ETH]: %GRAY%ETH %TAN%Lance of Yaggai
//The Tannr Gorerod
//ItemDisplay[pik UNI !ID !ETH]: %TAN%The Tannr Gorerod
//ItemDisplay[pik UNI !ID ETH]: %GRAY%ETH %TAN%The Tannr Gorerod
//The Impaler
//ItemDisplay[9sr UNI !ID !ETH]: %TAN%The Impaler
//ItemDisplay[9sr UNI !ID ETH]: %GRAY%ETH %TAN%The Impaler
//Kelpie Snare
//ItemDisplay[9tr UNI !ID !ETH]: %TAN%Kelpie Snare
//ItemDisplay[9tr UNI !ID ETH]: %GRAY%ETH %TAN%Kelpie Snare 
//Soulfeast Time
//ItemDisplay[9br UNI !ID !ETH]: %TAN%Soulfeast Time
//ItemDisplay[9br UNI !ID ETH]: %GRAY%ETH %TAN%Soulfeast Time
//Hone Sundan
//ItemDisplay[9st UNI !ID !ETH]: %TAN%Hone Sundan
//ItemDisplay[9st UNI !ID ETH]: %GRAY%ETH %TAN%Hone Sundan
//Spire of Honor
//ItemDisplay[9p9 UNI !ID !ETH]: %TAN%Spire of Honor
//ItemDisplay[9p9 UNI !ID ETH]: %GRAY%ETH %TAN%Spire of Honor
//Arioc's Needle
//ItemDisplay[7sr UNI !ID !ETH]: %TAN%Arioc's Needle
//ItemDisplay[7sr UNI !ID ETH]: %GRAY%ETH %TAN%Arioc's Needle
//Viperfork
//ItemDisplay[7br UNI !ID !ETH]: %TAN%Viperfork 
//ItemDisplay[7br UNI !ID ETH]: %GRAY%ETH %TAN%Viperfork 
//Steel Pillar
//ItemDisplay[7p7 UNI !ID !ETH]: %TAN%Steel Pillar
//ItemDisplay[7p7 UNI !ID ETH]: %GRAY%ETH %TAN%Steel Pillar
////WP8 POLEARMS
//Dimoak's Hew
//ItemDisplay[bar UNI !ID !ETH]: %TAN%Dimoak's Hew
//ItemDisplay[bar UNI !ID ETH]: %GRAY%ETH %TAN%Dimoak's Hew
//Steelgoad
//ItemDisplay[vou UNI !ID !ETH]: %TAN%Steelgoad
//ItemDisplay[vou UNI !ID ETH]: %GRAY%ETH %TAN%Steelgoad
//Soul Harvest
//ItemDisplay[scy UNI !ID !ETH]: %TAN%Soul Harvest
//ItemDisplay[scy UNI !ID ETH]: %GRAY%ETH %TAN%Soul Harvest
//The Battlebranch
//ItemDisplay[pax UNI !ID !ETH]: %TAN%The Battlebranch
//ItemDisplay[pax UNI !ID ETH]: %GRAY%ETH %TAN%The Battlebranch
//Woestave
//ItemDisplay[hal UNI !ID !ETH]: %TAN%Woestave
//ItemDisplay[hal UNI !ID ETH]: %GRAY%ETH %TAN%Woestave
//The Grim Reaper
//ItemDisplay[wsc UNI !ID !ETH]: %TAN%The Grim Reaper
//ItemDisplay[wsc UNI !ID ETH]: %GRAY%ETH %TAN%The Grim Reaper
//The Meat Scraper
//ItemDisplay[9b7 UNI !ID !ETH]: %TAN%The Meat Scraper
//ItemDisplay[9b7 UNI !ID ETH]: %GRAY%ETH %TAN%The Meat Scraper
//Blackleach Blade
//ItemDisplay[9vo UNI !ID !ETH]: %TAN%Blackleach Blade
//ItemDisplay[9vo UNI !ID ETH]: %GRAY%ETH %TAN%Blackleach Blade
//Athena's Wrath
//ItemDisplay[9s8 UNI !ID !ETH]: %TAN%Athena's Wrath
//ItemDisplay[9s8 UNI !ID ETH]: %GRAY%ETH %TAN%Athena's Wrath
//Pierre Tombale Couant
//ItemDisplay[9pa UNI !ID !ETH]: %TAN%Pierre Tombale Couant
//ItemDisplay[9pa UNI !ID ETH]: %GRAY%ETH %TAN%Pierre Tombale Couant
//Husoldal Evo
//ItemDisplay[9h9 UNI !ID !ETH]: %TAN%Husoldal Evo
//ItemDisplay[9h9 UNI !ID ETH]: %GRAY%ETH %TAN%Husoldal Evo
//Grim's Burning Dead
//ItemDisplay[9wc UNI !ID !ETH]: %TAN%Grim's Burning Dead
//ItemDisplay[9wc UNI !ID ETH]: %GRAY%ETH %TAN%Grim's Burning Dead
//Bonehew
ItemDisplay[7o7 UNI !ID !ETH]: %RED%¤ Bonehew ¤
ItemDisplay[7o7 UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Bonehew ¤
//Reaper's Toll
ItemDisplay[7s8 UNI !ID !ETH]: %RED%¤ Reaper's Toll ¤
ItemDisplay[7s8 UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Reaper's Toll %RED%¤
//Tomb Reaver
ItemDisplay[7pa UNI !ID !ETH]: %RED%¤ Tomb Reaver ¤
ItemDisplay[7pa UNI !ID ETH]: %RED%¤ %GRAY%ETH %RED%Tomb Reaver ¤
//Stormspire
ItemDisplay[7wc UNI !ID !ETH]: %TAN%Stormspire
ItemDisplay[7wc UNI !ID ETH]: %GRAY%ETH %TAN%Stormspire
////WP9 BOWS
//Pluckeye
//ItemDisplay[sbw UNI !ID]: %TAN%Pluckeye
//Witherstring
//ItemDisplay[hbw UNI !ID]: %TAN%Witherstring
//Raven Claw
//ItemDisplay[lbw UNI !ID]: %TAN%Raven Claw
//Rogue's Bow
//ItemDisplay[cbw UNI !ID]: %TAN%Rogue's Bow
//Stormstrike
//ItemDisplay[sbb UNI !ID]: %TAN%Stormstrike
//Wizendraw
//ItemDisplay[lbb UNI !ID]: %TAN%Wizendraw
//Hellclap
//ItemDisplay[swb UNI !ID]: %TAN%Hellclap
//Blastbark
//ItemDisplay[lwb UNI !ID]: %TAN%Blastbark
//Skystrike
//ItemDisplay[8sb UNI !ID]: %TAN%Skystrike
//Riphook
//ItemDisplay[8hb UNI !ID]: %TAN%Riphook
//Kuko Shakaku
//ItemDisplay[8lb UNI !ID]: %TAN%¤ Kuko Shakaku ¤
//Endlesshail
//ItemDisplay[8cb UNI !ID]: %TAN%Endlesshail
//Witchwild String
//ItemDisplay[8s8 UNI !ID]: %TAN%Witchwild String
//Cliffkiller
//ItemDisplay[8l8 UNI !ID]: %TAN%Cliffkiller
//Magewrath
//ItemDisplay[8sw UNI !ID]: %TAN%Magewrath
//Goldstrike Arch
ItemDisplay[8lw UNI !ID]: %RED%¤¤¤ Goldstrike Arch ¤¤¤
//Eaglehorn
ItemDisplay[6l7 UNI !ID]: %TAN%¤ Eaglehorn ¤
//Widowmaker
ItemDisplay[6sw UNI !ID]: %TAN%¤ Widowmaker ¤
//Windforce
ItemDisplay[6lw UNI !ID]: %RED%¤¤¤ %PURPLE%Windforce %RED%¤¤¤
////WP10 CROSSBOWS
//Leadcrow
//ItemDisplay[lxb UNI !ID]: %TAN%Leadcrow
//Ichorsting
//ItemDisplay[mxb UNI !ID]: %TAN%Ichorsting
//Hellcast
//ItemDisplay[hxb UNI !ID]: %TAN%Hellcast
//Doomslinger
//ItemDisplay[rxb UNI !ID]: %RED%¤¤ Doomslinger ¤¤
//Langer Briser
//ItemDisplay[8lx UNI !ID]: %TAN%Langer Briser
//Pus Spitter
//ItemDisplay[8mx UNI !ID]: %TAN%Pus Spitter
//Buriza-Do Kyanon
//ItemDisplay[8hx UNI !ID]: %TAN%Buriza-Do Kyanon
//Demon Machine
//ItemDisplay[8rx UNI !ID]: %TAN%Demon Machine
//Hellrack
//ItemDisplay[6hx UNI !ID]: %TAN%Hellrack
//Gut Siphon
//ItemDisplay[6rx UNI !ID]: %TAN%Gut Siphon
////WP11 STAVES
//Bane Ash
//ItemDisplay[sst UNI !ID !ETH]: %TAN%Bane Ash
//ItemDisplay[sst UNI !ID ETH]: %GRAY%ETH %TAN%Bane Ash
//Serpent Lord
//ItemDisplay[lst UNI !ID !ETH]: %TAN%Serpent Lord
//ItemDisplay[lst UNI !ID ETH]: %GRAY%ETH %TAN%Serpent Lord
//Spire of Lazarus
//ItemDisplay[cst UNI !ID !ETH]: %TAN%Spire of Lazarus
//ItemDisplay[cst UNI !ID ETH]: %GRAY%ETH %TAN%Spire of Lazarus
//The Salamander
//ItemDisplay[bst UNI !ID !ETH]: %TAN%The Salamander
//ItemDisplay[bst UNI !ID ETH]: %GRAY%ETH %TAN%The Salamander
//The Iron Jang Bong
//ItemDisplay[wst UNI !ID !ETH]: %TAN%The Iron Jang Bong
//ItemDisplay[wst UNI !ID ETH]: %GRAY%ETH %TAN%The Iron Jang Bong
//Razorswitch
//ItemDisplay[8ss UNI !ID !ETH]: %TAN%Razorswitch
//ItemDisplay[8ss UNI !ID ETH]: %GRAY%ETH %TAN%Razorswitch
//Ribcracker
//ItemDisplay[8ls UNI !ID !ETH]: %TAN%Ribcracker
//ItemDisplay[8ls UNI !ID ETH]: %GRAY%ETH %TAN%Ribcracker
//Chromatic Ire
//ItemDisplay[8cs UNI !ID !ETH]: %TAN%Chromatic Ire
//ItemDisplay[8cs UNI !ID ETH]: %GRAY%ETH %TAN%Chromatic Ire
//Warpspear
//ItemDisplay[8bs UNI !ID !ETH]: %TAN%Warpspear
//ItemDisplay[8bs UNI !ID ETH]: %GRAY%ETH %TAN%Warpspear
//Skull Collector
ItemDisplay[8ws UNI !ID !ETH]: %TAN%Skull Collector
ItemDisplay[8ws UNI !ID ETH]: %GRAY%ETH %TAN%Skull Collector
//Ondal's Wisdom
ItemDisplay[6cs UNI !ID !ETH]: %RED%¤¤ %PURPLE%Ondal's Wisdom %RED%¤¤
ItemDisplay[6cs UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Ondal's Wisdom %RED%¤
//Mang Song's Lesson
ItemDisplay[6ws UNI !ID !ETH]: %RED%Mang Song's Lesson ¤
ItemDisplay[6ws UNI !ID ETH]: %GRAY%ETH %TAN%Mang Song's Lesson
////WP12 WANDS
//Torch of Iro
//ItemDisplay[wnd UNI !ID !ETH]: %TAN%Torch of Iro
//ItemDisplay[wnd UNI !ID ETH]: %GRAY%ETH %TAN%Torch of Iro
//Maelstrom
//ItemDisplay[ywn UNI !ID !ETH]: %TAN%Maelstrom
//ItemDisplay[ywn UNI !ID ETH]: %GRAY%ETH %TAN%Maelstrom
//Gravenspine
//ItemDisplay[bwn UNI !ID !ETH]: %TAN%Gravenspine
//ItemDisplay[bwn UNI !ID ETH]: %GRAY%ETH %TAN%Gravenspine
//Ume's Lament
//ItemDisplay[gwn UNI !ID !ETH]: %TAN%Ume's Lament
//ItemDisplay[gwn UNI !ID ETH]: %GRAY%ETH %TAN%Ume's Lament
//Suicide Branch
//ItemDisplay[9wn UNI !ID !ETH]: %TAN%¤ Suicide Branch ¤
//ItemDisplay[9wn UNI !ID ETH]: %GRAY%ETH %TAN%Suicide Branch
//Carin Shard
//ItemDisplay[9yw UNI !ID !ETH]: %TAN%Carin Shard
//ItemDisplay[9yw UNI !ID ETH]: %GRAY%ETH %TAN%Carin Shard
//Arm of King Leoric
//ItemDisplay[9bw UNI !ID !ETH]: %TAN%Arm of King Leoric
//ItemDisplay[9bw UNI !ID ETH]: %GRAY%ETH %TAN%Arm of King Leoric
//Blackhand Key
//ItemDisplay[9gw UNI !ID !ETH]: %TAN%¤ Blackhand Key ¤
//ItemDisplay[9gw UNI !ID ETH]: %GRAY%ETH %TAN%Blackhand Key
//Boneshade
ItemDisplay[7bw UNI !ID !ETH]: %TAN%¤ Boneshade ¤
ItemDisplay[7bw UNI !ID ETH]: %TAN%¤ %GRAY%ETH %TAN%Boneshade ¤
//Death's Web
ItemDisplay[7gw UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Death's Web %RED%¤¤¤
ItemDisplay[7gw UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %PURPLE%Death's Web %RED%¤¤
////WP13 SCEPTERS
//Knell Striker
//ItemDisplay[scp UNI !ID !ETH]: %TAN%Knell Striker
//ItemDisplay[scp UNI !ID ETH]: %GRAY%ETH %TAN%Knell Striker
//Rusthandle
//ItemDisplay[gsc UNI !ID !ETH]: %TAN%Rusthandle
//ItemDisplay[gsc UNI !ID ETH]: %GRAY%ETH %TAN%Rusthandle
//Stormeye
//ItemDisplay[wsp UNI !ID !ETH]: %TAN%Stormeye
//ItemDisplay[wsp UNI !ID ETH]: %GRAY%ETH %TAN%Stormeye
//Zakarum's Hand
ItemDisplay[9sc UNI !ID !ETH]: %TAN%Zakarum's Hand
ItemDisplay[9sc UNI !ID ETH]: %GRAY%ETH %TAN%Zakarum's Hand
//The Fetid Sprinkler
ItemDisplay[9qs UNI !ID !ETH]: %TAN%The Fetid Sprinkler
ItemDisplay[9qs UNI !ID ETH]: %GRAY%ETH %TAN%The Fetid Sprinkler
//Hand of Blessed Light
ItemDisplay[9ws UNI !ID !ETH]: %RED%¤¤ Hand of Blessed Light ¤¤
ItemDisplay[9ws UNI !ID ETH]: %GRAY%ETH %TAN%Hand of Blessed Light
//Heaven's Light or The Redeemer
ItemDisplay[7sc UNI !ID !ETH]: %RED%¤¤ Heaven's Light or The Redeemer ¤¤
ItemDisplay[7sc UNI !ID ETH]: %GRAY%ETH %RED%Heaven's Light or %GRAY%ETH %RED%The Redeemer
//Astreon's Iron Ward
ItemDisplay[7ws UNI !ID !ETH]: %RED%¤ Astreon's Iron Ward ¤
ItemDisplay[7ws UNI !ID ETH]: %GRAY%ETH %RED%Astreon's Iron Ward
////QUIVERS
//Arrows and Bolts
//ItemDisplay[aq2 UNI !ID]: %TAN%%NAME%
//ItemDisplay[cq2 UNI !ID]: %TAN%%NAME%
////CL1 DRUID ITEMS
//Jalal's Mane
ItemDisplay[dra UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Jalal's Mane %RED%¤¤¤
ItemDisplay[dra UNI !ID ETH]: %GRAY%ETH %RED%Jalal's Mane
//Cerebus' Bite
ItemDisplay[drb UNI !ID !ETH]: %TAN%Cerebus' Bite
ItemDisplay[drb UNI !ID ETH]: %GRAY%ETH %TAN%Cerebus' Bite
//Ravenlore
ItemDisplay[dre UNI !ID !ETH]: %RED%¤¤ Ravenlore ¤¤
ItemDisplay[dre UNI !ID ETH]: %GRAY%ETH %RED%Ravenlore
//Spirit Keeper
ItemDisplay[drd UNI !ID !ETH]: %RED%¤¤ Spirit Keeper ¤¤
ItemDisplay[drd UNI !ID ETH]: %GRAY%ETH %TAN%Spirit Keeper
////CL2 BARBARIAN ITEMS
//Arreat's Face
ItemDisplay[baa UNI !ID !ETH]: %RED%¤¤¤ %PURPLE%Arreat's Face %RED%¤¤¤
ItemDisplay[baa UNI !ID ETH]: %GRAY%ETH %RED%Arreat's Face
//Wolfhowl
ItemDisplay[bac UNI !ID !ETH]: %RED%¤¤ Wolfhowl ¤¤
ItemDisplay[bac UNI !ID ETH]: %GRAY%ETH %RED%Wolfhowl
//Demonhorn's Edge
ItemDisplay[bad UNI !ID !ETH]: %TAN%Demonhorn's Edge
ItemDisplay[bad UNI !ID ETH]: %GRAY%ETH %TAN%Demonhorn's Edge
//Halaberd's Reign
ItemDisplay[bae UNI !ID !ETH]: %TAN%¤ Halaberd's Reign ¤
ItemDisplay[bae UNI !ID ETH]: %GRAY%ETH %TAN%Halaberd's Reign
////CL3 PALADIN ITEMS
//Alma Negra
ItemDisplay[pac UNI !ID !ETH]: %RED%¤¤ Alma Negra ¤¤
ItemDisplay[pac UNI !ID ETH]: %GRAY%ETH %RED%Alma Negra
//Herald of Zakarum
ItemDisplay[pa9 UNI !ID !ETH]: %RED%¤¤ %PURPLE%Herald of Zakarum %RED%¤¤
ItemDisplay[pa9 UNI !ID ETH]: %GRAY%ETH %RED%Herald of Zakarum
//Dragonscale
ItemDisplay[pae UNI !ID !ETH]: %TAN%Dragonscale
ItemDisplay[pae UNI !ID ETH]: %GRAY%ETH %TAN%Dragonscale
////CL4 NECROMANCER ITEMS
//Homunculus
ItemDisplay[nea UNI !ID !ETH]: %RED%¤¤ %PURPLE%Homunculus %RED%¤¤
ItemDisplay[nea UNI !ID ETH]: %GRAY%ETH %RED%Homunculus
//Darkforce Spawn
ItemDisplay[nef UNI !ID !ETH]: %TAN%¤ Darkforce Spawn ¤
ItemDisplay[nef UNI !ID ETH]: %GRAY%ETH %TAN%Darkforce Spawn
//Boneflame
ItemDisplay[nee UNI !ID !ETH]: %RED%¤ Boneflame ¤
ItemDisplay[nee UNI !ID ETH]: %GRAY%ETH %TAN%Boneflame
////CL5 ASSASSIN ITEMS
//Shadow Killer (always ETH)
ItemDisplay[7cs UNI !ID ETH]: %TAN%¤ ETH Shadow Killer ¤
//Bartuc's Cut-Throat
ItemDisplay[9tw UNI !ID !ETH]: %TAN%Bartuc's Cut-Throat
ItemDisplay[9tw UNI !ID ETH]: %GRAY%ETH %TAN%Bartuc's Cut-Throat
//Jade Talon
ItemDisplay[7wb UNI !ID !ETH]: %TAN%Jade Talon
ItemDisplay[7wb UNI !ID ETH]: %GRAY%ETH %TAN%Jade Talon
//Firelizard's Talons
ItemDisplay[7lw UNI !ID !ETH]: %TAN%¤ Firelizard's Talons ¤
ItemDisplay[7lw UNI !ID ETH]: %GRAY%ETH %TAN%Firelizard's Talons
////CL6 SORCERER ITEMS
//The Oculus
ItemDisplay[oba UNI !ID !ETH]: %RED%¤¤ The Oculus ¤¤
ItemDisplay[oba UNI !ID ETH]: %GRAY%ETH %TAN%The Oculus
//Eschuta's Temper
ItemDisplay[obc UNI !ID !ETH]: %RED%¤¤¤ %PURPLE% Eschuta's Temper %RED%¤¤¤
ItemDisplay[obc UNI !ID ETH]: %GRAY%ETH %TAN%Eschuta's Temper
//Death's Fathom
ItemDisplay[obf UNI !ID !ETH]: %PURPLE%¤¤¤ Death's Fathom ¤¤¤
ItemDisplay[obf UNI !ID ETH]: %RED%¤ %GRAY%ETH %PURPLE%Death's Fathom %RED%¤
////CL7 AMAZON ITEMS
//Stoneraven
ItemDisplay[amd UNI !ID !ETH]: %TAN%Stoneraven
ItemDisplay[amd UNI !ID ETH]: %GRAY%ETH %TAN%Stoneraven
//Lycander's Flank
ItemDisplay[am9 UNI !ID !ETH]: %TAN%Lycander's Flank
ItemDisplay[am9 UNI !ID ETH]: %GRAY%ETH %TAN%Lycander's Flank
//Lycander's Aim
ItemDisplay[am7 UNI !ID]: %TAN%¤ Lycander's Aim ¤
//Titan's Revenge
ItemDisplay[ama UNI !ID !ETH]: %RED%¤¤ Titan's Revenge ¤¤
ItemDisplay[ama UNI !ID ETH]: %RED%¤¤ %GRAY%ETH %RED%Titan's Revenge ¤¤
//Thunderstroke
ItemDisplay[amf UNI !ID !ETH]: %RED%¤ Thunderstroke ¤
ItemDisplay[amf UNI !ID ETH]: %GRAY%ETH %TAN%Thunderstroke
//Blood Raven's Charge
ItemDisplay[amb UNI !ID]: %TAN%Blood Raven's Charge
////RINGS/AMULETS/JEWELS
ItemDisplay[(rin OR amu OR jew) UNI !ID]: %RED%¤¤¤¤¤¤%PURPLE% %NAME% %RED%¤¤¤¤¤¤
////SET ITEMS
//AMULETS
ItemDisplay[amu SET !ID]: %GREEN%**** Amulet ****
///ANGELIC RAIMENT
//Angelic Mantle
//ItemDisplay[rng SET !ID]: %GREEN%%NAME% %DGREEN%Angelic
//Angelic Sickle
//ItemDisplay[sbr SET !ID]: %GREEN%%NAME% %DGREEN%Angelic
///ARCANNA'S TRICKS
//Arcanna's Head
//ItemDisplay[skp SET !ID]: %GREEN%%NAME% %DGREEN%Arcanna's
//Arcanna's Flesh
//ItemDisplay[ltp SET !ID]: %GREEN%%NAME% %DGREEN%Arcanna's
//Arcanna's Deathwand
//ItemDisplay[wst SET !ID]: %GREEN%%NAME% %DGREEN%Arcanna's
///ARCTIC GEAR
//Arctic Furs
//ItemDisplay[qui SET !ID]: %GREEN%%NAME% %DGREEN%Arctic
//Arctic Binding
//ItemDisplay[vbl SET !ID]: %GREEN%%NAME% %DGREEN%Arctic
//Arctic Mitts
//ItemDisplay[tgl SET !ID]: %GREEN%%NAME% %DGREEN%Iratha's Cuff or Arctic Mitts
//Arctic Horn
//ItemDisplay[swb SET !ID]: %GREEN%%NAME% %DGREEN%Arctic
///BERSERKER'ARSENAL
//Berserker's Headgear
//ItemDisplay[hlm SET !ID]: %GREEN%%NAME% %DGREEN%Berserker's
//Berserker's Hauberk
//ItemDisplay[spl SET !ID]: %GREEN%%NAME% %DGREEN%Berserker's
//Berserker's Hatchet
//ItemDisplay[2ax SET !ID]: %GREEN%%NAME% %DGREEN%Berserker's
///CATHAN'S TRAPS
//Cathan's Visage
//ItemDisplay[msk SET !ID]: %GREEN%%NAME% %DGREEN%Cathan's
//Cathan's Mesh
//ItemDisplay[chn SET !ID]: %GREEN%%NAME% %DGREEN%Cathan's
//Cathan's Rule
//ItemDisplay[bst SET !ID]: %GREEN%%NAME% %DGREEN%Cathan's
///CIVERB'S VESTMENTS
//Civerb's Cudgel
//ItemDisplay[gsc SET !ID]: %GREEN%%NAME% %DGREEN%Civerb's
//Civerb's Ward
//ItemDisplay[lrg SET !ID]: %GREEN%%NAME% %DGREEN%Civerb's
///CLEGLAW'S BRACE
//Cleglaw's Tooth
//ItemDisplay[lsd SET !ID]: %GREEN%%NAME% %DGREEN%Cleglaw's
//Cleglaw's Pincer's
//ItemDisplay[mgl SET !ID]: %GREEN%%NAME% %DGREEN%Cleglaw's
//Cleglaw's Claw
//ItemDisplay[sml SET !ID]: %GREEN%%NAME% %DGREEN%Cleglaw's
///DEATH'S DISGUISE
//Death's Touch
//ItemDisplay[wsd SET !ID]: %GREEN%%NAME% %DGREEN%Death's
//Death's Hand
//ItemDisplay[lgl SET !ID]: %GREEN%%NAME% %DGREEN%Death's
//Death's Guard
//ItemDisplay[lbl SET !ID]: %GREEN%%NAME% %DGREEN%Death's
///HSARUS' DEFENSE
//Hsarus' Iron Fist
//ItemDisplay[buc SET !ID]: %GREEN%%NAME% %DGREEN%Hsarus'
//Hsarus' Iron Stay
//ItemDisplay[mbl SET !ID]: %GREEN%%NAME% %DGREEN%Hsarus' or Hwanin's
//Hsarus' Iron Heel
//ItemDisplay[mbt SET !ID]: %GREEN%%NAME% %DGREEN%Hsarus'
///INFERNAL TOOLS
//Infernal Cranium
//ItemDisplay[cap SET !ID]: %GREEN%%NAME% %DGREEN%Infernal Cranium or Sander's Paragon
//Infernal Sign
//ItemDisplay[tbl SET !ID]: %GREEN%%NAME% %DGREEN%Infernal Sign or Iratha's Cord
//Infernal Torch
//ItemDisplay[gwn SET !ID]: %GREEN%%NAME% %DGREEN%Infernal
///IRATHA'S FINERY
//Iratha's Coil
//ItemDisplay[crn SET !ID]: %GREEN%%NAME% %DGREEN%Iratha's Coil or Milabrega's Diadem
//Iratha's Cord
//ItemDisplay[tbl SET !ID]: %GREEN%%NAME% %DGREEN%Infernal Sign or Iratha's Cord
//Iratha's Cuff
//ItemDisplay[tgl SET !ID]: %GREEN%%NAME% %DGREEN%Iratha's Cuff or Arctic Mitts
///ISENHART'S ARMORY
//Isenhart's Lightbrand
//ItemDisplay[bsd SET !ID]: %GREEN%%NAME% %DGREEN%Isenhart's
//Isenhart's Horns
//ItemDisplay[fhl SET !ID]: %GREEN%%NAME% %DGREEN%Isenhart's
//Isenhart's Case
//ItemDisplay[brs SET !ID]: %GREEN%%NAME% %DGREEN%Isenhart's
//Isenhart's Parry
//ItemDisplay[gts SET !ID]: %GREEN%%NAME% %DGREEN%Isenhart's
///MILABREGA'S REGALIA
//Milabrega's Diadem
//ItemDisplay[crn SET !ID]: %GREEN%%NAME% %DGREEN%Iratha's Coil or Milabrega's Diadem
//Milabrega's Robe
//ItemDisplay[aar SET !ID]: %GREEN%%NAME% %DGREEN%Milabrega's
//Milabrega's Orb
//ItemDisplay[kit SET !ID]: %GREEN%%NAME% %DGREEN%Milabrega's
//Milabrega's Rod
//ItemDisplay[wsp SET !ID]: %GREEN%%NAME% %DGREEN%Milabrega's
///SIGON'S COMPLETE STEEL
//Sigon's Visor
//ItemDisplay[ghm SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
//Sigon's Shelter
//ItemDisplay[gth SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
//Sigon's Sabot
//ItemDisplay[hbt SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
//Sigon's Guard
//ItemDisplay[tow SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
//Sigon's Wrap
//ItemDisplay[hbl SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
//Sigon's Gage
//ItemDisplay[hgl SET !ID]: %GREEN%%NAME% %DGREEN%Sigon's
///TANCRED'S BATTLEGEAR
//Tancred's Skull
//ItemDisplay[bhm SET !ID]: %GREEN%%NAME% %DGREEN%Tancred's
//Tancred's Spine
//ItemDisplay[ful SET !ID]: %GREEN%%NAME% %DGREEN%Tancred's
//Tancred's Hobnails
//ItemDisplay[lbt SET !ID]: %GREEN%%NAME% %DGREEN%Tancred's
//Tancred's Crowbill
//ItemDisplay[mpi SET !ID]: %GREEN%%NAME% %DGREEN%Tancred's
///VIDALA'S RIG
//Vidala's Barb
//ItemDisplay[lbb SET !ID]: %GREEN%%NAME% %DGREEN%Vidala's
//Vidala's Ambush
//ItemDisplay[lea SET !ID]: %GREEN%%NAME% %DGREEN%Vidala's
//Vidala's Fetlock
//ItemDisplay[tbt SET !ID]: %GREEN%%NAME% %DGREEN%Vidala's
///ALDUR'S WATCHTOWER
//Aldur's Stony Gaze
//ItemDisplay[dr8 SET !ID]: %GREEN%%NAME% %DGREEN%Aldur's %RED%¤
//Aldur's Advance
//ItemDisplay[xtb SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Aldur's %RED%¤
//Aldur's Deception
//ItemDisplay[uul SET !ID]: %GREEN%%NAME% %DGREEN%Aldur's %RED%¤
//Aldur's Rhythm
//ItemDisplay[9mt SET !ID]: %GREEN%%NAME% %DGREEN%Aldur's
///BUL-KATHOS' CHILDREN
//Bul-Kathos' Sacred Charge
//ItemDisplay[7gd SET !ID]: %GREEN%%NAME% %DGREEN%Bul-Kathos' %RED%¤
//Bul-Kathos' Tribal Guardian
//ItemDisplay[7wd SET !ID]: %GREEN%%NAME% %DGREEN%Bul-Kathos' %RED%¤
///COW KING'S LEATHERS
//Cow King's Horns
//ItemDisplay[xap SET !ID]: %GREEN%%NAME% %DGREEN%Cow King's %RED%¤
//Cow King's Hide
//ItemDisplay[stu SET !ID]: %GREEN%%NAME% %DGREEN%Cow King's %RED%¤
//Cow King's Hooves
//ItemDisplay[vbt SET !ID]: %GREEN%%NAME% %DGREEN%Sander's or Cow King's
///THE DISCIPLE
//Laying of Hands
ItemDisplay[ulg SET !ID]: %RED%¤¤ %GREEN%%NAME% %DGREEN%The Disciple %RED%¤¤
//Dark Adherent
//ItemDisplay[uui SET !ID]: %GREEN%%NAME% %DGREEN%The Disciple
//Rite of Passage
//ItemDisplay[xlb SET !ID]: %GREEN%%NAME% %DGREEN%The Disciple
//Credendum
//ItemDisplay[umc SET !ID]: %GREEN%%NAME% %DGREEN%The Disciple
///GRISWOLD'S LEGACY
//Griswold's Heart
//ItemDisplay[xar SET !ID]: %GREEN%%NAME% %DGREEN%Griswold's
//Griswold's Valor
ItemDisplay[urn SET !ID]: %GREEN%%NAME% %DGREEN%Griswold's %RED%¤
//Griswold's Redemption
ItemDisplay[7ws SET !ID]: %GREEN%%NAME% %DGREEN%Griswold's
//Griswold's Honor
ItemDisplay[paf SET !ID]: %GREEN%%NAME% %DGREEN%Griswold's %RED%¤
///HEAVEN'S BRETHREN
//Haemosu's Adamant
//ItemDisplay[xrs SET !ID]: %GREEN%%NAME% %DGREEN%Heaven's Brethren
//Dangoon's Teaching
//ItemDisplay[7ma SET !ID]: %GREEN%%NAME% %DGREEN%Heaven's Brethren %RED%¤
//Taebaek's Glory
//ItemDisplay[uts SET !ID]: %GREEN%%NAME% %DGREEN%Heaven's Brethren
//Ondal's Almighty
//ItemDisplay[uhm SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Heaven's Brethren %RED%¤
///HWANIN'S MAJESTY
//Hwanin's Splendor
//ItemDisplay[xrn SET !ID]: %GREEN%%NAME% %DGREEN%Hwanin's
//Hwanin's Justice
//ItemDisplay[9vo SET !ID !ETH]: %GREEN%%NAME% %DGREEN%Hwanin's
//Hwanin's Justice Eth
//ItemDisplay[9vo SET !ID ETH]: %GRAY%ETH %GREEN%%NAME% %DGREEN%Hwanin's
//Hwanin's Refuge
//ItemDisplay[xcl SET !ID]: %GREEN%%NAME% %DGREEN%Hwanin's
//Hwanin's Blessing
//ItemDisplay[mbl SET !ID]: %GREEN%%NAME% %DGREEN%Hsarus' or Hwanin's
///IMMORTAL KING
//Immortal King's Will
ItemDisplay[ba5 SET !ID]: %GREEN%%NAME% %DGREEN%Immortal King %RED%¤
//Immortal King's Stone Crusher
ItemDisplay[7m7 SET !ID]: %GREEN%%NAME% %DGREEN%Immortal King
//Immortal King's Soul Cage
ItemDisplay[uar SET !ID]: %PURPLE%¤¤¤ %GREEN%%NAME% %DGREEN%Immortal King %PURPLE%¤¤¤
//Immortal King's Detail
ItemDisplay[zhb SET !ID]: %GREEN%%NAME% %DGREEN%Immortal King
//Immortal King's Forge
ItemDisplay[xhg SET !ID]: %GREEN%%NAME% %DGREEN%Immortal King
//Immortal King's Pillar
ItemDisplay[xhb SET !ID]: %GREEN%%NAME% %DGREEN%Immortal King %RED%¤
///M'AVINA'S BATTLE HYMN
//M'avina's True Sight
//ItemDisplay[ci3 SET !ID]: %GREEN%%NAME% %DGREEN%Mavina's
//M'avina's Caster
//ItemDisplay[amc SET !ID]: %GREEN%%NAME% %DGREEN%Mavina's
//M'avina's Embrace
//ItemDisplay[uld SET !ID]: %GREEN%%NAME% %DGREEN%Mavina's
//M'avina's Icy Clutch
//ItemDisplay[xtg SET !ID]: %GREEN%%NAME% %DGREEN%Mavina's
//M'avina's Tenet
//ItemDisplay[zvb SET !ID]: %GREEN%%NAME% %DGREEN%Mavina's
///NATALYA'S ODIUM
//Natalya's Totem
ItemDisplay[xh9 SET !ID]: %GREEN%%NAME% %DGREEN%Natalya's
//Natalya's Mark
ItemDisplay[7qr SET !ID]: %PURPLE%¤¤¤ %GREEN%%NAME% %DGREEN%Natalya's %PURPLE%¤¤¤
//Natalya's Shadow
ItemDisplay[ucl SET !ID]: %GREEN%%NAME% %DGREEN%Natalya's %RED%¤
//Natalya's Soul
ItemDisplay[xmb SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Natalya's %RED%¤
///NAJ'S ANCIENT VESTIGE
//Naj's Circlet
//ItemDisplay[ci0 SET !ID]: %GREEN%%NAME% %DGREEN%Naj's
//Naj's Light Plate
ItemDisplay[ult SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Naj's %RED%¤
//Naj's Puzzler
//ItemDisplay[6cs SET !ID ]: %GREEN%%NAME% %DGREEN%Naj's %RED%¤
///ORPHAN'S CALL
//Guillaume's Face
ItemDisplay[xhm SET !ID]: %RED%¤¤ %GREEN%%NAME% %DGREEN%Orphan's (Guillaume's Face) %RED%¤¤
//Whitstan's Guard
//ItemDisplay[xml SET !ID]: %GREEN%%NAME% %DGREEN%Orphan's
//Magnus' Skin
//ItemDisplay[xvg SET !ID]: %GREEN%%NAME% %DGREEN%Orphan's
//Wilhelm's Pride
//ItemDisplay[ztb SET !ID]: %GREEN%%NAME% %DGREEN%Orphan's
///SANDER'S FOLLY
//Sander's Paragon
//ItemDisplay[cap SET !ID]: %GREEN%%NAME% %DGREEN%Infernal Cranium or Sander's Paragon
//Sander's Superstition
//ItemDisplay[bwn SET !ID]: %GREEN%%NAME% %DGREEN%Sander's
//Sander's Taboo
//ItemDisplay[vgl SET !ID]: %GREEN%%NAME% %DGREEN%Sander's
//Sander's Riprap
//ItemDisplay[vbt SET !ID]: %GREEN%%NAME% %DGREEN%Sander's or Cow King's
///SAZABI'S GRAND TRIBUTE
//Sazabi's Mental Sheath
//ItemDisplay[xhl SET !ID]: %GREEN%%NAME% %DGREEN%Sazabi's
//Sazabi's Cobalt Redeemer
//ItemDisplay[7ls SET !ID !ETH]: %RED%¤ %GREEN%%NAME% %DGREEN%Sazabi's %RED%¤
//ItemDisplay[7ls SET !ID ETH]: %RED%¤ %GRAY%ETH %GREEN%%NAME% %DGREEN%Sazabi's %RED%¤
//Sazabi's Ghost Liberator
//ItemDisplay[upl SET !ID]: %GREEN%%NAME% %DGREEN%Sazabi's %RED%¤
///TAL RASHA'S WRAPPINGS
//Tal Rasha's Lidless Eye
ItemDisplay[oba SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Tal Rasha's %RED%¤
//Tal Rasha's Horadric Crest
ItemDisplay[xsk SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Tal Rasha's %RED%¤
//Tal Rasha's Guardianship
ItemDisplay[uth SET !ID]: %PURPLE%¤¤¤ %GREEN%%NAME% %DGREEN%Tal Rasha's %PURPLE%¤¤¤
//Tal Rasha's Fine-Spun Cloth
ItemDisplay[zmb SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Tal Rasha's %RED%¤
///Trang-Oul's Avatar
//Trang-Oul's Guise
ItemDisplay[uh9 SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Trang-Oul's %RED%¤
//Trang-Oul's Scales
ItemDisplay[xul SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Trang-Oul's %RED%¤
//Trang-Oul's Wing
ItemDisplay[ne9 SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Trang-Oul's %RED%¤
//Trang-Oul's Girth
ItemDisplay[utc SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Trang-Oul's %RED%¤
//Trang-Oul's Claws
ItemDisplay[xmg SET !ID]: %RED%¤ %GREEN%%NAME% %DGREEN%Trang-Oul's %RED%¤
///UNIQUE&SET CATCHALL
ItemDisplay[UNI ETH SOCK>0]: %GRAY%ETH %TAN%%NAME% [%SOCKETS%]
ItemDisplay[SET ETH SOCK>0]: %GRAY%ETH %GREEN%%NAME% [%SOCKETS%]
ItemDisplay[UNI ETH]: %GRAY%ETH %TAN%%NAME%
ItemDisplay[SET ETH]: %GRAY%ETH %GREEN%%NAME%
ItemDisplay[UNI SOCK>0]: %NAME% [%SOCKETS%]
ItemDisplay[SET SOCK>0]: %NAME% [%SOCKETS%]
ItemDisplay[UNI]: %NAME%
ItemDisplay[SET]: %NAME%
ItemDisplay[UNI ETH !ID SOCK>0]: %GRAY%ETH %TAN%%NAME% [%SOCKETS%]
ItemDisplay[SET ETH !ID SOCK>0]: %GRAY%ETH %GREEN%%NAME% [%SOCKETS%]
ItemDisplay[UNI ETH !ID]: %GRAY%ETH %TAN%%NAME%
ItemDisplay[SET ETH !ID]: %GRAY%ETH %GREEN%%NAME%
ItemDisplay[UNI !ID SOCK>0]: %NAME% [%SOCKETS%]
ItemDisplay[SET !ID SOCK>0]: %NAME% [%SOCKETS%]	
ItemDisplay[UNI !ID]: %NAME%
ItemDisplay[SET !ID]: %NAME%
////RUNEWORDS
ItemDisplay[RW]: %NAME%
////SHOPPING
//+3 Java/Bow skills Gloves
ItemDisplay[EQ4 MAG !ETH TABSK2>2 IAS=20]: %NAME% %PURPLE%+3 Javelin Skills 20IAS
ItemDisplay[EQ4 MAG !ETH TABSK2>2 IAS=10]: %NAME% %RED%+3 Javelin Skills 10IAS
ItemDisplay[EQ4 MAG !ETH TABSK2>2]: %NAME% %ORANGE%+3 Javelin Skills
ItemDisplay[EQ4 MAG !ETH TABSK0>2 IAS=20]: %NAME% %PURPLE%+3 Bow Skills 20IAS
ItemDisplay[EQ4 MAG !ETH TABSK0>2 IAS=10]: %NAME% %RED%+3 Bow Skills 10IAS
ItemDisplay[EQ4 MAG !ETH TABSK0>2]: %NAME% %ORANGE%+3 Bow Skills
//+2 Java/Bow skills Gloves
ItemDisplay[EQ4 MAG !ETH TABSK2=2 IAS=20]: %NAME% %RED%+2 Javelin Skills 20IAS
ItemDisplay[EQ4 MAG !ETH TABSK2=2 IAS=10]: %NAME% %RED%+2 Javelin Skills 10IAS
ItemDisplay[EQ4 MAG !ETH TABSK0=2 IAS=20]: %NAME% %RED%+2 Bow Skills 20IAS
ItemDisplay[EQ4 MAG !ETH TABSK0=2 IAS=10]: %NAME% %RED%+2 Bow Skills 10IAS
//BO Sticks
ItemDisplay[(WP3 OR WP5 OR WP6) TABSK34>2]: %NAME% %YELLOW%+3 Warcries Skills
ItemDisplay[(WP3 OR WP5 OR WP6) TABSK34=2]: %NAME% %YELLOW%+2 Warcries Skills
////CRAFTING ITEMS
///HELMS
//Blood Helms (Magic Helm/Casque/Armet + RAL + RUBY + JEWEL
ItemDisplay[(hlm OR xlm OR ulm) MAG ILVL>82 CLVL<91]: %ORANGE%Blood Helm %WHITE%[L%ILVL%]
///GLOVES
//Blood Gloves (Heavy Gloves(vgl)/Sharkskin(xvg)/Vampirebone(uvg) ilvl 85-95) + NEF + RUBY + JEWEL 
//Hit Power Gloves (Chain Gloves(vgl)/Heavy Bracers(xmg)/Vambraces(umg) ilvl 85-95) + ORT + SAPPHIRE + JEWEL
///BOOTS
//Caster Boots (Wyrmhide Boots/Demonhide Boots/Boots) + Thul + Amethyst + Jewel
ItemDisplay[(ulb OR xlb OR lbt) MAG ILVL>84]: %ORANGE%Caster Boots %WHITE%[L%ILVL%]
///BELTS
//Exceptional and Elite Quality belts ONLY
//Caster Belts (Vampirefang/Sharkskin) + ITH + AMETHYST + JEWEL
ItemDisplay[(uvc OR zvb) MAG ILVL>84]: %ORANGE%Caster Belt %WHITE%[L%ILVL%]
//Blood Belts (Mithril Coil/Mesh Belt) + TAL + RUBY + JEWEL
ItemDisplay[(umc OR zmb) MAG ILVL>84]: %ORANGE%Blood Belt %WHITE%[L%ILVL%]
////ARMOR BASES
///EQ1/EQ7 HELMS
//Demonhead, Bone Visage, Diadem
ItemDisplay[(usk OR uh9 OR ci3) NMAG !ETH !SOCK=1 !SOCK=2 ED=15]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[(usk OR uh9 OR ci3) NMAG !ETH !SOCK=1 ED>0 ED<15]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[(usk OR uh9 OR ci3) NMAG !ETH SOCK=3]: %WHITE%%NAME% %YELLOW%[%SOCKETS%]
ItemDisplay[(usk OR uh9 OR ci3) NMAG !ETH SOCK=0]: %WHITE%%NAME%
//Tiara
ItemDisplay[ci2 NMAG !ETH !SOCK=1]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[ci2 NMAG !ETH SOCK=0]: %NAME% [L%ILVL%]
//Masks
ItemDisplay[(msk OR xsk) NMAG SOCK=3 !ETH]: %NAME% [%SOCKETS%]
///EQ2 BODY ARMORS
//92+ base hide
ItemDisplay[EQ2 CLVL>91 ELT NMAG ETH SOCK>2]: %GRAY%ETH %DGREEN%%NAME%%DGREEN%[%SOCKETS%]
ItemDisplay[EQ2 CLVL>91 ELT NMAG ETH SOCK=0 ED>9]: %GRAY%ETH %DGREEN%%NAME%%BLUE% 10+ED%DGREEN%[%SOCKETS%]
ItemDisplay[EQ2 CLVL>91 ELT NMAG !ETH SOCK>2 (uui OR uea OR ula OR utu OR urs OR utp)]: %DGREEN%%NAME%%DGREEN%[%SOCKETS%]
ItemDisplay[EQ2 CLVL>91 ELT NMAG !ETH SOCK=0 ED>9 (uui OR uea OR ula OR utu OR urs OR utp)]: %DGREEN%%NAME%%BLUE% 10+ED%DGREEN%[%SOCKETS%]
ItemDisplay[EQ2 CLVL>91 NMAG]:
//All elite (!Shadow/Sacred/Hellforged)
ItemDisplay[EQ2 !uar !uld ELT NMAG ETH !SOCK=1 ED=15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED%PURPLE%[%SOCKETS%]
ItemDisplay[EQ2 !uar !uul !uld ELT NMAG ETH !SOCK=1 ED>0 ED<15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED%RED%[%SOCKETS%]
ItemDisplay[EQ2 !uth !ult !uar !uld ELT NMAG !ETH !SOCK=1 ED=15]: %DGREEN%%NAME%%BLUE% +15ED%PURPLE%[%SOCKETS%]
ItemDisplay[EQ2 !uth !ult !uar !uul !uld ELT NMAG !ETH !SOCK=1 ED>0 ED<15]: %DGREEN%%NAME%%BLUE% +ED%RED%[%SOCKETS%]
ItemDisplay[EQ2 !uar !uul !uld ELT NMAG ETH !SOCK=1]: ETH %NAME% [%SOCKETS%]
ItemDisplay[EQ2 !uth !ult !uar !uul !uld ELT NMAG !ETH !SOCK=1]: %NAME% [%SOCKETS%]
//Dusk Shroud/Great Hauberk/Archon Plate/Sacred Armor
ItemDisplay[(utp OR uui OR urs) NMAG ETH !SOCK=1 ED=14]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +14ED%PURPLE%[%SOCKETS%]
ItemDisplay[(utp OR uui OR urs) NMAG !ETH !SOCK=1 ED=14]: %DGREEN%%NAME%%BLUE% +14ED%PURPLE%[%SOCKETS%]
//Archon Plate
ItemDisplay[utp NMAG ETH !SOCK=1 ED=13]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +13ED%PURPLE%[%SOCKETS%]
ItemDisplay[utp NMAG !ETH !SOCK=1 ED=13]: %DGREEN%%NAME%%BLUE% +13ED%PURPLE%[%SOCKETS%]
///HIGH DEF ARMORS (MAX 5% FROM HIGHEST NON ED DEF)
ItemDisplay[uui NMAG ETH !SOCK=1 DEF>664]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uui NMAG !ETH !SOCK=1 DEF>439]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uea NMAG ETH !SOCK=1 DEF>668]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uea NMAG !ETH !SOCK=1 DEF>441]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ula NMAG ETH !SOCK=1 DEF>674]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ula NMAG !ETH !SOCK=1 DEF>445]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[utu NMAG ETH !SOCK=1 DEF>684]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[utu NMAG !ETH !SOCK=1 DEF>450]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ung NMAG ETH !SOCK=1 DEF>695]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ung NMAG !ETH !SOCK=1 DEF>460]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ucl NMAG ETH !SOCK=1 DEF>705]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ucl NMAG !ETH !SOCK=1 DEF>470]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[urs NMAG ETH !SOCK=1 DEF>710]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[urs NMAG !ETH !SOCK=1 DEF>459]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uhn NMAG ETH !SOCK=1 DEF>718]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uhn NMAG !ETH !SOCK=1 DEF>475]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[upl NMAG ETH !SOCK=1 DEF>730]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[upl NMAG !ETH !SOCK=1 DEF>485]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uld NMAG ETH SOCK>1 DEF>744]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[ult NMAG ETH !SOCK=1 DEF>754]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uth NMAG ETH !SOCK=1 DEF>768]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[uul uth NMAG ETH]:
ItemDisplay[uul NMAG !ETH]:
//Archon Plate 30%from highest
ItemDisplay[utp NMAG ETH !SOCK=1 DEF>620]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[utp NMAG !ETH !SOCK=1 DEF>444]: %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
//Light Plate/Mage Plate
ItemDisplay[xtp NMAG !ETH !SOCK=1]: %NAME% [%SOCKETS%]
ItemDisplay[xtp NMAG ETH !SOCK=1]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[ltp NMAG !ETH !SOCK=1 CLVL<71]: %NAME% [%SOCKETS%]
ItemDisplay[ltp NMAG ETH !SOCK=1 CLVL<71]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
///EQ3 SHIELDS
//Monarch
ItemDisplay[uit NMAG !ETH ED=15 (SOCK=0 OR SOCK=4)]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[uit NMAG !ETH ED>0 ED<15 (SOCK=0 OR SOCK=4)]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[uit NMAG !ETH SOCK=4]: %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
ItemDisplay[uit NMAG !ETH SOCK=0]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[uit NMAG ETH (SOCK=0 OR SOCK=4)]: %GRAY%ETH %WHITE%%NAME% %YELLOW%[%SOCKETS%]
//Troll Nest
ItemDisplay[ush NMAG ETH ED=15 !SOCK=1]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[ush NMAG ETH ED>0 ED<15 !SOCK=1]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[ush NMAG ETH !SOCK=1]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[ush NMAG !ETH ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[ush NMAG !ETH ED>0 ED<15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[ush NMAG !ETH !SOCK=1]: %NAME% %WHITE%[%SOCKETS%]
//Hyperion
ItemDisplay[urg NMAG ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[urg NMAG ED>0 ED<15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
////WEAPON BASES
///WP1 AXES
//Small Crescent
ItemDisplay[7ax NMAG ETH SOCK=4]: ETH %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[7ax NMAG !ETH SOCK=4]: %NAME% %WHITE%[%SOCKETS%]
//Ettin Axe
ItemDisplay[72a NMAG ETH ED=15 (SOCK=0 OR SOCK>2)]: ETH %NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[72a ETH NMAG ED>0 ED<15 (SOCK=0 OR SOCK>2)]: ETH %NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[72a ETH NMAG (SOCK=0 OR SOCK>2)]: ETH %NAME% %WHITE%[%SOCKETS%]
//Berserker Axe
ItemDisplay[7wa ETH NMAG ED=15 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wa ETH NMAG ED=14 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +14ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wa ETH NMAG ED=13 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +13ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wa ETH NMAG ED>0 ED<13 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7wa ETH NMAG !SOCK=1 !SOCK=2]: %GRAY%ETH %NAME% %RED%[%SOCKETS%]
ItemDisplay[7wa !ETH NMAG ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wa !ETH NMAG ED>0 ED<15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7wa !ETH NMAG (SOCK=0 OR SOCK=5 OR SOCK=6)]: %NAME% %WHITE%[%SOCKETS%]
//Glorious Axe
ItemDisplay[7gi ETH NMAG ED=15 (SOCK=0 OR SOCK>3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7gi ETH NMAG ED>0 ED<15 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gi !ETH NMAG ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7gi !ETH NMAG ED>0 ED<15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gi ETH NMAG (SOCK=0 OR SOCK>3)]: %GRAY%ETH %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
///WP2 MACES
///Flail
//ItemDisplay[fla NMAG ILVL>66]:
ItemDisplay[fla NMAG !ETH ED=15 !SOCK=1]: %GRAY%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[fla NMAG !ETH (SOCK=4 OR SOCK=5)]: %GRAY%%NAME% %YELLOW%[%SOCKETS%]
ItemDisplay[fla NMAG ETH (SOCK=4 OR SOCK=5)]: ETH %GRAY%%NAME% %YELLOW%[%SOCKETS%]
//Scourge
ItemDisplay[7fl NMAG ETH ED=15 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7fl NMAG ETH ED>0 ED<15 SOCK>3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7fl NMAG !ETH ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7fl NMAG !ETH ED>0 ED<15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7fl NMAG ETH SOCK>3]: ETH %NAME% %WHITE%[%SOCKETS%]
//Legendary Mallet
ItemDisplay[7wh NMAG ETH ED=15 !SOCK=1 !SOCK=2 !SOCK=4]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wh NMAG ETH ED>0 ED<15 !SOCK=1 !SOCK=2 !SOCK=4]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7wh NMAG !ETH ED=15 !SOCK=1 !SOCK=2 !SOCK=4]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wh NMAG !ETH ED>0 ED<15 !SOCK=1 !SOCK=2 !SOCK=4]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7wh NMAG ETH !SOCK=1 !SOCK=2 !SOCK=4]]: ETH %NAME% %RED%[%SOCKETS%]
///Thunder Maul
ItemDisplay[7gm NMAG ETH ED=15 (SOCK=0 OR SOCK>4)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7gm NMAG ETH ED>0 ED<15 (SOCK=0 OR SOCK>4)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gm NMAG !ETH ED=15 (SOCK=0 OR SOCK>2)]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7gm NMAG !ETH ED>0 ED<15 (SOCK=0 OR SOCK>2)]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gm NMAG ETH (SOCK=0 OR SOCK=6)]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
///WP3 SWORDS
//Larzuk Spirit
ItemDisplay[(crs OR bsd OR lsd) NMAG SOCK=0 (ILVL>25 AND ILVL<41)]: %DGREEN%%NAME% %WHITE%(4s at Larzuk) %WHITE%[L%ILVL%]
//ItemDisplay[(bsd OR lsd) NMAG ILVL>67 !ETH SOCK=4]:
//Crystal Sword
ItemDisplay[crs NMAG !ETH SOCK=5]: %DGREEN%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[crs NMAG !ETH (SOCK=3 OR SOCK=4)]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[crs NMAG ETH (SOCK=4 OR SOCK=5)]: %GRAY%ETH %DGREEN%%NAME% %WHITE%[%SOCKETS%]
//Broad Sword
ItemDisplay[bsd NMAG !ETH SOCK=4]: %DGREEN%%NAME% %WHITE%[%SOCKETS%]
//Long Sword
ItemDisplay[lsd NMAG ETH SOCK=4 CLVL<76]: %GRAY%ETH %NAME% %WHITE%(Trapsin)[%SOCKETS%]
ItemDisplay[lsd NMAG ETH SOCK=0 CLVL<76]: %GRAY%ETH %NAME% %WHITE%(Trapsin)[%SOCKETS%]
ItemDisplay[lsd NMAG !ETH (SOCK=0 OR SOCK=4) CLVL<76]: %NAME% %WHITE%(Trapsin)[%SOCKETS%]
//Dimensional Blade
ItemDisplay[9cr NMAG !ETH ED=15 !SOCK=1]: %GRAY%%NAME%%BLUE% +15ED %WHITE%[%SOCKETS%]
ItemDisplay[9cr NMAG !ETH (SOCK=3 OR SOCK=5)]: %GRAY%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[9cr NMAG ETH (SOCK=3 OR SOCK=5)]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
///Phase Blade
ItemDisplay[7cr NMAG ED=15 !SOCK=1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7cr NMAG ED=14 !SOCK=1 !SOCK=2]: %DGREEN%%NAME%%BLUE% +14ED %PURPLE%[%SOCKETS%]
ItemDisplay[7cr NMAG ED>0 ED<14 !SOCK=1 !SOCK=2]: %DGREEN%%NAME%%BLUE% +ED %YELLOW%[%SOCKETS%]
ItemDisplay[7cr NMAG !SOCK=1 !SOCK=2]: %DGREEN%%NAME% %WHITE%[%SOCKETS%]
///Conquest Sword (Lawbringer for A3 merc)
ItemDisplay[7bs NMAG ETH ED=15 SOCK=3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7bs NMAG ETH ED>0 ED<15 SOCK=3]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7bs NMAG ETH SOCK=3]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
ItemDisplay[7bs NMAG !ETH ED=15 !SOCK=1]: %GRAY%%NAME%%BLUE% +15ED %WHITE%[%SOCKETS%]
//Cryptic Sword (Lawbringer for A3 merc)
ItemDisplay[7ls NMAG ETH ED=15 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7ls NMAG ETH ED>0 ED<15 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7ls NMAG ETH (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
ItemDisplay[7ls NMAG !ETH ED=15 (SOCK=0 OR SOCK=3)]: %DGREEN%%NAME%%BLUE% +15ED %YELLOW%[%SOCKETS%]
ItemDisplay[7ls NMAG !ETH ED=15 !SOCK=0 !SOCK=1 !SOCK=3]: %DGREEN%%NAME%%BLUE% +15ED %WHITE%[%SOCKETS%]
//Mythical Sword (Lawbringer)
ItemDisplay[7wd NMAG ETH ED=15 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7wd NMAG ETH ED>0 ED<15 (SOCK=0 OR SOCK=3)]: ETH %NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7wd NMAG ETH (SOCK=0 OR SOCK=3)]: ETH %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[7wd NMAG !ETH ED=15 !SOCK=1]: %GRAY%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
//Legend Sword (Lawbringer for A5 merc) 
ItemDisplay[72h NMAG ETH ED=15 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[72h NMAG ETH ED>0 ED<15 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[72h NMAG !ETH ED=15 !SOCK=1 CLVL<71]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[72h NMAG !ETH ED>0 ED<15 !SOCK=1 CLVL<71]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[72h NMAG ETH (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
ItemDisplay[72h NMAG !ETH (SOCK=0 OR SOCK=3) CLVL<71]: %WHITE%%NAME% %WHITE%[%SOCKETS%]
//Colossus Sword
ItemDisplay[7fb NMAG ETH ED=15 SOCK>2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7fb NMAG !ETH ED=15 !SOCK=1 !SOCK=2]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7fb NMAG !ETH ED=15 SOCK=2]: %DGREEN%%NAME%%BLUE% +15ED %YELLOW%[%SOCKETS%]
ItemDisplay[7fb NMAG ETH ED>0 ED<15 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7fb NMAG !ETH ED>0 ED<15 SOCK>2]: %DGREEN%%NAME%%BLUE% +ED %YELLOW%[%SOCKETS%]
ItemDisplay[7fb NMAG ETH ED=15 SOCK=0]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7fb NMAG ETH !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME% %WHITE%[%SOCKETS%]
///Colossus Blade
ItemDisplay[7gd NMAG !ETH ED=15 SOCK>1]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7gd NMAG !ETH ED>0 ED<15 SOCK>2]: %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gd NMAG ETH ED=15 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7gd NMAG ETH ED>0 ED<15 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7gd NMAG ETH !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
///WP4 DAGGERS
///WP5 THROWING
///WP6 JAVELINS(NON AMA)
///WP7 SPEARS(NON AMA)
//Mancatcher
ItemDisplay[7br NMAG ETH (SOCK=0 OR SOCK>3) ED=15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7br NMAG ETH (SOCK=0 OR SOCK>3) ED>0 ED<15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7br NMAG !ETH (SOCK=0 OR SOCK>3) ED=15]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7br NMAG ETH (SOCK=0 OR SOCK>3)]: %GRAY%ETH %DGREEN%%NAME% %WHITE%[%SOCKETS%]
//Ghost Spear
ItemDisplay[7st NMAG ETH (SOCK=0 OR SOCK>3) ED=15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7st NMAG ETH (SOCK=0 OR SOCK>3) ED>0 ED<15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7st NMAG !ETH (SOCK=0 OR SOCK>3) ED=15]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7st NMAG (SOCK=0 OR SOCK=4)]: %NAME% [%SOCKETS%]
//War Pike
ItemDisplay[7p7 NMAG ETH (SOCK=0 OR SOCK>4) ED=15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7p7 NMAG ETH (SOCK=0 OR SOCK>4) ED>0 ED<15]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +ED %PURPLE%[%SOCKETS%]
ItemDisplay[7p7 NMAG !ETH (SOCK=0 OR SOCK>3) ED=15]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[7p7 NMAG !ETH (SOCK=0 OR SOCK>3) ED>0 ED<15]: %GRAY%%NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[7p7 NMAG ETH (SOCK=0 OR SOCK=6)]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[7p7 NMAG (SOCK=0 OR SOCK=4)]: %NAME% [%SOCKETS%]
///WP8 POLEARMS
//Thresher+Giant Thresher
ItemDisplay[7wc NMAG ETH (SOCK=0 OR SOCK>2)]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[7wc NMAG !ETH (SOCK=0 OR SOCK>2)]: %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
ItemDisplay[7s8 NMAG ETH (SOCK=0 OR SOCK>2)]: %GRAY%ETH %DGREEN%%NAME% %PURPLE%[%SOCKETS%]
ItemDisplay[7s8 NMAG !ETH (SOCK=0 OR SOCK>2)]: %DGREEN%%NAME% %WHITE%[%SOCKETS%]
//Colossus Voulge
ItemDisplay[7vo NMAG ETH (SOCK=0 OR SOCK=4)]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
ItemDisplay[7vo NMAG !ETH SOCK=4]: %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
//Cryptic Axe+Great Poleaxe
ItemDisplay[(7pa OR 7h7) NMAG ETH (SOCK=0 OR SOCK>3)]: %GRAY%ETH %DGREEN%%NAME% %RED%[%SOCKETS%]
ItemDisplay[(7pa OR 7h7) NMAG !ETH SOCK>3]: %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
//Norm+Exceptional bases (-Bardiche/Lochaber Axe)
ItemDisplay[WP8 EXC !9b7 ETH NMAG SOCK=4]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP8 EXC !9b7 !ETH NMAG SOCK=4]: %GRAY%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP8 NORM !bar ETH NMAG SOCK=4]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP8 NORM !bar !ETH NMAG SOCK=4]: %GRAY%%NAME% %WHITE%[%SOCKETS%]
///WP9 BOWS(NON AMA)
ItemDisplay[WP9 !CL7 ELT NMAG ED=15 SOCK>3]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[WP9 !CL7 ELT NMAG ED>0 ED<15 SOCK>3]: %NAME%%BLUE% +ED %YELLOW%[%SOCKETS%]
ItemDisplay[WP9 !CL7 !6sb ELT NMAG ED=15 SOCK=0]: %DGREEN%%NAME%%BLUE% +15ED %RED%[%SOCKETS%]
ItemDisplay[WP9 !CL7 !6sb ELT NMAG ED>0 ED<15 SOCK=0]: %NAME%%BLUE% +ED %YELLOW%[%SOCKETS%]
ItemDisplay[WP9 !CL7 ELT NMAG SOCK>3]: %GRAY%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP9 !CL7 ELT NMAG ED=15 (SOCK=2 OR SOCK=3)]: %DGREEN%%NAME%%BLUE% +15ED %WHITE%[%SOCKETS%]
ItemDisplay[WP9 NORM NMAG SOCK=4]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP9 (8sb OR 8hb OR 8lb) NMAG SOCK=4]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[hbw NMAG SOCK=4]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[WP9 !CL7 NMAG ILVL>55]:
////WP10 CROSSBOWS
ItemDisplay[WP10 NMAG ED>9 ED<16 SOCK=4]: %NAME%%BLUE% +ED %WHITE%[%SOCKETS%]
///WP11 STAVES
//Seraph rod
ItemDisplay[7qs NMAG ETH (SOCK=0 OR SOCK=3)]: %GRAY%ETH %ORANGE%%NAME% %DGREEN%[%SOCKETS%]
//+3 ES+Shiver = GG Memory
ItemDisplay[WP11 NMAG SOCK=4 (SK58>2 AND SK50>0)]: %ORANGE%¤ GG MEMORY BASE [%SOCKETS%] ¤
ItemDisplay[(cst OR bst OR 8cs OR 8bs OR 6cs OR 6bs) NMAG !SUP SOCK=0 (SK58>2 AND SK50>0)]: %ORANGE%¤ GG MEMORY BASE [%SOCKETS%] ¤
ItemDisplay[(wst OR 8ws OR 6ws) NMAG !SUP SOCK=0 (SK58>2 AND SK50>0)]: %ORANGE%¤¤¤ GG MEMORY BASE [%SOCKETS%] ¤¤¤
//+3 ES = Memory
ItemDisplay[WP11 NMAG SOCK=4 SK58>2]: %ORANGE%%NAME% +3 Energy Shield [%SOCKETS%] ¤
ItemDisplay[(cst OR bst OR 8cs OR 8bs OR 6cs OR 6bs) NMAG !SUP SOCK=0 SK58>2]: %WHITE%%NAME% %ORANGE%+3 Energy Shield [%SOCKETS%] ¤
ItemDisplay[(wst OR 8ws OR 6ws) NMAG !SUP SOCK=0 SK58>2]: %WHITE%%NAME% %ORANGE%+3 Energy Shield (Cube for 4sox)[%SOCKETS%] ¤
//+2 ES = Memory
ItemDisplay[WP11 NMAG SOCK=4 SK58=2 CLVL<86]: %NAME% %ORANGE%+2 Energy Shield%RED%[%SOCKETS%]
ItemDisplay[(cst OR bst OR 8cs OR 8bs OR 6cs OR 6bs) NMAG !SUP SOCK=0 SK58=2 CLVL<86]: %NAME% %ORANGE%+2 Energy Shield%RED%[%SOCKETS%]
ItemDisplay[(wst OR 8ws OR 6ws) NMAG !SUP SOCK=0 SK58=2 CLVL<86]: %NAME% %ORANGE%+2 Energy Shield (Cube for 4sox)%RED%[%SOCKETS%]
//+1 ES = Memory - Early ladder
ItemDisplay[WP11 NMAG SOCK=4 SK58=1]: %NAME% %ORANGE%+1 Energy Shield%RED%[%SOCKETS%]
ItemDisplay[(cst OR bst OR 8cs OR 8bs OR 6cs OR 6bs) NMAG !SUP SOCK=0 SK58=1]: %NAME% %ORANGE%+1 Energy Shield%RED%[%SOCKETS%]
ItemDisplay[(wst OR 8ws OR 6ws) NMAG !SUP SOCK=0 SK58=1]: %NAME% %ORANGE%+1 Energy Shield (Cube for 4sox)%RED%[%SOCKETS%]
//+3 Lightning Surge = Memory
ItemDisplay[WP11 NMAG (SOCK=0 OR SOCK=4) SK49>2]: %DGREEN%%NAME% %ORANGE%+3 Lightning Surge%WHITE%[%SOCKETS%]
ItemDisplay[(cst OR bst OR 8cs OR 8bs OR 6cs OR 6bs) NMAG (SOCK=0 OR SOCK=4) SK49>2]: %DGREEN%%NAME% %ORANGE%+3 Lightning Surge%WHITE%[%SOCKETS%]
ItemDisplay[(wst OR 8ws OR 6ws) NMAG (SOCK=0 OR SOCK=4) SK49>2]: %DGREEN%%NAME% %ORANGE%+3 Lightning Surge%WHITE%[%SOCKETS%]
//+3 Skill = Leaf
ItemDisplay[WP11 NMAG SOCK=2 SK52>2 SOCK=2]: %DGREEN%%NAME% %ORANGE%+3 Enflame %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SOCK=2 SK47>2 SOCK=2]: %DGREEN%%NAME% %ORANGE%+3 Fire Ball %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SOCK=2 SK46>2 SOCK=2]: %DGREEN%%NAME% %ORANGE%+3 Immolate %WHITE%[%SOCKETS%]
//Elite ETH Staff
ItemDisplay[6ws NMAG ETH SOCK=6]: %GRAY%ETH %DGREEN%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[(6cs OR 6bs OR 6ws) NMAG ETH ED=15 SOCK=4]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+15ED %PURPLE%[%SOCKETS%]
ItemDisplay[(6cs OR 6bs OR 6ws) NMAG ETH SOCK=4]: %GRAY%ETH %DGREEN%%NAME% %WHITE%[%SOCKETS%]
ItemDisplay[(6cs OR 6bs) NMAG ETH ED=15 SOCK=0]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+15ED %PURPLE%[%SOCKETS%]
ItemDisplay[(6cs OR 6bs OR 6ws) NMAG ETH SOCK=0]: %GRAY%ETH %NAME% %WHITE%[%SOCKETS%]
//Leveling Staff
ItemDisplay[WP11 NMAG SK38>2 ILVL<81]: %NAME% %ORANGE%+3 Charged Bolt %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK44>2 ILVL<81]: %NAME% %ORANGE%+3 Frost Nova %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK47>2 ILVL<81]: %NAME% %ORANGE%+3 Fire Ball %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK46>2 ILVL<81]: %NAME% %ORANGE%+3 Immolate %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK38=2 ILVL<67]: %NAME% %ORANGE%+2 Charged Bolt %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK44=2 ILVL<67]: %NAME% %ORANGE%+2 Frost Nova %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK47=2 ILVL<67]: %NAME% %ORANGE%+2 Fire Ball %WHITE%[%SOCKETS%]
ItemDisplay[WP11 NMAG SK46=2 ILVL<67]: %NAME% %ORANGE%+2 Immolate %WHITE%[%SOCKETS%]
///WP12 WANDS
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK67>2 AND SK84>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth +3 Bone Spear %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK92>2 AND SK83>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova +3 Desecrate %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK67>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK84>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Bone Spear +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK92>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK83>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Desecrate +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK94>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Fire Golem +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG (SK74>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Corpse Explosion +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK67>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK73>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Deadly Poison %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK84>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Bone Spear %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK92>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK83>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Desecrate %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK94>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Fire Golem %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK74>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Corpse Explosion %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK79>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Convocation %RED%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK93>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Bone Spirit %RED%[%SOCKETS%]
//WANDS LEVELING
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK67=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Teeth %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK73=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Deadly Poison %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK84=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Bone Spear %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK92=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Poison Nova %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK83=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Desecrate %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK74=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Corpse Explosion %YELLOW%[%SOCKETS%]
ItemDisplay[WP12 !wnd !ywn !9wn NMAG SK79=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Convocation %YELLOW%[%SOCKETS%]
///WP13 SCEPTERS
//Magic Scepters
ItemDisplay[WP13 !ETH (TABSK25>2 AND SK102>2)]: %NAME% %ORANGE%+3 Offensive +3 Holy Fire%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>1 AND SK102>1)]: %NAME% %ORANGE%2+ Offensive 2+ Holy Fire%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK102>1)]: %NAME% %ORANGE%+2 Paladin 2+ Holy Fire%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>2 AND SK114>2)]: %NAME% %ORANGE%+3 Offensive +3 Holy Freeze%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>1 AND SK114>1)]: %NAME% %ORANGE%2+ Offensive 2+ Holy Freeze%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK114>1)]: %NAME% %ORANGE%+2 Paladin 2+ Holy Freeze%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>2 AND SK118>2)]: %NAME% %ORANGE%+3 Offensive +3 Holy Shock%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>1 AND SK118>1)]: %NAME% %ORANGE%2+ Offensive 2+ Holy Shock%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK118>1)]: %NAME% %ORANGE%+2 Paladin 2+ Holy Shock%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>2 AND SK119>2)]: %NAME% %ORANGE%+3 Offensive +3 Sanctuary%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK25>1 AND SK119>1)]: %NAME% %ORANGE%2+ Offensive 2+ Sanctuary%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK119>2)]: %NAME% %ORANGE%+2 Paladin Skills +3 Sanctuary%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK24>2 AND SK121>2)]: %NAME% %ORANGE%+3 Combat +3 FoH%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK24>1 AND SK121>1)]: %NAME% %ORANGE%2+ Combat 2+ FoH%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK121>1)]: %NAME% %ORANGE%+2 Paladin Skills 2+ FoH%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK24>2 AND SK101>2)]: %NAME% %ORANGE%+3 Combat +3 Holy Bolt%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 !ETH (CLSK3=2 AND SK112>1)]: %NAME% %ORANGE%+2 Paladin Skills 2+ Blessed Hammer%RED%[%SOCKETS%]
ItemDisplay[WP13 !ETH (TABSK24>1 AND SK112>1)]: %NAME% %ORANGE%2+ Combat 2+ Blessed Hammer%RED%[%SOCKETS%]
//Non Magic Scepters
ItemDisplay[WP13 NMAG !ETH SK117>2 SOCK=5]: %NAME% %ORANGE%+3 Holy Shield%PURPLE%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK112>2 (SOCK=0 OR SOCK=4)]: %NAME% %ORANGE%+3 Blessed Hammer%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK113>2 (SOCK=0 OR SOCK=4)]: %NAME% %ORANGE%+3 Concentration%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK101>2 (SOCK=0 OR SOCK>2)]: %NAME% %ORANGE%+3 Holy Bolt%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK118>2 (SOCK=0 OR SOCK>2)]: %NAME% %ORANGE%+3 Holy Shock%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK118>2 (SOCK=0 OR SOCK>2)]: %NAME% %ORANGE%+3 Sanctuary %RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK114>2 (SOCK=0 OR SOCK>2)]: %NAME% %ORANGE%+3 Holy Freeze%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK102>2 (SOCK=0 OR SOCK>2)]: %NAME% %ORANGE%+3 Holy Fire%RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK117=2 SOCK=5]: %NAME% %ORANGE%+2 Holy Shield %RED%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK102=2 ILVL<67]: %NAME% %ORANGE%+2 Holy Fire %WHITE%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK112=2 ILVL<67]: %NAME% %ORANGE%+2 Blessed Hammer%WHITE%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK113=2 ILVL<67]: %NAME% %ORANGE%+2 Concentration%WHITE%[%SOCKETS%]
ItemDisplay[WP13 NMAG !ETH SK101=2 ILVL<67]: %NAME% %ORANGE%+2 Holy Bolt%WHITE%[%SOCKETS%]
ItemDisplay[WP13 NMAG SOCK=4]: %NAME% %ORANGE%Holy Thunder Base %WHITE%[%SOCKETS%]
//Scepters no skills
ItemDisplay[(7ws OR 7qs) ETH NMAG ED=15 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% +15ED %DGREEN%[%SOCKETS%]
ItemDisplay[(7ws OR 7qs) ETH NMAG ED>0 ED<15 !SOCK=1 !SOCK=2]: ETH %NAME%%BLUE% +ED %DGREEN%[%SOCKETS%]
ItemDisplay[7ws !ETH NMAG ED=15 !SOCK=1 !SOCK=2]: %DGREEN%%NAME%%BLUE% +15ED %PURPLE%[%SOCKETS%]
ItemDisplay[7ws !ETH NMAG ED>0 ED<15 !SOCK=1 !SOCK=2]: %NAME%%BLUE% +ED %RED%[%SOCKETS%]
ItemDisplay[(7ws OR 7qs) ETH NMAG !SOCK=1 !SOCK=2]: ETH %NAME% %DGREEN%[%SOCKETS%]
ItemDisplay[7ws !ETH NMAG]: %NAME% %WHITE%[%SOCKETS%]
///CL1 DRUID PELTS NON MAGIC
ItemDisplay[CL1 NMAG !ETH (SK250>2 AND SK249>2)]: %DGREEN%%NAME% %ORANGE%+3 Hurricane +3 Armageddon%PURPLE%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH (SK250>2 AND SK245>2)]: %DGREEN%%NAME% %ORANGE%+3 Hurricane +3 Tornado%PURPLE%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK221>2]: %DGREEN%%NAME% %ORANGE%+3 Raven%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK238>2]: %DGREEN%%NAME% %ORANGE%+3 Rabies%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK239>2]: %DGREEN%%NAME% %ORANGE%+3 Fire Claws%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK229>2]: %DGREEN%%NAME% %ORANGE%+3 Molten Boulder%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK243>2]: %DGREEN%%NAME% %ORANGE%+3 Shockwave%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK244>2]: %DGREEN%%NAME% %ORANGE%+3 Volcano%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK245>2]: %DGREEN%%NAME% %ORANGE%+3 Tornado%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK250>2]: %DGREEN%%NAME% %ORANGE%+3 Hurricane%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK247>2]: %DGREEN%%NAME% %ORANGE%+3 Grizzly%RED%[%SOCKETS%]
ItemDisplay[CL1 NMAG !ETH SK225>2]: %DGREEN%%NAME% %ORANGE%+3 Firestorm%RED%[%SOCKETS%]
///DRUID PELTS LEVELING
ItemDisplay[CL1 NMAG !ETH SK234>2 ILVL<81]: %NAME% %ORANGE%+3 Fissure%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK221=2 ILVL<67]: %NAME% %ORANGE%+2 Raven%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK238=2 ILVL<67]: %NAME% %ORANGE%+2 Rabies%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK239=2 ILVL<67]: %NAME% %ORANGE%+2 Fire Claws%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK244=2 ILVL<67]: %NAME% %ORANGE%+2 Volcano%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK245=2 ILVL<67]: %NAME% %ORANGE%+2 Tornado%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK250=2 ILVL<67]: %NAME% %ORANGE%+2 Hurricane%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK225=2 ILVL<67]: %NAME% %ORANGE%+2 Firestorm%YELLOW%[%SOCKETS%]
ItemDisplay[CL1 !ETH SK234=2 ILVL<67]: %NAME% %ORANGE%+2 Fissure%YELLOW%[%SOCKETS%]
///CL2 BARBARIAN PRIMAL HELMS NON MAGIC
ItemDisplay[CL2 NMAG !ETH (SK154>2 AND SK150>2)]: %DGREEN%%NAME% %ORANGE%+3 War Cry and +3 Grim Ward%PURPLE%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (SK154>1 AND SK150>1)]: %DGREEN%%NAME% %ORANGE%2+ War Cry and 2+ Grim Ward%RED%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (SK154>2 AND SK149>2)]: %DGREEN%%NAME% %ORANGE%+3 War Cry and +3 BO%PURPLE%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (TABSK34>2 AND SK149>2)]: %DGREEN%%NAME% %ORANGE%+3 Warcries +3 BO%PURPLE%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (TABSK34>2 AND SK150>2)]: %DGREEN%%NAME% %ORANGE%+3 Warcries +3 War Cry%PURPLE%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (CLSK4=2 AND SK150>1)]: %DGREEN%%NAME% %ORANGE%+2 Barb 2+ War Cry%RED%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH (TABSK34>1 AND SK150>1)]: %DGREEN%%NAME% %ORANGE%2+ Warcries 2+ War Cry%RED%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH SK154>2]: %DGREEN%%NAME% %ORANGE%+3 War Cry%YELLOW%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH SK133>2]: %DGREEN%%NAME% %ORANGE%+3 Ethereal Throw%YELLOW%[%SOCKETS%]
ItemDisplay[CL2 NMAG !ETH SK149>2]: %DGREEN%%NAME% %ORANGE%+3 Battle Orders%YELLOW%[%SOCKETS%]
///CL3 PALADIN SHIELDS
ItemDisplay[CL3 NMAG !ETH RES=45 !SOCK=1]: %DGREEN%%NAME%%BLUE% 45+ %PURPLE%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH RES>39 RES<45 !SOCK=1]: %DGREEN%%NAME%%BLUE% 40-44+ %RED%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH RES>34 RES<40 !SOCK=1]: %DGREEN%%NAME%%BLUE% 35-39+ %YELLOW%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH RES=45 SOCK=0]: %DGREEN%%NAME%%BLUE% 45+ %PURPLE%[%SOCKETS%]
ItemDisplay[CL3 NMAG ELT ETH RES=45 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% 45+ %PURPLE%[%SOCKETS%]
ItemDisplay[CL3 NMAG ELT ETH RES>39 RES<45 !SOCK=1 !SOCK=2]: %GRAY%ETH %DGREEN%%NAME%%BLUE% 40-44+ %RED%[%SOCKETS%]
//AR shields
ItemDisplay[CL3 NMAG !ETH ITEMSTAT68=121 !SOCK=1]: %DGREEN%%NAME%%BLUE% 121AR %RED%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH ITEMSTAT68=120 !SOCK=1]: %DGREEN%%NAME%%BLUE% 120AR %RED%[%SOCKETS%]
ItemDisplay[CL3 NMAG ELT ETH ITEMSTAT68=121 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% 121AR %RED%[%SOCKETS%]
ItemDisplay[CL3 NMAG ELT ETH ITEMSTAT68=120 (SOCK=0 OR SOCK=3)]: %GRAY%ETH %DGREEN%%NAME%%BLUE% 120AR %RED%[%SOCKETS%]
ItemDisplay[NMAG pab !ETH ITEMSTAT17>49 !SOCK=1 !SOCK=2]: %DGREEN%%NAME%%BLUE% +ED%RED%[%SOCKETS%]
//Low
ItemDisplay[CL3 NMAG !ETH RES>19 RES<35 !SOCK=1]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH RES>0 RES<20 SOCK=4]: %NAME% %WHITE%[%SOCKETS%]
ItemDisplay[CL3 NMAG !ETH ILVL>66 RES>0 RES<20 !SOCK=4]:
ItemDisplay[CL3 NMAG ETH ILVL>66 RES>0 RES<40]:
ItemDisplay[CL3 NMAG ILVL>66 ITEMSTAT68<120 !SOCK=4]:
///CL4 NECRO SHRUNKEN HEADS
ItemDisplay[CL4 NMAG !ETH (SK67>2 AND SK84>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth +3 Bone Spear %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK92>2 AND SK83>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova +3 Desecrate %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK67>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK84>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Bone Spear +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK92>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK83>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Desecrate +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH (SK94>2 AND SK79>2) !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Fire Golem +3 Convo %PURPLE%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK67>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Teeth %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK73>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Deadly Poison %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK84>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Bone Spear %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK92>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Poison Nova %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK83>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Desecrate %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK74>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Corpse Explosion %RED%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK94>2 !SOCK=1]: %DGREEN%%NAME% %ORANGE%+3 Fire Golem %YELLOW%[%SOCKETS%]
//NECRO SHRUNKEN HEADS LEVELING
ItemDisplay[CL4 NMAG !ETH SK67=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Teeth %YELLOW%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK73=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Deadly Poison %YELLOW%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK84=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Bone Spear %YELLOW%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK92=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Poison Nova %YELLOW%[%SOCKETS%]
ItemDisplay[CL4 NMAG !ETH SK83=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Desecrate %YELLOW%[%SOCKETS%]
///CL5 ASSASSIN CLAWS
//Magic Claws
ItemDisplay[CL5 (TABSK48>2 AND SK271>2)]: %NAME% %ORANGE%+3 Traps +3 Lightning Sentry%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>1 AND SK271>1)]: %NAME% %ORANGE%2+ Traps 2+ Lightning Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK271>2)]: %NAME% %ORANGE%+2 Assa Skills +3 Lightning Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK271>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Lightning Sentry%YELLOW%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK261>2)]: %NAME% %ORANGE%+3 Traps +3 Charged Bolt Sentry%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>1 AND SK261>1)]: %NAME% %ORANGE%2+ Traps 2+ Charged Bolt Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK261>2)]: %NAME% %ORANGE%+2 Assa Skills +3 Charged Bolt Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6>1 AND SK261>1)]: %NAME% %ORANGE%2+ Assa Skills 2+ Charged Bolt Sentry%YELLOW%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK262>2)]: %NAME% %ORANGE%+3 Traps +3 Wake of Fire%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>1 AND SK262>1)]: %NAME% %ORANGE%2+ Traps 2+ Wake of Fire%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK262>2)]: %NAME% %ORANGE%+2 Assa Skills +3 Wake of Fire%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6>1 AND SK262>1)]: %NAME% %ORANGE%2+ Assa Skills 2+ Wake of Fire%YELLOW%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK272>2)]: %NAME% %ORANGE%+3 Traps +3 Inferno Sentry%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK272>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Inferno Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK251>2)]: %NAME% %ORANGE%+3 Traps +3 Fire Blast%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK251>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Fire Blast%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK49>2 AND SK278>2)]: %NAME% %ORANGE%+3 ShadowDisc +3 Venom%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK278>2)]: %NAME% %ORANGE%+2 Assa Skills +3 Venom%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK49>1 AND SK278>1)]: %NAME% %ORANGE%2+ ShadowDisc 2+ Venom%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK49>2 AND SK267>2)]: %NAME% %ORANGE%+3 ShadowDisc +3 Fade%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK267>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Fade%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK49>2 AND SK258>2)]: %NAME% %ORANGE%+3 ShadowDisc +3 Burst of Speed%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK258>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Burst of Speed%RED%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK276>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Death Sentry%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK276>2)]: %NAME% %ORANGE%+3 Traps +3 Death Sentry%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK257>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Blade Throw%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK257>2)]: %NAME% %ORANGE%+3 Traps +3 Blade Throw%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 (CLSK6=2 AND SK277>1)]: %NAME% %ORANGE%+2 Assa Skills 2+ Blade Shield%RED%[%SOCKETS%]
ItemDisplay[CL5 (TABSK48>2 AND SK277>2)]: %NAME% %ORANGE%+3 Traps +3 Blade Shield%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 !ETH (TABSK50>2 AND SK269>2)]: %NAME% %ORANGE%+3 Martial Arts +3 Emberstorm%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 TABSK48>2]: %NAME% %ORANGE%+3 Traps%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 7tw OR 7lw) MAG !ETH !ID]: %BLUE%%NAME%
//Non magic claws
ItemDisplay[(7xf OR 7qr OR 7ar) NMAG ETH !SOCK=1 !SOCK=2 SK273>2]: %GRAY%ETH %WHITE%%NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[(7xf OR 7qr OR 7ar) NMAG !ETH !SOCK=1 !SOCK=2 SK273>2]: %NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG ETH !SOCK=1 !SOCK=2 SK273>2]: %GRAY%ETH %WHITE%%NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !SOCK=1 !SOCK=2 SK273>2]: %NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[CL5 NMAG ETH CLVL<61 !SOCK=1 !SOCK=2 SK273>2]: %GRAY%ETH %WHITE%%NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[CL5 NMAG !ETH CLVL<61 !SOCK=1 !SOCK=2 SK273>2]: %NAME% %ORANGE%+3 Mind Blast%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 (SK271>2 AND SK251>2)]: %NAME% %ORANGE%+3 Lightning Sentry +3 Fire Blast%PURPLE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 (SK271>2 AND SK262>2)]: %NAME% %ORANGE%+3 Lightning Sentry +3 Wake of Fire%PURPLE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 (SK261>2 AND SK251>2)]: %NAME% %ORANGE%+3 Charged Bolt Sentry +3 Fire Blast%PURPLE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 (SK261>2 AND SK262>2)]: %NAME% %ORANGE%+3 Charged Bolt Sentry +3 Wake of Fire%PURPLE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 (SK278>2 AND SK277>2)]: %NAME% %ORANGE%+3 Venom +3 Blade Shield %PURPLE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK271>2]: %NAME% %ORANGE%+3 Lightning Sentry%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK278>2]: %NAME% %ORANGE%+3 Venom%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK267>2]: %NAME% %ORANGE%+3 Fade%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK277>2]: %NAME% %ORANGE%+3 Blade Shield%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK258>2]: %NAME% %ORANGE%+3 Burst of Speed%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK262>2]: %NAME% %ORANGE%+3 Wake of Fire%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK261>2]: %NAME% %ORANGE%+3 Charged Bolt Sentry%WHITE%[%SOCKETS%]
ItemDisplay[(9lw OR 9tw OR 9qr OR 7ar OR 7wb OR 7lw OR 7tw OR 7qr) NMAG !SOCK=2 SK276>2]: %NAME% %ORANGE%+3 Death Sentry%WHITE%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 ED=15 SK274>0]: %NAME% %RED%+15ED %BLUE%BoI ELT Claw%PURPLE%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK277>0 AND SK274>0)]: %NAME%%ORANGE%+BoI&BS Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK278>0)]: %NAME%%ORANGE%+BoI&Venom Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK262>0)]: %NAME%%ORANGE%+BoI&WoF Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK257>0)]: %NAME%%ORANGE%+BoI&BT Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK271>0)]: %NAME%%ORANGE%+BoI&LS Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK261>0)]: %NAME%%ORANGE%+BoI&CBS Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK258>0)]: %NAME%%ORANGE%+BoI&BoS Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK267>0)]: %NAME%%ORANGE%+BoI&Fade Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 (SK274>0 AND SK275>0)]: %NAME%%ORANGE%+BoI&DF Combo%GOLD%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 ED>0 ED<15 SK274>0]: %NAME%%RED% +ED %BLUE%BoI ELT Claw %RED%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 SK274>0]: %NAME% %BLUE%+BoI ELT Claw %YELLOW%[%SOCKETS%]
ItemDisplay[CL5 ELT NMAG !ETH !7xf !7cs !7wb !SOCK=1 !SOCK=2 ED=15]: %NAME% %BLUE%+15ED ELT Claw %PURPLE%[%SOCKETS%]
ItemDisplay[(7ar OR 7qr) NMAG ELT ETH !SOCK=1 !SOCK=2 ED=15]: ETH %NAME%%BLUE% +15ED Blade Assa Claw%PURPLE%[%SOCKETS%]
ItemDisplay[(7ar OR 7qr) NMAG ELT ETH !SOCK=1 !SOCK=2 ED>0 ED<15]: ETH %NAME%%BLUE% +ED Blade Assa Claw%RED%[%SOCKETS%]
ItemDisplay[(7ar OR 7qr) NMAG ELT ETH !SOCK=1 !SOCK=2]: ETH %NAME%%BLUE% Blade Assa Claw%RED%[%SOCKETS%]
ItemDisplay[CL5 NMAG ILVL>40]:
///CL6 SORC ORBS
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 (SK40>2 AND SK52>2)]: %NAME% %ORANGE%+3 Enflame +3 Frigerate%PURPLE%[%SOCKETS%]
ItemDisplay[CL6 (TABSK10>2 AND SK40>2)]: %NAME% %ORANGE%+3 ColdS +3 Frigerate%PURPLE%[%SOCKETS%]
ItemDisplay[CL6 (TABSK10>1 AND SK40>1)]: %NAME% %ORANGE%2+ ColdS 2+ Frigerate%RED%[%SOCKETS%]
ItemDisplay[CL6 (CLSK1=2 AND SK40>1)]: %NAME% %ORANGE%+2 Sorc 2+ Frigerate%RED%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 SK40>2]: %NAME% %ORANGE%+3 Frigerate%YELLOW%[%SOCKETS%]
ItemDisplay[CL6 (TABSK10>1 AND SK50>2)]: %NAME% %ORANGE%+Cold Skills +3 Shiver Armor%RED%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) !SOCK=1 !SOCK=2 SK50>2]: %NAME% %ORANGE%+3 Shiver Armor%WHITE%[%SOCKETS%]
ItemDisplay[CL6 (TABSK8>2 AND SK52>2)]: %NAME% %ORANGE%+3 FireS +3 Enflame%PURPLE%[%SOCKETS%]
ItemDisplay[CL6 (TABSK8>1 AND SK52>1)]: %NAME% %ORANGE%2+ FireS 2+ Enflame%RED%[%SOCKETS%]
ItemDisplay[CL6 (CLSK1=2 AND SK52>2)]: %NAME% %ORANGE%+2 Sorc +3 Enflame%RED%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 SK52>2]: %NAME% %ORANGE%+3 Enflame%YELLOW%[%SOCKETS%]
ItemDisplay[CL6 (TABSK9>1 AND SK57>2)]: %NAME% %ORANGE%+Lightning Skills +3 Discharge%RED%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 SK57>2]: %NAME% %ORANGE%+3 Discharge%YELLOW%[%SOCKETS%]
ItemDisplay[CL6 (TABSK9>1 AND SK58>2)]: %NAME% %ORANGE%+5 or +6 Energy Shield%RED%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 SK58>2]: %NAME% %ORANGE%+3 Energy Shield%YELLOW%[%SOCKETS%]
ItemDisplay[CL6 (TABSK8>2 AND SK62>2)]: %NAME% %ORANGE%+3 FireS +3 Hydra %PURPLE%[%SOCKETS%]
ItemDisplay[CL6 (ob5 OR oba OR obf) NMAG !SOCK=1 !SOCK=2 SK62>2]: %NAME% %ORANGE%+3 Hydra%YELLOW%[%SOCKETS%]
ItemDisplay[CL6 (TABSK10>1 AND SK44>2)]: %NAME% %ORANGE%+Cold Skills +3 Frost Nova%RED%[%SOCKETS%]
ItemDisplay[CL6 NMAG !SOCK=1 !SOCK=2 SK44>2]: %NAME% %ORANGE%+3 Frost Nova%RED%[%SOCKETS%]
//ORBS LEVELING
ItemDisplay[CL6 NMAG SK38>2 ILVL<81]: %GRAY%%NAME% %ORANGE%+3 Charged Bolt%WHITE%[%SOCKETS%]
ItemDisplay[CL6 SK38=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Charged Bolt%WHITE%[%SOCKETS%]
ItemDisplay[CL6 NMAG SK44>2 ILVL<81]: %GRAY%%NAME% %ORANGE%+3 Frost Nova%WHITE%[%SOCKETS%]
ItemDisplay[CL6 SK44=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Frost Nova%WHITE%[%SOCKETS%]
ItemDisplay[CL6 NMAG SK47>2 ILVL<81]: %GRAY%%NAME% %ORANGE%+3 Fire Ball%WHITE%[%SOCKETS%]
ItemDisplay[CL6 SK47=2 ILVL<67]: %GRAY%%NAME% %ORANGE%+2 Fire Ball%WHITE%[%SOCKETS%]
///CL7 AMAZON BOWS
ItemDisplay[(amb OR amc) NMAG ED=15 TABSK0>2 (SOCK=3 OR SOCK=4)]: %DGREEN%%NAME% %BLUE%+15ED +3Bow%PURPLE%[%SOCKETS%]
ItemDisplay[(amb OR amc) NMAG ED=14 TABSK0>2 (SOCK=3 OR SOCK=4)]: %DGREEN%%NAME% %BLUE%+14ED +3Bow%PURPLE%[%SOCKETS%]
ItemDisplay[(amb OR amc) NMAG ED>0 ED<15 TABSK0>2 (SOCK=3 OR SOCK=4)]: %DGREEN%%NAME% %BLUE%+ED +3Bow%RED%[%SOCKETS%]
ItemDisplay[(am1 OR amb OR am6) NMAG TABSK0>2 SOCK=3 CLVL>84]: %DGREEN%%NAME% %ORANGE%Melody Base Ele Bowzon %BLUE%+3Bow%WHITE%[%SOCKETS%]
ItemDisplay[(amb OR amc) NMAG TABSK0>2 SOCK=4]: %DGREEN%%NAME% %BLUE%+3Bow%YELLOW%[%SOCKETS%]
ItemDisplay[am6 NMAG ED=15 TABSK0>2 (SOCK=3 OR SOCK=4)]: %DGREEN%%NAME% %BLUE%+15ED +3Bow%RED%[%SOCKETS%]
ItemDisplay[am6 NMAG ED>0 ED<15 TABSK0>2 (SOCK=3 OR SOCK=4)]: %DGREEN%%NAME% %BLUE%+ED +3Bow%RED%[%SOCKETS%]
ItemDisplay[(amb OR amc) NMAG TABSK0>2 SOCK=0]: %DGREEN%%NAME% %BLUE%+3Bow%WHITE%[%SOCKETS%]
///AMAZON JAVELINS
ItemDisplay[(am5 OR ama OR amf) !UNI ID TABSK2>5]: %NAME% %ORANGE%+6 Jav Skills %PURPLE%[%SOCKETS%]
ItemDisplay[(am5 OR ama OR amf) !UNI ID TABSK2=5]: %NAME% %ORANGE%+5 Jav Skills %RED%[%SOCKETS%]
ItemDisplay[(am5 OR ama OR amf) !UNI ID (TABSK2>2 AND CLSK0=2)]: %NAME% %ORANGE%+3 Jav Skills +2 Ama Skills %RED%[%SOCKETS%]
ItemDisplay[(am5 OR ama OR amf) MAG !ID]: %NAME%
///AMAZON SPEARS
ItemDisplay[CL7 ELT NMAG ETH ED=15 TABSK2>2 SOCK=5]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+15ED %PURPLE%[%SOCKETS%]
ItemDisplay[CL7 ELT NMAG ETH ED=14 TABSK2>2 SOCK=5]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+14ED %PURPLE%[%SOCKETS%]
ItemDisplay[CL7 ELT NMAG ETH ED>0 ED<14 TABSK2>2 SOCK=5]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+ED %RED%[%SOCKETS%]
ItemDisplay[(amd OR ame) ELT NMAG ETH ED=15 TABSK2>2 (SOCK=0 OR SOCK>4)]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+15ED %PURPLE%[%SOCKETS%]
ItemDisplay[(amd OR ame) ELT NMAG ETH ED>0 ED<15 TABSK2>2 (SOCK=0 OR SOCK>4)]: %GRAY%ETH %DGREEN%%NAME% %BLUE%+ED %RED%[%SOCKETS%]
ItemDisplay[(amd OR ame) ELT NMAG ETH TABSK2>2 (SOCK=0 OR SOCK>4)]: %GRAY%ETH %DGREEN%%NAME% %YELLOW%[%SOCKETS%]
////VENDOR ITEMS
ItemDisplay[WP12 NMAG !ETH (wnd OR ywn OR 9wn) ILVL>49 (SK73>0 OR SK79>2 OR SK82>2 OR SK83>1 OR SK85>2 OR SK86>1 OR SK87>0 OR SK88>0 OR SK89>0 OR SK90>1 OR SK91>1 OR SK92>0 OR SK93>0 OR SK94>0 OR SK95>0)]: %NAME% %ORANGE%($%PRICE%)
ItemDisplay[WP12 NMAG !ETH SOCK=1 (SK73>0 OR SK79>2 OR SK82>2 OR SK83>1 OR SK85>2 OR SK86>1 OR SK87>0 OR SK88>0 OR SK89>0 OR SK90>1 OR SK91>1 OR SK92>0 OR SK93>0 OR SK94>0 OR SK95>0)]: %NAME% %ORANGE%($%PRICE%)
ItemDisplay[(7tk OR 7ta OR 7bk) NMAG !ETH !ED=15]: Throw %ORANGE%($%PRICE%)
//6 Socket Weapon Bases
ItemDisplay[WEAPON (7mp OR 7wa OR 7gi OR 7gm OR hal OR 9cr OR 7gd) NMAG SOCK=6]: %GRAY%%NAME% %WHITE%[%SOCKETS%]
////LEVELING
ItemDisplay[EQ1 EXC NMAG CLVL<66 SOCK>1 !ETH]: %NAME% [%SOCKETS%]
ItemDisplay[EQ1 NORM NMAG CLVL<41 SOCK>1 !ETH]: %NAME% [%SOCKETS%]
ItemDisplay[(xui OR xea OR xla OR xtu OR xrs) NMAG CLVL<81 SOCK>1 !ETH]: %NAME% [%SOCKETS%]
ItemDisplay[(qui OR lea OR hla OR stu OR brs) NMAG CLVL<46 SOCK>1 !ETH]: %NAME% [%SOCKETS%]
ItemDisplay[WP9 EXC ELT NMAG CLVL<86 SOCK=3]: %NAME% [%SOCKETS%]
ItemDisplay[WP9 NORM NMAG CLVL<61 SOCK=3]: %NAME% [%SOCKETS%]
ItemDisplay[(am6 OR am7 OR amb OR amc) NMAG CLVL<86 SOCK=3]: %NAME% [%SOCKETS%]
ItemDisplay[(am1 OR am2) NMAG CLVL<61 SOCK=3]: %NAME% [%SOCKETS%]
////CATCHALL/HIDING
ItemDisplay[NMAG !ELT !EXC SOCK=0 !ED>0 ILVL<6 !RW]:
ItemDisplay[NMAG !ELT !EXC SOCK=0 ED>0 ILVL<26 !RW]: %NAME%
///MAGIC
//Armor
ItemDisplay[EQ2 MAG !ID ILVL>65]:
//Shields !monarch !troll nest
ItemDisplay[EQ3 MAG !ID !uit !ush ILVL>65]:
//Gloves/Boots/Belts
ItemDisplay[EQ4 MAG !ID ILVL>54]:
ItemDisplay[EQ5 MAG !ID ILVL>54]:
ItemDisplay[EQ6 MAG !ID ILVL>54]:
//Circlets
ItemDisplay[EQ7 MAG !ETH !ID]: %BLUE%¤ %NAME% ¤
ItemDisplay[EQ7 MAG ETH !ID]: %BLUE%ETH %NAME%
//Helm
ItemDisplay[EQ1 MAG !ID ILVL>54]:
//Staff, Wand, Scepter
ItemDisplay[WP11 MAG !ID ILVL>39]:
ItemDisplay[WP12 MAG !ID ILVL>39]:
ItemDisplay[WP13 MAG !ID ILVL<40]: %BLUE%%NAME%
ItemDisplay[WP13 MAG !ID ILVL>39]:
//Class Specific
ItemDisplay[CL1 MAG !ID ILVL>55]:
ItemDisplay[CL2 MAG !ID ILVL>55]:
ItemDisplay[CL3 MAG !ID ILVL>55]:
ItemDisplay[CL4 MAG !ID ILVL>55]:
ItemDisplay[CL5 MAG !ETH !ID]:
ItemDisplay[CL5 MAG ETH !ID]:
ItemDisplay[CL6 MAG !ID ILVL>55]:
ItemDisplay[CL7 MAG !ID ILVL>55]:
//._.
ItemDisplay[(wst OR 6hx OR dr3 OR bwn OR 9qr OR 8cs OR ywn OR gwn OR ba3 OR dr3 OR ne4 OR dr5 OR wsp OR 9wn OR 8ws) NMAG ILVL>14]:
ItemDisplay[(CL1 OR CL2 OR CL3 OR CL4 OR CL5 OR CL6 OR CL7) NMAG ILVL>14]:
ItemDisplay[(WP11 OR WP12 OR WP13) NMAG ILVL>14]:
ItemDisplay[(WP4 OR WP5 OR WP6 OR WP10) NMAG ILVL>14]:
///NEW CHARACTER/PLAYER EXPERIENCE
ItemDisplay[(ARMOR OR WEAPON) NMAG !RW NORM ILVL<15 SOCK>0 ETH]: ETH %NAME% [%SOCKETS%]
ItemDisplay[(ARMOR OR WEAPON) NMAG !RW NORM ILVL<15 SOCK=0 ETH]:
ItemDisplay[(ARMOR OR WEAPON) NMAG !RW NORM ILVL<15 SOCK>0]: %NAME% [%SOCKETS%]
ItemDisplay[(ARMOR OR WEAPON) NMAG !RW NORM SOCK=0 ILVL<5]: %NAME%
ItemDisplay[(ARMOR OR WEAPON) NMAG !RW NORM SOCK=0 ILVL>4]:
ItemDisplay[(ARMOR OR WEAPON) NMAG ILVL<35 SOCK>1 !RW]: %NAME% [%SOCKETS%]
ItemDisplay[MAG ILVL<7 !ID]: %NAME%
ItemDisplay[MAG ILVL>6 !ID]:
ItemDisplay[MAG ID]: %NAME%
ItemDisplay[NMAG ILVL>6]:
ItemDisplay[ETH SOCK>0]: ETH %NAME% [%SOCKETS%]
ItemDisplay[ETH SOCK=0]: ETH %NAME%
ItemDisplay[SOCK>0]: %NAME% [%SOCKETS%]
//Debug
//ItemDisplay[]: %NAME% %RED%[Report me %CODE% to Gadn]
