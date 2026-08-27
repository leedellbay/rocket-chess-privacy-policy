# Rocket Chess — the account

Written for two readers: an App Store or Play reviewer checking how account
creation, editing and deletion work, and anyone using the app who wants to
know the same thing.

## There is no account, in the usual sense

Rocket Chess has no sign-in, no email or password, and no server-side account
of ours. What the app calls a **player** is a name kept in the app's private
storage on the device — nothing more. More than one player can exist side by
side on the same device (that's what pass-and-play needs), and one of them is
the one currently "playing."

Playing online (see [https://leedellbay.github.io/rocket-chess-privacy-policy/ §2](privacy policy))
does not change this: hosting or joining a game uses a player you already
created on the device. It does not create a separate account anywhere, and
nothing about a player is stored on the relay — see the privacy policy for
what online play does send, and for how long.

## Creating a player

From the hub screen, the card labelled **"Your account"** (or **"Add a
player"** once one exists) opens a name dialog:

- 1–24 characters
- must be unique on that device (case-insensitive)
- stored only in the app's local storage; nothing is sent anywhere to create
  it

Creating a player selects it as the current one immediately.

## Editing a player

Tap **"Playing as \<name\>"** → **"Switch, rename, or add someone else"** to
open "Who is playing on this device." The pencil icon next to a player opens
**"Change name,"** which is the only thing about a player that can be
edited — a player has no other profile fields (an avatar initial and colour
are derived automatically from the name, not set separately).

Preferences — theme, board and piece colours, text size, difficulty, and so
on — travel with whichever player is current and switch automatically when
you switch players, but changing them is not an account edit: the account
itself is just the name.

## Deleting a player

Same sheet, trash icon next to a player, which asks for confirmation:

> Remove \<name\>? Their games and statistics go too. This cannot be undone.

Confirming removes, immediately and only on the device:

- the player entry itself
- every game record attributed to them, as either side
- their seat at the pass-and-play table and their selection as the current
  player, if either applied

There is no soft delete, no recovery period and no copy held anywhere else
to also delete — removing a player here is the entire deletion process.

## Playing without a player

A current player can be deselected without deleting them — **"Nobody, for
now"** in the same sheet. Games played this way aren't attributed to anyone
and don't count toward any statistics. This is not account deletion, just
playing without one chosen.

## Deleting everything at once

Uninstalling the app removes every player, every game record and every
preference along with it, since none of it is held anywhere but the device.
There is no cloud copy for us to also delete on our end.

## Where this is implemented

`lib/store/app_store.dart` — `addPlayer`, `rename`, `removePlayer`, `choose`.
`lib/ui/hub_screen.dart` — the dialogs and the "manage players" sheet
described above. Related policy language: `privacy policy`, sections 1
and 8.
