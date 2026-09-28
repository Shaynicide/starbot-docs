---
description: All Starbot changelogs, in recent order and separated by version
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# 💡 Changelog

<details>

<summary><mark style="color:$primary;"><strong>6.3.0</strong></mark></summary>

#### Bump Reminders

★ Added reminder settings for <mark style="color:$primary;">Disboard</mark> and <mark style="color:$primary;">Dissoku</mark>

　☆ After each `/bump` or `/up` command, a reminder while be sent 2 hours later

#### Enter & Exit Messages

★ Added background styles to choose from for **Image** type

★ Message & image now in container

　☆ Text can be set **above or below** the image

#### Starbot Updates

★ Added setting for **Starbot Updates** channel

　☆ Future Starbot announcements will be sent here if set

#### Help Menu

★ Improved `/help` clarity & split bot info into own button

#### New Member Cleanup

★ Added feature to remove messages from new users who leave quickly

　☆ Time period & exempt channels can be set

#### Updated Setup Menu

★ Created a more comprehensive setup menu

#### Internal

★ Set up event framework so Starbot events can be handled easier

</details>

<details>

<summary><mark style="color:$primary;"><strong>6.2.1</strong></mark></summary>

#### Voice Channel Alerts

★ Added an **Allowed Channels** list

　☆ For more details, check [here](settings-menu/voice-and-rooms/voice-activity.md#allowed-list-and-exempt-list)

★ Allowed **categories** to be added to lists

#### XP Channel Lists

★ The above changes were also applied

</details>

<details>

<summary><mark style="color:$primary;"><strong>6.2.0</strong></mark></summary>

#### `Edit Image` Command

★ Right click a message to and use to upload a custom image for:

　☆ Role select menu

　☆ Response form

　☆ Lottery message

#### Role Menus

★ Raised cap from 10 to 24 roles per menu

　☆ Added navigation buttons in editor (8 roles per page)

</details>

<details>

<summary><mark style="color:$primary;"><strong>6.1.0</strong></mark></summary>

#### Website

★ New website is up and functional!

　☆ Most settings editable from dashboard

　☆ User/server profile, achievements, cards etc. viewable

#### Sticky Messages

★ Added sticky messages that stay as the last message in a channel

★ Deletes old message and reposts message on time/message interval

#### Trap Channel

★ Added option to add anti-spam trap channel

　☆ Same exceptions and action applies as trap role

　☆ Any message in the channel will cause the moderation action

#### `/cleanup` Command

★ `/cleanup` clears messages up to 2 weeks old from a channel

</details>

<details>

<summary><mark style="color:$primary;"><strong>6.0.0</strong></mark></summary>

#### Database

★ Finally switched from a single JSON file to a real database

　☆ Should be _much_ more reliable

★ Data from before has been migrated

★ Added bot stat tracking (command usage, temporary VC creation, etc.)

#### Guide & Changelog

★ This guide & changelog have been rewritten to match current Starbot

#### Menu Overhaul

★ `/settings` has been grouped by category

★ Reworked majority of menus to be cleaner

★ Removed cumbersome timed menus

★ Made set-up menus easier to understand and navigate

#### Moderation Logs

★ Added a new type - System

★ Full moderation log history can now be viewed easily

★ Added user & log type filters

#### Ban Appeals

★ Ban appeals are now stored server-side instead of relying on messages

★ Appeal responses are now logged in the mod log

★ When enabled, users are sent a DM on ban with appeal button

#### Welcome Role

★ Also known as the _Newbie Role_ has been reworked and fixed

★ Can be removed if any of the selected conditions are met

★ Added a pruning feature that removes members with the role X days after joining

#### Temporary VC

★ Should be more reliable and quicker

★ Created a more fleshed out `/room` command

　☆ Easier to use

　☆ Added transfer/claim ownership button

#### Surveys

★ Surveys questions can now be set as required or not

★ New question types added

　☆ File uploads

　☆ User select

　☆ Radio options

★ Forum style now selectable (was automatic if forum channel selected)

★ Thread style added - adds user to a private thread

#### Greeting Messages

★ Made a new, cleaner greeting image

★ Changed creation method to be quicker and cleaner

#### Mini-Games

★ Mini-games have been rewritten cleaner

★ Game lobby creation has been streamlined

#### Trivia Time

★ Added new trivia categories

★ Added tons of updated questions in each category

★ Japanese now available (for all questions!)

★ `Report Question` button added after each question

#### User Menu

★ Can access user menu with `/me`

#### Pets

★ Added new pets to the list

★ All pet skills are now fully functional

#### Items

★ New items added

★ Passive item effects fixed

★ Changed some equipable items to one-use items

★ Added ability to specify channel that item-related messages are sent to

#### Gacha

★ Added cleaner display for x10 gacha pulls

★ Added modifiers based on items and statuses

#### Achievements

★ New achievements added

★ Some achievements removed or modified

#### Status System

★ Made a framework for statuses

★ Current status list can be checked with **/me status**

#### Website

★ Began rewrite of website - dashboard currently not available

★ Not yet optimized for mobile/vertical layout

★ **Star Typing** mini-game rewritten

#### Changed

★ **`/quit`** (Now **`/game quit`**)

#### Removed

★ **`/poll`** (Discord native feature now)

★ **`/beg`** (Increased users means too many requests to look at)

★ **`/breakout`** (Slowed by rate limits, **`/pick`** and moving members is faster)

#### Bug Fixes & Internal

★ I fixed SO. MANY. BUGS. IDK WHERE TO BEGIN.

★ I cleaned up EVERYTHING. YOU DON'T EVEN KNOW.

★ Improved error handling, better safeguards, improved stability

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>5.8.1</strong></mark></summary>

#### VC Alerts

★ Now allows customizable delay before alert is sent

#### Bug Fixes

★ Fixed auto-VC room sorting algorithm

★ Fixed bug where XP leaderboard would not load in certain cases

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.8.0</strong></mark></summary>

#### Website

★ Rebuilt website from scratch

　☆ Most settings can be changed through the dashboard

　☆ Collected [achievements](achievements.md), [trading cards](coins-and-items.md#trading-cards), pets, and [items](coins-and-items.md) can be viewed

　☆ Added mini-games to the website

#### Pets

★ Added new pets

　☆ Especially moderation and level-up menus

#### Misc.

★ Added `30m` option to [#everyone-mute](changelog.md#everyone-mute "mention") timeout options

★ Added new mechanic to crafting

#### Bug Fixes

★ Fixed bug with @everyone Mute messages

★ Fixed bug where mod log target was sometimes empty

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.7.0</strong></mark></summary>

#### @everyone Mute

★ Added automatic timeout on @everyone mention to moderation settings

　☆ Timeout length is adjustable

　☆ Exempt role whitelist adjustable

　☆ Custom response message possible

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.6.1</strong></mark></summary>

#### XP System

★ Adjusted formula for XP calculation from messages

#### Bugfixes

★ Fixed VC alert message not showing when role mention is disabled

★ Fixed back button behavior in Level-Up System menu

★ Fixed not being able to add or remove roles in Level-Up System menu

★ Fixed bug where items could not be used

★ Fixed errors when playing **Faker**

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.6.0</strong></mark></summary>

#### Moderation Logs

★ Made logs and master log more compact, easier to read

★ Each case in a server now has a unique ID

★ Fixed pagination when navigating master log

★ Log reasons are now editable for up to 3 days

#### Temporary VC Creation

★ Removed action timeout from creation process

★ Each step now shows channel information up to that step

★ Can now select category to add channel at on last step

#### Settings Menu

★ Cleaned up various settings menu sections

　☆ Especially moderation and level-up menus

★ Changed anti-spam handling & response levels to readable language

　☆ For example, `5 | 1` → `Extreme | Timeout (1h)`

#### Misc.

★ Removed action timeout from boost menu

★ Added roll again options to `/roll`

★ Gave cursed item pulls in `/gacha` unique message

#### Bugfixes

★ Fixed boost menu back button not doing anything

★ Fixed block list members not being blocked on VC creation

★ Moved temporary VC audio quality 192kbps to boost level 2 (from 1)

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.5.0</strong></mark></summary>

#### Anti-Spam

★ Adjusted algorithm to be more accurate

　☆ Currently monitoring in case of need for adjustment

★ Fixed issues with certain spam responses not triggering

#### VC Alerts

★ Voice channels exempt from creating alerts can now be specified

#### Level-Up System

★ Channels exempt from XP gain can now be specified

#### Event

★ Added Christmas advent calendar event

#### Pets

★ Pets have been added

★ Pets can be accessed with `/pets`

#### Items

★ Pagination added to item list when using `/bag`

★ New items added

★ "X" rarity has been removed

　☆ Was originally used to prevent being pulled in gacha

　☆ Former "X" rarity items have had their rarities changed

★ Removed limit on **Event Coins** in bag

#### Surveys

★ Survey questions can now be edited without having to make a new survey

#### Bugfixes

★ Fixed  `/ban` not working when the member was not bannable by Starbot

★ Fixed errors with ban appeal settings

★ Fixed errors punishments in warning system

★ Fixed **Spirit Seal** burning already burnt items if burnt in succession without returning to bag

　☆ On a deeper level, fixed items having an inventory slot server-side even when at 0 or negative

★ Fixed boost message settings buttons using server language instead of user's language

★ Fixed being forced to choose compact mode on survey creation

★ Fixed bug where using **Edit** from the right-click menu would delete uneditable messages

★ Fixed boost message not triggering if user had boosted before, stopped, and boosted again

#### Internal

★ Organized event files so that new ones are easier to make

★ Event starts and ends are now automated

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.4.1</strong></mark></summary>

#### Games

★ Trivia Time

　☆ Trivia questions and answers should have characters encoded correctly

　☆ Fixed coin & item rewards at the end (also for **Word Wolf**)

　☆ Added a 12.5% chance for double point questions

　☆ Each question now clearly shows who got it right/wrong

　☆ Final results show scores of winning player(s)

#### Items

★ Increased chance of getting Spirit Seal / craft materials in gacha when holding a cursed item

★ Added an **"Open One More"** button to Mystery Boxes

#### Bugfixes

★ Fixed bug where language was always set to English regardless of choice as set-up

★ Fixed bug where charm wasn't affecting cursed item rates

★ Fixed bug where Member's Card discount would not be applied to gacha

★ Fixed some bugs with crafting

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.4.0</strong></mark></summary>

#### Ban Appeals

★ Added `/banappeal` command

★ Servers can set up ban appeals

　☆ Banned users can send an unban request to servers that support it

　☆ Moderators can either approve or reject the appeal (with comments)

#### Special Roles

★ Added a **VC role** to special roles

　☆ This role will be added on joining VC and removed upon disconnect

　☆ Will only be given/removed after 5 seconds of joining/disconnecting

★ Updated settings menu to reflect all current special roles

#### XP Reset

★ Add option to remove reward role on reset if level not met

#### Bugfixes

★ Fixed various errors in menus

★ Fixed anti-spam not deleting messages properly

★ Fixed error with lotteries not choosing winners correctly

★ Fixed using command usage not counting towards achievements

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.3.0</strong></mark></summary>

#### Warnings Rework

★ /unwarn removed

★ Warn command subcommands created for ease of use

　☆ /warn add

　☆ /warn remove

　☆ /warn list

　　✦ Warning history can now be viewed per user

★ Option to reduce warnings by 1 every X days without warning added

★ Added customizable punishment tiers

　☆ Add role, timeout (1-28 days), ban options available

#### Bug Fixes

★ Fixed error with server settings language

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.2.1</strong></mark></summary>

#### Block Command

★ /unblock removed

★ Block command subcommands created for ease of use

　☆ /block add

　☆ /block remove

　☆ /block list

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.2.0</strong></mark></summary>

#### Anti-Spam Gate Role

★ Added into Special Roles menu

★ When added, will timeout, kick, or ban user

★ On kick or ban, a log can be made with roles held

#### Lotteries

★ Added the ability to make create role blacklist/whitelist

★ Creating a blacklist will not allow users with a role on the list to participate

#### Bug Fixes

★ Fixed error with deleting offending messages on anti-spam trigger

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.1.0</strong></mark></summary>

#### Lotteries

★ Lotteries added to settings menu

★ 3 concurrent lotteries per server

★ Lotteries will automatically end after specified time (can be edited/ended early)

　☆ Lotteries can be rerolled (will display reroll count)

#### Ghost Ping Detection

★ Ghost Ping Detection added to moderation menu

★ Sends a message with who made the ghost ping and who they mentioned in-channel

#### Misc.

★ New icon!

★ Missing permission names are now localized when language is Japanese

#### Bug Fixes

★ Fixed bot roles not getting Read Message History permission by default in temporary VC

★ Fixed error with warning role settings

★ Fixed error with temporary VC audio settings menu

★ Fixed bug where editing level roles timed out after 30 seconds (instead of displayed 60)

★ Fixed bug where VC wouldn’t create if set above max possible for boost tier

　☆ This occurred when setting to a higher bitrate and then losing a boost level

　☆ Will now automatically reduce bitrate to max possible for tier on creation

★ Fixed XP reset reward roles not being distributed

★ Adjusted max survey question length to match Discord limits

★ Fixed bug where duplicated surveys would not link correctly

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.0.1</strong></mark></summary>

#### Surveys

★ /survey command removed, merged with /settings menu

★ Thread style added

　☆ When response location is a forum channel, creates a new thread for each response

#### Temporary VC

★ Added default audio quality on creation options (64 - 384kbps)

★ Fixed bug where rooms wouldn’t delete when a user creates and disconnects quickly

#### Profile Command

★ Added direct Achievement button to profile

★ Fixed bug where /profile would display both styles regardless of selection

</details>

<details>

<summary><mark style="color:$primary;"><strong>5.0.0</strong></mark></summary>

#### Bot Migration

★ Starbot migrated to a new bot account ([here](https://discord.com/api/oauth2/authorize?client_id=1198452952197763153\&permissions=1514408373463\&scope=bot+applications.commands))

★ All data and settings automatically transferred from old bot

#### Games

★ Faker overhauled\
　☆ New questions added

　☆ All responses and votes handled in-channel (no more DMs)

　☆ Can now change response until time runs out OR all players respond

★ Word Wolf brought back from the dead!

★ Trivia Time added (can be played alone or with friends; English only)

#### Data Handling

★ Changed data deletion thresholds

　☆ Server data will be deleted 30 days after bot is removed from server

　☆ User data will be deleted from server data 30 days after leaving a server

　☆ Global user data will be deleted 30 days after leaving all servers with Starbot

　☆ Timer is reset upon rejoining

#### Misc.

★ New achievements and items

★ Achievement 15 changed

★ Added “Eat/Drink Again” button after using consumable items

★ Bag will now sort items in Japanese kana order when in Japanese

#### Bug Fixes

★ Fixed some Starbot room permission bugs\
★ Fixed bug with spam check

★ Fixed bug with newbie roles

★ Fixed message bug when using a weapon

★ Users with no shared servers with Starbot will remain in block lists

★ Fixed bug where weapons would not break when they should

#### Internal

★ Admin commands grouped into command group

★ Changed how in-app reports are handled

★ Re-introduced local storage to reduce bandwidth usage

　☆ Bot can be restart much quicker

★ Fixed leave/ban server control panel

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>4.8.2</strong></mark></summary>

#### Mod Log Handlings

★ Changed how mod logs are handled internally\
　☆ Information should be gotten more efficiently

　☆ Errors should occur less often

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.8.1</strong></mark></summary>

#### User Icons

★ /icon will now display user’s server icon by default\
　☆ Can display global icon if selected in options

#### Bug Fixes

★ Resetting XP/levels with a reward role should now more accurately give role

★ Achievement 40 should no longer throw an error

★ Fixed error when duplicating a message\
★ Fixed bug with bypass newbie role via command

★ Fixed /pick private and public being reversed

★ Fixed race condition that caused /translate to occasionally fail

★ Fixed bug where having a deleted user on block list would block making rooms

★ Fixed bug where /event would not respond if there was no event

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.8.0</strong></mark></summary>

#### Anti-Spam

★ Added anti-spam function\
　☆ Set to OFF by default

　☆ Customizable trigger level (1: Light - 5: Aggressive)

　☆ Customizeable response level (1: 1 hour timeout - 5: 1 week timeout)

　☆ On trigger, previous messages will be deleted

#### User Blocking

★ /block and /unblock commands added\
　☆ Adds user to a personal block list

　☆ Blocked users will be blocked by default when creating a room

　☆ You can check your block list in /profile

#### Misc.

★ Channel select menus in settings now display set channels by default

#### Bug Fixes

★ Fixed error when transferring room ownership

★ Fixed permission required to make a ban log

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.7.1</strong></mark></summary>

#### Moderation Logs

★ Actions will now also log to an internal log\
　☆ Clicking a user from the warning list will show their warnings

★ Slight changes to master and secondary logs

　☆ Master log will only log selected actions

　☆ Secondary logs will always log if channel is specified

#### Bug Fixes

★ Fixed multiple errors that occurred when no language was selected

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.7.0</strong></mark></summary>

#### Bot Language

★ Bot will now use the user’s preferred language

★ Public in-server messages still use language from server settings

#### Menu Improvements

★ Fixed some broken menu buttons

★ Added back buttons to error messages

#### Auto-VC Rooms

★ Ownership and permissions should be more accurate

★ Fixed bug where rooms would be stuck with no owner

★ Member-only text channels removed

　☆ Messages can be sent in the actual voice channel

　☆ Users not in VC cannot send messages

★ Room ordering finally fixed

　☆ If room 1 and room 3 exist, room 2 should now order itself properly

　☆ Requires room position setting to be “under creation channel”

#### Team Maker

★ Added weighted/Valorant style options for balancing

　☆ The original random is also an option

#### Shop

★ Member’s Card dialogue no longer shows when discount is 0

★ Fixed some of the shopkeeper’s wording

#### Surveys

★ Survey command completely revamped

　☆ Survey menu and survey creation combined into one menu

　☆ Managing surveys now much easier

　☆ Survey details more comprehensive

#### Misc.

★ A few more commands are now able to be used in DMs

★ /profile now available (displays image or card of user stats)

★ /prune removed (Discord native prune upgraded)

#### Bug Fixes

★ Newbie role explanation now reflects actual settings

★ Ghost message tracking now takes Starbot into account

　☆ Deleted replies for bot responses now ignored

#### Internal

★ Interaction handling updated to be less messy

★ Code is more adaptive to changes

★ Took forever to do, so just adding another bullet point

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.6.3</strong></mark></summary>

#### Temporary Room Rewrite

★ Updated handling of temporary room data

★ Room owners now properly assigned

　☆ Owner will properly get edit channel permissions

　☆ Ownership will properly transfer on exit

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.6.2</strong></mark></summary>

#### Games

★ Faker voting now shows responsive feedback (instead of “interaction failed”)

★ Rock Paper Scissors now allows rematch on draws / bot games

★ /game & /quit combined into subcommands

　☆ /game menu, /game start (game selectable), /game quit

#### Text Channel Archives

★ Due to category having 50 channels max, the oldest log will be deleted when full

#### Member Pruning

★ Added option to mark prunable members with role

#### Bug Fixes

★ Fixed typo that caused temporary VC channel editing menu to break

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.6.1</strong></mark></summary>

#### XP Menu

★ Removed auto-reset feature

★ Replaced “Period” button with “XP Reset” menu

　☆ /xp-reset removed

　☆ Can now specify role to reward at certain level on reset

★ Reset time estimate now a bit more accurate

　☆ Now displays in minutes instead of seconds

#### New Member Role Bypass

★ Added user right-click menu command Bypass New

　☆ Can be used to toggle manual bypass of new member role

#### Misc.

★ Increased number of roles selectable in /prune

★ Removed right-click menu commands from Starbot DMs

#### Bug Fixes

★ Fixed errors with survey editing menu

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.6.0</strong></mark></summary>

#### Moderation Settings

★ Warning menu now expanded and separated

★ Max warning punishment can now be selected (used to be ban only)

　☆ Timeout (variable lengths)

　☆ Ban

　☆ Role assignment (for custom punishments)

　　✦ Warning role no longer assigned to all users with any amount of warnings

#### Moderation Logs

★ Master log can be specified and will be sent all enabled log types

★ Moderation log channels can now be different for each type of log

　☆ Warning, timeout, ban, and ghost message log channels can all be individually specified

　☆ If master log is enabled, logs will be sent to both channels

★ Timestamps now included in moderation logs

#### Settings Menu

★ Reverted settings menu (main) to original view

　☆ Much less cluttered

★ Updated settings to match updates

★ Lowest mod power (manage messages) mods can now use /settings

　☆ If necessary permissions not there, read-only

#### Rooms

★ Invite/block/kick menus now use a user menu

#### Website

★ Starbot website now secure (now uses HTTPS connection)

#### Internal

★ Revamped outdated “warnings” property in server data to “moderation”

　☆ Also restructured to match new moderation log update

#### Bug Fixes

★ Fixed newbie role criteria being judged incorrectly

★ Removed some code that caused Starbot to go offline when exiting program

　☆ I’m big dumb lmao

★ Fixed errors being thrown when a DM message was deleted

★ Fixed /translate hanging on error without error message

★ Disabled settings button in /help when member has no mod permissions

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.5.2</strong></mark></summary>

#### Newbie Role

★ Newbie role designation added

　☆ Given to new members on entry

　☆ Automatically removed when message requirement and one other are met (customizable)\
　　✦ X messages sent (default: 5)

　　✦ X days since joining (default: 14) -or-

　　✦ X hours spent in VC (default: 10)

#### Special Roles (Settings)

★ Bot and entry roles combined with newbie role into Special Roles in settings

★ These roles can now be easily changed individually through the menu

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.5.1</strong></mark></summary>

#### Ghost Message Logging

★ Added option to log “ghost messages” in moderation log

　☆ Ghost messages are messages that are deleted shortly after being sent

　☆ Time can be set in seconds from 1\~999 seconds

　☆ Bot messages and deletions by bots are ignored

　☆ Temporary VC channels are ignored

</details>

<details>

<summary><mark style="color:$primary;">4.5.0</mark></summary>

#### Breakout Rooms

★ /breakout can be used to split all users in a voice channel into random groups

　☆ Groups will be as even-sized as possible

　☆ Can be set as automatic VC rooms (disappear after use)

　☆ Original channel can be set to be deleted after all users moved

#### Member Pruning

★ /prune can be used to take actions on users without certain roles

　☆ If a member has none of the specified roles, they can be listed, kicked, or banned

#### Server Booster XP Bonus

★ XP bonus for server boosters can now be enabled in Level-Up System options

　☆ Bonus can be set from +0% to +100% (in increments of 20%)

#### Bug Fixes

★ Fixed bug where XP rate could not be set to 0 from website

★ Fixed bug where /ban would not respond

★ Fixed bug where boost message would not be saved

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.4.4</strong></mark></summary>

#### Bot Roles

★ Bots are now automatically assigned this role on entry

#### Website

★ Website updated with Bot Role and VC Alert menus

★ Fixed readability on Sakura theme

★ Role menu options now keep color when selected

★ Role menu options order now matches Discord

#### Bug Fixes

★ Removed obsolete TTS bot check in room visibility settings

★ Reverted accidental swapping of alpha and main port listening

　☆ Website’s back up - sorry!

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.4.3</strong></mark></summary>

#### Temporary VC

★ Added !EMOJI1/2/3! variable to room names (adds a random emoji)

#### Permission Check Command

★ Added command (/permissions) to check channels for missing permissions

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.4.2</strong></mark></summary>

#### Moderation Logs

★ Added ability to pick and choose what is logged

　☆ Warnings・timeouts・bans

#### Bug Fixes

★ Fixed error with exit messages displaying

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.4.1</strong></mark></summary>

#### Temporary VC Text Archives

★ Temporary VC creation channels now have option to archive text channel

　☆ Instead of deleting, channel will be moved to specified category

★ Temporary VC edit menu switched to menu from buttons

#### Profile Cards

★ Image generated profile card now in /profile

#### Surveys

★ Removed ID from footer of survey responses

★ Title in survey responses now link to survey forms

#### Misc.

★ Changed !INC! (counter variable for things like VC room number) to !NUM!

#### Bug Fixes

★ Fixed /pick not working when no select amount was specified

★ Fixed moderation menu in settings not opening

★ Fixed VC setting buttons not working due to internal renaming

★ Fixed /help report/feedback button not working

★ Removed deprecated /form

★ Fixed survey editing errors

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.4.0</strong></mark></summary>

#### Changelog

★ Moved changelog to Google Docs

#### Bot Role

★ Added ability to specify server bot role

#### Temporary VC

★ Refactored code to speed up creation process

#### VC Alerts

★ VC alert feature added

　☆ When enabled, creates a log of VC joins/exits

　☆ Can be set to first/last join/exit, or all

　☆ Can mention a specified role on join

#### Polls

★ Simple polls can now be created

#### Right-Click Menu

★ Users can now be warned/unwarned through right-click menu

★ Plain messages can now be converted to embeds with Embedify

#### Bug Fixes

★ Fixed Starbot icon not displaying in certain messages

★ Fixed image-style enter/exit message font

★ Fixed image-style enter/exit messages not sending

★ Fixed entry role not being assigned on server join

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.3.0</strong></mark></summary>

#### Website

★ Starbot website/dashboard now up and running again&#x20;

　☆ User info and server settings&#x20;

　☆ Themes for your A E S T H E T I C&#x20;

#### Dedicated Server&#x20;

★ Starbot now runs on a private web server&#x20;

★ Starbot no longer depends on my laptop & WiFi&#x20;

★ Uptime should be longer&#x20;

#### Entry Roles

★ Role assignment on server entry feature added&#x20;

　☆ Can be mass assigned retroactively&#x20;

#### Forms/Surveys

★ Forms have been improved (now surveys)&#x20;

　☆ Regular response or ticket system (old forms)&#x20;

#### Message Right-Click Menu

★ Message commands condensed, respond to message type&#x20;

　☆ Edit title and edit message now universal&#x20;

#### Bug Fixes

★ Fixed bug where VC rooms would hang if user left creation channel before being moved&#x20;

★ Fixed bug where VC room counter wouldn't go past 2

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.2.1</strong></mark></summary>

#### TTS Bots

Temporary VC text channels now include TTS bot permissions&#x20;

　☆ Checks server for TTS bots on creation&#x20;

　☆ Shovel (blue, red, green) currently supported&#x20;

#### Bug Fixes

★ Timeout moderations logs properly send&#x20;

★ Inventory not displaying (bag/shop) fixed&#x20;

★ Fixed Starbot room settings not working&#x20;

　☆ Ownership, visibility, invite, kick&#x20;

★ Fixed bug where role menu would ignore input title&#x20;

★ Fixed bug where only one reward role could be removed at a time

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.2.0</strong></mark></summary>

#### Channel Select Menus

★ Settings that required channel mentions updated&#x20;

　☆ Channels can now be selected from a list&#x20;

#### Forms/Role Select Menus

★ Forms/role select menus now editable through right click menu&#x20;

　☆ Title & message individually editable&#x20;

　☆ Single/multi-select editable (role select)&#x20;

#### XP Reset Command

★ Server admins can now reset user XP/levels&#x20;

　☆ Reward roles will automatically be reset&#x20;

　☆ Full effects take some time&#x20;

#### Bug Fixes

&#x20; ★ Fixed error that happened when duplicate roles were added&#x20;

&#x20; ★ Fixed role select menus not sorting&#x20;

&#x20; ★ Fixed XP leaderboard showing less than 10 members when someone who left was in the top 10&#x20;

&#x20; ★ Fixed bag not displaying&#x20;

#### Internal

★ Banned (from Starbot) users now able to use non-command features&#x20;

　☆ Server role menus/forms

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.1.2</strong></mark></summary>

#### Bug Fixes

★ XP / Level calculation corrected&#x20;

　☆ Overflowing XP will be corrected at next XP gain&#x20;

★ Fixed occasional error when creating VC rooms&#x20;

#### Internal

★ Server dashboard functionality incorporated&#x20;

★ Server VC counts now accurate&#x20;

★ Starbot server/user bans implemented

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.1.1</strong></mark></summary>

#### Games

★ Rock Paper Scissors (Janken) re-added as game&#x20;

　☆ Can be played against bot or another user&#x20;

★ /quit can now be used to leave games&#x20;

#### Items

★ Member's Card items restored&#x20;

★ Fatal Frames no longer affect Spirit Seal or materials for it&#x20;

#### Bug Fixes

★ Fixed error where enter/exit messages wouldn't save&#x20;

★ Fixed error where DMs wouldn't send unless user had DMed before&#x20;

#### Misc.

★ Slash command tooltips now display as command mentions&#x20;

★ /collect cooldown reverted to 1 hour&#x20;

　☆ Amounts adjusted (✪ 100-500)(x1,x5) → (✪ 250-1000)(x1,x3)&#x20;

#### Internal

★ Updated craft/bag/VC channel display code to loop instead of multiple chunks

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.1.0</strong></mark></summary>

#### New Content

★ Old mini-game system re-implemented and improved&#x20;

　☆ Requires being in VC&#x20;

　☆ Faker added to games&#x20;

★ /beg command added&#x20;

★ New items, gear, and achievements added&#x20;

★ Starbot now replies to DMs&#x20;

#### Items

★ Fake Coin now useable&#x20;

#### Bug Fixes

★ Fixed some items occasionally being unuseable&#x20;

★ Fixed DM slash commands

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.0.1</strong></mark></summary>

#### Items

★ Equippable items now work properly&#x20;

★ Energy system implemented&#x20;

★ Food & drink items now restore energy&#x20;

★ Giving items to others restored&#x20;

#### Bug Fixes

★ Fixed useable items randomly not working&#x20;

★ Fixed item shop menus (buy/sell)&#x20;

★ Item shop refresh time now displays properly (midnight, UTC 9)&#x20;

★ Mod log creation fixed&#x20;

★ Event items no longer appear in shop&#x20;

#### Misc.

★ Achievement icons in menu updated &#x20;

★ Slash command options localized&#x20;

#### Internal

★ Database connection error no longer floods console

</details>

<details>

<summary><mark style="color:$primary;"><strong>4.0.0</strong></mark></summary>

#### General

★ 100% switched to slash commands&#x20;

★ Simplified settings&#x20;

★ Menu navigation smoother & easier to use&#x20;

★ Help menu repurposed (slash commands already show info)&#x20;

#### Data

★ Server data now has 1 week grace period after bot leaves&#x20;

★ ✪ is now global&#x20;

#### Moderation

★ Added the ability to mass ban (up to 10) users at once&#x20;

#### Trading Cards

★ Trading cards now have the option to be shown off&#x20;

#### Internal

★ Rewrote a TON of code for cleanliness&#x20;

★ Updated code to fit with discord.js v14 standards &#x20;

★ Changed how forms are handled&#x20;

★ Item database now handled with spreadsheet&#x20;

#### Removed

★ Spellcasting&#x20;

★ EN/JP dictionary&#x20;

★ Janken&#x20;

★ Coin and item gifting&#x20;

★ Starbot mail

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>3.0.0</strong></mark></summary>

#### Settings

★ Overhauled settings menu into comprehensive menu&#x20;

　☆ General settings &#x20;

　☆ Temporary VC settings &#x20;

　　✦Make and Edit commands merged&#x20;

　☆ Warning settings &#x20;

　☆ Ban settings &#x20;

　☆ Enter/exit message settings &#x20;

　☆ Level system settings &#x20;

　☆ Channel designations &#x20;

#### Inventory

★ Overhauled inventory into comprehensive menu&#x20;

　☆ Items &#x20;

　　✦ Items display rank by color &#x20;

　☆ Give (items & coins) &#x20;

　☆ Spellbook &#x20;

　☆ Trading cards &#x20;

#### Items & Spells

★ New items & spells&#x20;

★ Some spells reworked&#x20;

#### Shop

★ Buy and sell commands merged into shop command&#x20;

　☆ Sell menu redesigned &#x20;

　☆ Buy menu redesigned &#x20;

　　✦ Shop changes daily &#x20;

　☆ Spellbook &#x20;

　☆ Trading cards &#x20;

#### Gacha & Slots

★ Gacha menu redesigned &#x20;

★ 'Pull again' functionality added &#x20;

#### Mail

★ Removed limit on user inbox storage &#x20;

★ Added page system to inbox &#x20;

★ Added visual feedback when deleting / claiming &#x20;

★ Message total now only includes server mail&#x20;

#### Slash Commands

★ Still only English descriptions available&#x20;

★ New commands have been added&#x20;

#### Misc.

★ Got rid of auto-closing menus (gacha, bag, etc.) &#x20;

★ Added notes for when user is under an item's effect &#x20;

　☆ Dark gem, fake coin, etc.&#x20;

★ Most menus have been upgraded for ease-of-use&#x20;

#### Bug Fixes

★ Fixed a big where Starbot's startup guide wouldn't work&#x20;

★ Fixed a bug where multiple Starter Boxes could be obtained&#x20;

★ Fixed a bug where mail couldn't be deleted &#x20;

★ Fixed some spells and items not executing fully&#x20;

★ Fixed a bug where spell giving was inaccurate&#x20;

　☆ Fixed old spells displaying 'new spell'&#x20;

　☆ Chance for new spells \*actually\* increased&#x20;

#### Internal

★ Server and global mail storage separated&#x20;

★ Added builder functions to lessen redundant code&#x20;

★ Changed Starter Box delivery condition&#x20;

★ Startup message permission check reworked&#x20;

#### Known Issues

★ Monitoring inbox system for mail duplication errors

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>2.4.4</strong></mark></summary>

#### Bug Fixes

★ Fixed a bug where Read All could not be used in inbox&#x20;

★ Fixed a bug where backups and backup backups weren't... backing up &#x20;

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.4.3</strong></mark></summary>

#### Slash Commands

★ Began support for '/' commands&#x20;

　☆ Currently only /help is available&#x20;

　☆ Displays in English only (for now), but response language is unchanged&#x20;

　☆ Servers that had Starbot will need to re-click “Add to Server”

#### Bug Fixes

★ Fixed a bug where every 10th level's required XP was calculated incorrectly&#x20;

★ Fixed some spells that wouldn't activate&#x20;

★ Fixed a bug that caused ★ to increase in VC&#x20;

★ Fixed a bug where unusable items had a use button&#x20;

★ Fixed a bug where users could interact with other users' commands on older messages&#x20;

★ Fixed some inbox buttons that were always in English&#x20;

#### Internal

★ Refactored interaction code to be cleaner and more accurate

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.4.2</strong></mark></summary>

#### Achievements

★ Made achievements show in pages&#x20;

★ You can now select an achievement to view details&#x20;

#### Internal

★ Starbot now handles banned servers and users

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.4.1</strong></mark></summary>

#### Version Numbering

★ Lowered Starbot version number by 1 (1.0.0 -> 0.0.1 (beta))

#### Currency

★ Events now have a chance to award ★&#x20;

★ Gacha prizes and types adjusted&#x20;

★ New ★ gacha added&#x20;

　☆ Game codes moved here&#x20;

★ Cleaner currency display in various areas&#x20;

★ Star Coins now denoted by ☆&#x20;

★ Event Coins now denoted by ✲

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.4.0</strong></mark></summary>

#### Global Data

★ Achievements and trading cards are now global&#x20;

★ Inbox is now global&#x20;

　☆ Server-specific messages will only appear in-server&#x20;

#### Currency

★ ✪ is now per-server currency&#x20;

★ ★ is now global currency &#x20;

★ ✪ has been deflated and item costs/gacha/slots have been adjusted&#x20;

#### Misc.

★ Embed style cards have been made much cleaner&#x20;

★ XP min rate raised to ×0.10&#x20;

★ XP max rate lowered to ×5.00&#x20;

★ Achievements can now only be gained in servers with 10 members&#x20;

★ Janken added to games menu&#x20;

★ Food items now edible

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.3.0</strong></mark></summary>

#### Starbot Mail

★ Created a new inbox system with Starbot&#x20;

★ Inbox can be checked with sb.mail or sb.inbox

★ Achievement notifications have been moved here&#x20;

　☆ Achievement DMs will no longer be sent&#x20;

　☆ Rewards must now be manually claimed&#x20;

#### User Cards

★ sb.me's output card style has been changed&#x20;

　☆ More info has been added&#x20;

　☆ Displays large PNG of user avatar

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.2.2</strong></mark></summary>

#### Data Wipe

★ All server data has been unfortunately wiped... 😢 &#x20;

★ Any user who uses a Starbot command this week will get an apology gift&#x20;

#### VC Creation

★ Can now mention or specify channel ID to make VC creation channel from existing channel&#x20;

★ Fixed some parts with sb.vcedit that were bugged/hard to read&#x20;

#### Bot Stats

★ Bot stats are now available to see with sb.starbot

#### Internal

★ Data will now have 3 backups, written in intervals&#x20;

　☆ Every 1 second (basic writing)&#x20;

　☆ Every 5 minutes (for quick fixes)&#x20;

　☆ Every 1 hour (for further backups)

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.2.1</strong></mark></summary>

#### XP System

★ sb.xp fully implemented in menu/button style&#x20;

★ Leveling rate now gets slower the higher your level is&#x20;

★ Level reward roles now assign and update properly&#x20;

★ New option to set server leaderboard to monthly&#x20;

★ Removed achievement XP to account for monthly leaderboards&#x20;

★ Leaderboard data now separate from user info (internal)

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.2.0</strong></mark></summary>

#### Commands

★ Command to create add/remove role menus implemented&#x20;

　☆ sb.role will create a role select menu&#x20;

　☆ Will add/remove based on if user has role or not&#x20;

#### Events

★ Implemented New Year's event&#x20;

#### Items

★ Raygun now has full functionality&#x20;

#### Bug Fixes

★ Fixed dice roll bug that didn't ignore strange input&#x20;

★ Fixed bug where temporary VC data wouldn't clear&#x20;

★ Fixed bug preventing greeting card/messages from being made&#x20;

★ Fixed bug where casting Alchemize took/gave items reversed&#x20;

#### Internal

★ Changed how bug reports are formatted

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.1.1</strong></mark></summary>

#### Bug Fixes

★ Fixed dice roll function&#x20;

★ Fixed language/quote settings in web dashboard&#x20;

★ Fixed a problem with welcome/stat card making&#x20;

★ Fixed total user count in stats command&#x20;

★ Fixed bug with using help on specific commands&#x20;

#### XP System

★ Adjusted XP requirements&#x20;

★ Adjusted achievement XP rewards&#x20;

#### Internal&#x20;

★ Fixed & expanded reload command&#x20;

　☆ Can make more changes without restarting Starbot&#x20;

★ Cleaned user verification function&#x20;

★ Changed load order so bot doesn't react before 100% ready

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.1.0</strong></mark></summary>

#### General

★ Updated Starbot's help menu&#x20;

　☆ Notes, bug reports, and donations added&#x20;

#### Spells

★ Silence/Mute has new functionality&#x20;

★ Void Thief now has a higher success rate&#x20;

#### Bug Fixes

★ Starbot's status now correctly displays room amount&#x20;

★ Temporary room counters fixed&#x20;

★ Fixed some bugs with various items and spells&#x20;

★ Fixed some bugs that made janken unplayable&#x20;

★ Fixed an error with the Wealth aura&#x20;

★ Fixed an error where Starbot DMs couldn't be disabled&#x20;

#### Internal

★ Updated newly deprecated embed code

</details>

<details>

<summary><mark style="color:$primary;"><strong>2.0.0</strong></mark></summary>

#### General

★ Added a command bug killswitch&#x20;

　☆ If a command causes an error, it will auto-disable&#x20;

★ XP rates have been adjusted&#x20;

#### Items

★ Key items can now be viewed normally in bag&#x20;

★ Gacha rates adjusted&#x20;

　☆ Cursed item rates lowered&#x20;

　☆ Spirit Seal rates increased&#x20;

#### Spells

★ New spells added&#x20;

★ Old Scroll spells have higher chance of being new&#x20;

Games

★ Truth or Dare cards added&#x20;

★ Faker and Word Wolf \*direct commands\* removed&#x20;

#### Statuses

★ User stats and statuses have been split&#x20;

★ You can now check details for each status&#x20;

★ Auras (server-wide statuses) added&#x20;

　☆ Starbot message colors change based on aura&#x20;

#### Bug Fixes

★ Fixed a bug where Starbot would leave VC too quickly&#x20;

★ Fixed a bug with Starbot's entrance message&#x20;

★ Fixed some temporary VC channel bugs&#x20;

★ Fixed a bug that allowed others to interact with other users' menus&#x20;

#### Internal

★ Moved server data to external database&#x20;

　☆ Game codes now hidden&#x20;

★ Slightly increased bot speed&#x20;

★ Rearranged file/folder structure&#x20;

★ Functions are cleaner and require less input

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>1.0.0</strong></mark></summary>

#### General

★ Updated code to fit with discord.js v13 standards

★ Tons of new features

★ Added menus, buttons, etc.

</details>

***

<details>

<summary><mark style="color:$primary;"><strong>0.0.X</strong></mark></summary>

#### General

★ Discord.js v12

★ This was a mess

★ English & Japanese files were separate

★ All commands were in a single file LMAO

★ B E T A | B E T A | B E T A

</details>
