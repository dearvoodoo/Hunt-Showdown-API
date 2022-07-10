.. _audio:

=======
Audio
=======

This is the module guide for the audio module. You will
find detailed docs about usage and commands.

``[p]`` is considered as your prefix. (Default: ``!`` or ``/``)

.. _audio-usage:

-----
Usage
-----

This module includes all functions for Murmur to make Music in channels. 
Compatible with YouTube, Soundcloud and Spotify. (BETA play Twitch stream audio)

.. _audio-commands:

--------
Commands
--------

Here's a list of all commands available for this module.

.. _audio-command-disconnect:

^^^^^^^^^
Disconnect
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]disconnect

**Description**

Disconnect from the voice channel.

.. _audio-command-now:

^^^^^^^^^
Now / Now playing
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]now

**Description**

Now playing.

.. _audio-command-pause:

^^^^^^^^^
Pause / Resume
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]pause

**Description**

Pause or resume a playing track.

.. _audio-command-prev:

^^^^^^^^^
Prev / Previous
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]prev

**Description**

Skip to the start of the previously played track.

.. _audio-command-seek:

^^^^^^^^^
Seek
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]seek <seconds>

**Description**

Seek ahead or behind on a track by seconds or a to a specific time.

.. note:: Accepts seconds or a value formatted like 00:00:00 (``hh:mm:ss``) or 00:00 (``mm:ss``)..

**Arguments**

* ``<seconds>``: Timecode formated value.

.. _audio-command-shuffle:

^^^^^^^^^
Shuffle
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]shuffle

**Description**

Toggle shuffle.

.. _audio-command-bumped:

^^^^^^^^^
Bumped
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]bumped

**Description**

Toggle bumped track shuffle.

.. note:: Set this to disabled if you wish to avoid bumped songs being shuffled. This takes priority over ``!shuffle``.

.. _audio-command-skip:

^^^^^^^^^
Skip
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]skip [skip_to_track]

**Description**

Skip to the next track, or to a given track number.

**Arguments**

* ``[skip_to_track]``: Number of track to skip.

.. _audio-command-stop:

^^^^^^^^^
Stop
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]stop

**Description**

Stop playback and clear the queue.

.. _audio-command-summon:

^^^^^^^^^
Summon
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]summon

**Description**

Summon Murmur to a voice channel.

.. note:: You have to be in a voice channel. Murmur will join you in the same channel.

.. _audio-command-volume:

^^^^^^^^^
Volume
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]volume <vol>

**Description**

Set the volume, 1% - 150%.

.. note:: Please use integrated Discord user volume before using this.

**Arguments**

* ``<vol>``: Value between 1 and 150.

.. _audio-command-repeat:

^^^^^^^^^
Repeat
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]repeat

**Description**

Toggle repeat.

.. _audio-command-remove:

^^^^^^^^^
Remove
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]remove <index_or_url>

**Description**

Remove a specific track number from the queue.

**Arguments**

* ``<index_or_url>``: URL of the track or position in queue.

.. _audio-command-bump:

^^^^^^^^^
Bump
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]bump <track_number>

**Description**

	Bump a track number to the top of the queue.

**Arguments**

* ``<track_number>``: Number of the track in the queue to bump at the top of the list.

.. _audio-command-play:

^^^^^^^^^
Play
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]play <URL_or_search_query>

**Description**

Play a URL or search for a track

**Arguments**

* ``<URL_or_search_query>``: URL or title of the song/video.

.. _audio-command-bumpplay:

^^^^^^^^^
Bump Play
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]bumpplay [play_now=False] <query>

**Description**

DescriptionCommaForce play a URL or search for a track.nde

**Arguments**

* ``[play_now]``: Default on ``False``. Set to ``True`` if you want the song to play now.
* ``<query>``: URL or title of the song/video.

.. _audio-command-genre:

^^^^^^^^^
Genre
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]genre

**Description**

Pick a Spotify playlist from a list of categories to start playing.

.. _audio-command-autoplay:

^^^^^^^^^
Auto Play
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]autoplay

**Description**

Starts auto play.

.. _audio-command-search:

^^^^^^^^^
Search
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]search <query>

**Description**

Pick a track with a search.

.. note:: 
    Use ``!search list <search term>`` to queue all tracks found on YouTube.
    
    Use ``!search sc <search term>`` to search on SoundCloud instead of YouTube.

**Arguments**

* ``<query>``: Search query.

.. _audio-command-queue:

^^^^^^^^^
Queue
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue [page]

**Description**

List the songs in the queue.

**Arguments**

* ``[page]``: Queue page number.

.. _audio-command-queue-clear:

^^^^^^^^^
Queue Clear
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue clear

**Description**

Clears the queue.

.. _audio-command-queue-clean:

^^^^^^^^^
Queue Clean
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue clean

**Description**

Removes songs from the queue if the requester is not in the voice channel.

.. _audio-command-queue cleanself:

^^^^^^^^^
Queue CleanSelf
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue cleanself

**Description**

Removes all tracks you requested from the queue.

.. _audio-command-queue-search:

^^^^^^^^^
Queue Search
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue search <search_words>

**Description**

Search the queue.

**Arguments**

* ``<search_words>``: Search words.

.. _audio-command-queue-shuffle:

^^^^^^^^^
Queue Shuffle
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]queue shuffle

**Description**

Shuffles the queue.