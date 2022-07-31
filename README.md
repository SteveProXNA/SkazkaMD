# Skazka
Slavic RGP Adventure game ported to the Sega MegaDrive / Genesis.

![Skazka](https://github.com/SteveProXNA/SkazkaMD/blob/main/img/SkazkaMD.png)

###### RELEASE
Sunday, 31st July 2022

###### INTRO
Skazka is a Slavic RGP Adventure game originally written by Kirils Skrabe in BASIC for the Sega SC-3000 and posted to the SC-3000 Survivors [Facebook](https://bit.ly/3De1P4E) group on March 3rd 2022.  Original source code can be found [here](https://bit.ly/3tGV9J3).

###### PORTS
Saverio Russo [ported](https://bit.ly/3IKJg9x) the game to the SG-1000 using a custom "SC3K DevKit" which I believed is based on "Dear imGUI".
<br />
Then Skazka was ported to the Sega Master System using the [devkitSMS](https://github.com/sverx/devkitSMS).
<br />
Next Skazka has been ported to the Sega MegaDrive / Genesis using the  [SGDK](https://github.com/Stephane-D/SGDK).

###### TOOLS
- Programming:	SGDK
- Language:		C
- Visual Studio 2015
- Graphics:		[RseizeImage.net](https://resizeimage.net) / [BMP converter](https://online-converting.com/image/convert2bmp)
- Music:		Audacity / YouTube
- Emulators:	Fusion / Gens

###### SOURCE CODE
https://github.com/SteveProXNA/SkazkaMD

###### ROM HACKING
You can hack this ROM!  
Download and dump Skazka.sms into Hex Editor, e.g. HxD, and modify the bytes:
- 0x01DE	Delay			Used to speed through any game delay.
- 0x01DF	Invincible		Non-zero value enables invincibility.
- 0x01E0	Current XP		Non-zero sets current experience pts.
- 0x01E1	Current HP		Non-zero sets default healthy points.
- 0x01E2	Set Gold 		Non-zero sets current gold available.
- 0x01E3	Set Weapon 		Set value to 1 or 2 for stock else 0.
- 0x01E4	Set Armor		Set value to 1 or 2 for armor else 0.
- 0x01E5	Add Life		Set value to 1=Life otherwise 0=None.
- 0x01E6	Village Talk	Set value to 1=repeat villagers talk.
- 0x01E7	Music Off		Set 0=Music to play otherwise silent.
- 0x01E8	Sound Off		Set 0=Sound to play otherwise silent.

###### ENEMIES
- There are 5x different enemies in order of increasing difficulty: Razboynik, Hungry Wolf, Kikimora, Leshy, Baby Yaga
- Defeat final boss Koschey to beat the game!

###### LEVELS
- There are 3x levels: 1, 2, 3.  Maximum player HP = 30 and maximum player XP = 99

###### HINTS
- Try to buy the weapon "Sword" or armor "Tegilay" with your initial gold before entering any forest fights
- After completing each forest fight, ensure you "Rest" at the main screen to replenish all HP
- In the shop, if you buy an item you already have then the gold will be deducted unconditionally so be aware - there is no validation!
- Try to get "+1 Life" just in case you lose a fight or the final boss battle so you do not have to restart game
- Maximize player HP + XP and get the best weapon "Axe" and the best armor "Kolchuga" before attempting to beat the boss.  
- Once you fight the boss you cannot "Run away".  Try to fight boss once you have > 60 XP because your weapon and armor may be slightly more powerful!

###### CHEATS
- On title screen, hold button B to skip intro music.  Same applies on boss and over screens.
- On title screen, hold button B after intro music completes to reveal hidden credits screen.
- On stats screen, move joystick left or right to skip over the flashing arrows indication.
- In forest screen, press button B to "Run away" without risking losing any HPs [Easy mode].

###### CREDITS
Extra special thanks to: [@MegadriveDev](https://twitter.com/MegadriveDev) for the SGDK  [github.com/Stephane-D/SGDK](https://github.com/Stephane-D/SGDK)
<br />
Plus big shout out to the MegaDrive community for their on line help and support esp:
<br />
@bigevilboss / @matteusbeus / @MoonWatcherMD / @ohsat_games / @SpritesMind

###### DOCUMENTATION
Links to documentation on games written for the Sega MegaDrive using the SGDK:
<br />
https://steveproxna.blogspot.com/2020/09/sgdk-programming-setup.html
<br />
https://steveproxna.blogspot.com/2020/11/sgdk-programming-sample.html

###### COMPANY BIO
StevePro Studios is an independent game developer that builds and publishes 80s + 90s retro arcade video games!
<br />
Founded by Steven Boland "SteveProXNA" (Jan-2007) a "one man team of one" currently based in Dublin, Ireland.

###### CONTACT
- Blog:		[steveproxna.blogspot.com](https://steveproxna.blogspot.com)
- Email:	[steven_boland@hotmail.com](mailto:steven_boland@hotmail.com)
- Twitter:	[@SteveProXNA](http://twitter.com/SteveProXNA)

