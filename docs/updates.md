# starbaby Updates

## 0.1.0 (174)

The original native mini player no longer flashes during startup or page reloads.
Its renderer is retained in source for an explicit rollback, but is disabled from
launch. The web player is now the only mini-player presentation.

With Starbaby web 0.4.311, the player stays visible beneath menus without accepting
clicks through them. Metadata uses consistent year typography and muted em dashes.
Playback, media keys, shuffle, and Show/Hide Mini Player remain unchanged.

## 0.1.0 (173)

The mini player now shares Starbaby's web styling: a compact dark bar with
Previous, Play/Pause, Next, artwork, artist and album metadata, song title,
scrubber, elapsed/total time, play counts, Exclude, and the familiar star picker.

The native playback engine, media keys, account ownership, and shuffle remain
unchanged. Show/Hide Mini Player still works. The original native player remains
the fallback for older web versions and narrow windows. Requires web 0.4.306.

## 0.1.0 (172)

Music Shuffle is now available from the dice in the Mac app. Choose Unrated,
Highly Rated, or Never Played, then a decade. Native Next, Previous, and automatic
advancement follow the mix across albums with eligibility checks before playback.

Resuming the current song retains the mix. Pausing or changing playback cancels
pending native selections. Ordinary album playback and DJ are unchanged.
Requires the companion Starbaby web update 0.4.304.
