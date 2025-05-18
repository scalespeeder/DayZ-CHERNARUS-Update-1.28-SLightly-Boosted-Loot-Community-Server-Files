1.28 DayZ Chernarus Slightly Boosted Loot PvE xml Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus Local Server DAYZ EXPERIMENTAL Version 1.28 MAY 2025.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

cfggameplay.json includes map function config that shows player position without needing GPS Receiver, tourist map or compass, and build anywhere settings. cfggameplay.json must be enabled in server settings and / or serverdz.cfg.
DO NOT USE cfggameplay.json if you don't want build anywhere enabled.

These files have less mods than my previous ones. No hidden or special items are added, apart from those listed below.

Many thanks to DayZ Boosterz website for their easy-to-use and fast tools! https://dayzboosterz.com/

-----------------------

PLEASE READ THE INSTRUCTIONS ON HOW TO INSTALL THESE FILES AS IT IS DIFFERENT TO HOW IT USED TO BE DONE!!!!!!

-----------------------

Only upload these files when update 1.28 has gone live.

Stop your server.

To install these files, firstly make sure you make backups of any custom files or settings you might also need. Then reset you server mission files to default / vanilla files.
Then (if you are going to use it) upload cfggameplay.xml OVER THE TOP OF & IN THE SAME FOLDER THE ORGINAL VERSION OF THIS FILE.

On console you already have a "custom" folder inside the mission folder on your server. ON PC YOU MUST MAKE ONE, eg: mpmissions\dayzOffline.chernarusplus\custom

Now upload 1C-128-extra-types.xml 1C-128-extra-events.xml 1C-128-extra-cfgspawnabletypes.xml 1C-128-extra-messages.xml & 1C-128-extra-globals.xml into that custom folder.

Next open up your vanilla cfgeconomycore.xml, and near the bottom, above the closing

</economycore>

tag,

paste this:

	<ce folder="custom">
	<file name="1C-128-extra-types.xml" type="types" />
	<file name="1C-128-extra-events.xml" type="events" />
	<file name="1C-128-extra-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="1C-128-extra-messages.xml" type="messages" />
	<file name="1C-128-extra-globals.xml" type="globals" />
	</ce>
	
Save the file and re-upload if necessary.

Restart your server & changes should start to take effect. How quickly will depend on the population of your server.


----------

types.xml edits

2 x Weapons.

2 x Mags.

2 x Boxed Ammo.

2 x Food.

2 x Drinks.

3/4 Loose Ammo.

3/4 Flags.

3/4 Clothing.

Payday masks added ( 1 of each).

Mags spawn full of bullets.

2 x Tetracycline (antibiotics).

----------

globals.xml edits

server waits ten minutes before going into idle mode. (better for loot economy.)

5 second login / logout.

loot should spawn in pristine, unless over-ridden in cfgspawnabletypes.xml.

----------

cgfgameplay.json edits

"build anywhere" settings.

when opened, map shows player location. (On PC you don;t need to find map, just press M. On console, you need to find a map.)

----------

events.xml edits

2 x vehicles spawn.

----------

cfgspawnabletypes edits

most items should spawn pristine. (I might have missed some!)

pistols and SMGs spawn with supressors & mags.

AR's & rifles spawn with optics & mags.

boats spawn with sparkplugs.

vehicles spawn complete, with fuel-can in cargo. players will need to add water to radiator where applicable. (No other loot in vehicles.)

-----------

messages.xml edits

server restart every 12 hours with countdown message.

GOOD LUCK!