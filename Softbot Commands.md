Softbot Commands:
=========

NOTE: This bot is a work-in-progress. Features may not work as they should.

X specifies a number - arguments between ( ) are optional.

'Timer' is an optional argument that will automatically toggle on/off again after X minutes. (timer) means that you can provide just the numbers as second argument in order to set X.


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!kill | null | Shuts down the bot and stops all processes |
|!stop | null | Stops the bot |
|!refresh| null | Refreshes the browser of the bot |
|!reload | null | Reloads the bot |
|!lockdown | null | Puts room in lockdown |
|!sb ad| (timer) X | Toggles advertisements / Sets advertisement interval / Sets auto-toggle timer |
|!sb hs | (timer X) | Toggles history skipping / Sets auto-toggle timer |
|!sb sl | (timer) X | Toggles song length skipping / Sets maximum song time / Sets auto-toggle timer |
|!sb ss | (timer X) | Toggles song stats / Sets auto-toggle timer |
|!sb sf | (timer X) | Toggles song filter / Sets auto-toggle timer |
|!sb cf | (timer X) | Toggles chat filter / Sets auto-toggle timer |
|!sb uc | (timer X) | Toggles user commands / Sets auto-toggle timer |


Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!move | @user posX | Moves user to posX in the waitlist |
|!lock | (timer X) | Locks the waitlist / Sets auto-toggle timer |
|!unlock | (timer X) | Unlocks the waitlist / Sets auto-toggle timer |
|!clearlock | null | Clears and locks the waitlist |
|!clearwaitlist | null | Clears the waitlist |
|!clearchat | null | Clears chat |


Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!test | null | Displays current settings |
|!stats | null | Displays room statistics |
|!allowlink | @user | Sets user to RDJ for 20 seconds so they can post a link |
|!skip | null | Skips the current song |
|!kick | @user | Kicks user for 15 seconds |
|!ban | @user hour/day/perm | Bans user for (one) hour/day/perm |
|!getid | @user | Displays mentioned user's ID |
|!getcid | null | Displays the CiD of the current song |
|!getmedia | null | Displays the author and name of the current song |
|!autojoin | null | Displays a warning message about autojoin |
|!mehs | null | Displays a warning message about excessively meh'ing |
|!version | null | Displays bot version |
|!lockskip | null | Skips and moves DJ back to #1 in the waitlist |


Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!pic | null | Links the current video thumbnail |
|!staff | rdj, bouncer, manager, host, ba, admin | Explains what the rank is |


User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!ping | (@user) | Pong! |
|!commands / !cmd | (@user) | Links the commands page |
|!help | (@user) | Links an image on how to use Plug.DJ |
|!rules | (@user) | Links the rules page |
|!link | (@user) | Links the current song |
|!theme | null | Shows information on the room theme/genres |
|!p3 | (@user) | Links PlugCubed |
|!adblock | (@user) | Links Adblock |
|!emoji | (@user) | Links emoji-cheat-sheet |
|!oplist / !op | (@user) | Links OPlist |
|!bllist / !bl | (@user) | Links Blacklist |
