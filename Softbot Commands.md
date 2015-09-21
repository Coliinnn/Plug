Softbot Commands:
=========

X specifies a number - arguments between ( ) are optional.

'Timer' is an optional argument that will automatically toggle on/off again after X minutes. (timer) means that you can provide just the numbers as second argument in order to set X.


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!freeze | null | Freezes chat |
|!getstats | null | Displays account statistics: Level, XP, PP |
|!kill | null | Shuts down the bot and stops all processes |
|!lockdown | null | Puts room in lockdown |
|!number | null | Starts Guess The Number |
|!refresh| null | Refreshes the browser of the bot |
|!reload | null | Reloads the bot |
|!roulette | null | Starts the roulette |
|!sb ad | (timer X) (X) | Toggles advertisements / Sets advertisement interval |
|!sb af | (timer X) (rank) (X) | Toggles AFK Removal / Sets AFK limit / Sets rank-bypass |
|!sb cf | (timer X) | Toggles chat filter |
|!sb dc | (timer X) (X) | Toggles DC / Sets DC limit |
|!sb hs | (timer X) | Toggles history skipping |
|!sb rc | (timer X) | Toggles responsive chat |
|!sb sf | (timer X) | Toggles song filter |
|!sb sl | (timer X) (X) | Toggles song length skipping / Sets maximum song time |
|!sb sk | (timer X) | Toggles stuck skipping |
|!sb ss | (timer X) | Toggles song stats |
|!sb slr | (timer X) | Toggles Slack Reporting |
|!sb slc | (timer X) | Toggles Slack Chat Logging |
|!sb uc | (timer X) | Toggles user commands |
|!stop | null | Stops the bot |


Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!clearchat | null | Clears chat |
|!clearlock | null | Clears and locks the waitlist |
|!clearwaitlist | null | Clears the waitlist |
|!lock | (timer X) | Locks the waitlist |
|!move | @user pos | Moves user to posX in the waitlist |
|!unlock | (timer X) | Unlocks the waitlist |


Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | Adds user to the wait list |
|!afktime | @user | Displays user's AFK time |
|!allowlink | @user | Sets user to RDJ for 20 seconds so they can post a link |
|!autojoin | null | Displays a warning message about autojoin |
|!ban | @user hour/day/perm | Bans user for (one) hour/day/perm |
|!getcid | null | Displays the cID of the current song |
|!getid | @user | Displays mentioned user's ID |
|!getmedia | null | Displays the author and name of the current song |
|!kick | @user | Kicks user for 15 seconds |
|!lockskip | null | Skips and moves DJ back to #1 in the waitlist |
|!mehs | null | Displays a warning message about excessively meh'ing |
|!mute | @user 15/30/45 | Mutes user for 15/30/45 minutes |
|!reloadlists | null | Reloads OP & Black lists |
|!remove | @user | Removes user from the wait list |
|!skip | null | Skips the current song |
|!stats | null | Displays room statistics |
|!test | null | Displays current settings |
|!version | null | Displays bot version |
|!voteratio | @user | Displays user's woots, mehs and ratio(w/m) |
|!warncount | @user | Displays user's warncount |
|!warnreset | @user | Resets user's warncount |


Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!pic | null | Links the current video thumbnail |
|!help | rdj, bouncer, manager, host, ba, admin | Explains the issued argument |
|!help | plug, roulette, number | Explains the issued argument |


User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!adblock | (@user) | Links Adblock |
|!bllist / !bl | (@user) | Links Blacklist |
|!changelog | (@user) | Links Softbot changelog |
|!commands / !cmd | (@user) | Links the commands page |
|!dc | null | Moves user back to position after disconnecting |
|!emoji | (@user) | Links emoji-cheat-sheet |
|!eta | (@user) | Displays how long until user reaches the DJ booth |
|!help | (@user) | Links an image on how to use Plug.DJ |
|!info | (@user) | Links Softbot information page |
|!join | (@user) | Joins the roulette |
|!leave | (@user) | Leaves the roulette |
|!link | (@user) | Links the current song |
|!oplist / !op | (@user) | Links OPlist |
|!p3 | (@user) | Links PlugCubed |
|!ping | (@user) | Pong! |
|!rcs | (@user) | Links Radiant Room Script |
|!rules | (@user) | Links the rules page |
|!theme | null | Shows information on the room theme/genres |
