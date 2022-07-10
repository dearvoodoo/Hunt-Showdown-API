.. _announcer:

=======
Announcer
=======

This is the module guide for the announcer module. You will
find detailed docs about usage and commands.

``[p]`` is considered as your prefix. (Default: ``!`` or ``/``)

.. _announcer-usage:

-----
Usage
-----

This module includes a YouTube subscription système to notify your user when a subscription post a new video..

.. _announcer-commands:

--------
Commands
--------

Here's a list of all commands available for this module.

.. _announcer-command-subscribe:

^^^^^^^^^
Subscribe
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]announcer subscribe <Youtube_Channel_ID> [Discord_Channel] [UseRoleMention] [Role]

**Description**

Subscribe a Discord channel to a YouTube channel  
If no discord channel is specified, the current channel will be subscribed

.. note:: Adding youtube channels by name is not supported at this time. The YouTube channel ID for this can be found in channel links on videos.  
For example, to subscribe to the channel VooDoo, you would search YouTube for the name, then on one of the videos in the results copy the channel link. It should look like this:  
https://www.youtube.com/channel/UCC3qjEASWsSJPX0ww_h4gXg  

So the VooDoo channel ID is UCC3qjEASWsSJPX0ww_h4gXg  

**Arguments**

* ``<Youtube_Channel_ID>``: The Youtube channel ID.
* ``<Discord_Channel>``: The Discord channel you want Murmur to use for alerts.
* ``[UseRoleMention]``: Set on ``True`` if you want to use role mention. If you want to tag ``@everyone`` leave this option and the next one empty.
* ``[Role]``: If you set ``True`` before please tag the role you want to use.

.. _announcer-command-unsubscribe:

^^^^^^^^^
Unsubscribe
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]announcer unsubscribe <channelYouTube> [channelDiscord]

**Description**

Unsubscribe a Discord channel from a YouTube channel  
If no Discord channel is specified, the subscription will be removed from all channels

.. note:: Note.

**Arguments**

* ``<channelYouTube>``: The Youtube channel ID..
* ``[channelDiscord]``: The Discord channel Murmur use for this channel id.

.. _announcer-command-showsubs:

^^^^^^^^^
Showsubs
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]announcer showsubs

**Description**

List current subscriptions

.. _announcer-command-update:

^^^^^^^^^
Update
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]announcer update

**Description**

Update feeds and post new videos

.. _announcer-command-:

^^^^^^^^^
Demo
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]announcer demo

**Description**

Post the latest video from all subscriptions