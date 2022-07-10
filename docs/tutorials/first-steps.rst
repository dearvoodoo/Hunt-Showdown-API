.. First Steps

========================
First Steps Hunt: Showdown API
========================

This guide serves as a tutorial for the first steps with Hunt: Showdown API.
It will cover the basics of using this API for your
app. We will also point you towards some further 
resources that may assist you in the process.

---------------
What is an API ?
---------------

API stands for Application Programming Interface.
In basic terms, APIs are a set of functions and procedures that allow for the creation of applications. They access the data and features of other applications, services, or operating systems.
Essentially, they’re a go-between for different software platforms. They allow two unrelated applications to “talk” to each other.

--------------------
What is this about ?
--------------------

Hunt: Showdown API is a fan-made API with all the info you need to build your app about the game.
By all info, I mean weapons, ammo, hunters, DLCs, tools, legendaries and consumables.
There are no stats or rankings of players as we do not have access to this kind of information.


.. attention:: 
    This site and API is not associated with, endorsed by, or in any other form connected with CRYTEK GMBH or any other company.
    It's a fan project. If anything is wrong, feel free to contact the author via Twitter @DearVooDoo.
    Use at your own risk.
    Good news are, this site does not use cookies and is running in your browser, no data is saved on the server.
    Links are not affiliate. Only free sharing 

    Thanks to Crytek for this amazing game.

--------------
The API ?
--------------

The API returns a JSON response by default.
You can use query in url to request a specific information.
All list of endpoints and result exemple are available in the category Endpoints.

.. note::
    API requests may be rate limited.
    Go to :doc:`/ratelimitation`

----------------
How to get image ?
----------------

This API can return a path for an image or an icon. 
You have to build the path yourself. But no worries this simple as fuck.

All images are uploaded to my website.
So take this part :code:`https://huntshowdown.dearvoodoo.com/imgs`
and just add the path that the API returns.

So an image link looks like this:
:code:`https://huntshowdown.dearvoodoo.com/imgs/ammo/compact/normal_ammo_box.png`


-------------------
How to use queries ?
-------------------

Queries are very usefull when you want specific information to be return.
For example, you want information on the "Bolt Thrower" trait.
You can use the ID of this trait to directly tell at the API that you want only information with this tag.
:code:`https://huntshowdown-api.herokuapp.com/trait_info?tag=bolt_thrower`
You can request more than one information at a time.
