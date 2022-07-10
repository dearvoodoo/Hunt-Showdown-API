.. 2.0.x Changelogs

Murmur Bot 2.0.11 (COMING SOON)
==========================

| Update not available yet.

This is a big update after the bot went private.

Global
------------------

- Add embeds for some messages.


RPS
------------------

- RPS now use Discord Buttons.



Role Button
------------------

- New module added !
- This module is like a Role Reaction system but with buttons. (25 max)


Select Menu
------------------

- New module added !
- Same as the Role Button module but with Select Menu Dropdown.


Sanction
------------------

- New module added!
- Sanction is a module to add button for easy moderation.
- See by yourself with the ``!sanction <user>`` command.


Calculator
------------------

- New module added !
- Add a calculator made with button with the command ``!calc``
- This module can now use the command ``!calc [calculation]``

| More soon


Murmur Bot 2.0.10 (2021-09-10)
==========================

This is a global fixing issues and optimisation update.

Update libs
------------------

- Updated psutil.
- Updated six.
- Updated cffi.
- Updated PyNaCl.
- Updated typing-extensions.
- Updated contextlib2.
- Updated attrs.
- Updated Markdown.
- Updated idna.
- Updated python-dateutil.
- Updated Babel.
- Updated Pygments.
- Updated click.
- Updated aiosqlite.
- Updated rich.
- Updated apsw-wheels.
- Updated uvloop.
- Updated chardet.
- Updated aiohttp.
- Updated distro.


Update Discord.py
------------------

- Updated ``discord.py`` to version ``1.7.3``.


Global
------------------

- Fixed a bug that cause Murmur to crash when guild upload a new sticker.
- Fixed a bunch of errors related to missing permissions and channels/messages no longer existing.
- Deleting the module ``Dead by Daylight``. Maybe come back later but at the moment I don't have time fopr that shitty game anymore.
- Fedora 32 is no longer supported as it has already reached end of life.
- Murmur is fully compatible with Python 3.9.
- The user will now be warned if he wants to put a server prefix longer than 20 characters.


Admin
------------------

- The ``!selfroleset add`` and ``!selfroleset remove`` commands can now be used to add multiple selfroles at once.


Aliases
------------------

- Added commands to edit existing aliases.


Audio
------------------

- ``!summon`` command will now indicate that it succeeded or failed to summon the bot.
- Fixed player with SoundCloud.
- Fixed YouTube search.
- Fixed fetching age-restricted tracks.
- Fixed an issue with short clips being cut off when auto disconnect at end of queue is enabled.
- Added Max volume per server with the ``!audioset maxvolume`` command.
- Removed external API.
- Updated Playlist links.


Clean up
------------------

- All ``!cleanup`` commands will now send a notification with the number of messages deleted. The notification is automatically deleted after 5 seconds. This can be disabled with the command ``!cleanupset notify``.
- The ``!cleanup user`` command can now be used to clean up messages from a user who is no longer on the server.


Filter
------------------

- Added ``!filter clear`` and ``!filter channel clear`` commands to clear server/channel filter list.
- Problem that caused the module to check DMs.


Mod
------------------

- ``!rename`` command will no longer allow changing the nicknames of members who are not lower in the role hierarchy than the caller of the command.
- The DM for the ``!tempban`` command will now include the reason for the ban if the ``!modset dm`` setting is enabled.
- Fixed an error with handling temp ban expirations when the server is unavailable due to a Discord outage.


Streams
------------------

- Optimisation
- Fixed an issue where a youtuber could be removed from the list after a long time.