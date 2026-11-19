Privacy Policy
==============

Ludo, last updated November 19, 2026.

I made Ludo so friends can play together, and it keeps as little about you as it can and still run a game. There's no sign-up, no ads, no analytics and no tracking. You never give it your name, email or phone number.

What the server keeps
---------------------

The first time you open a room, the app signs you in with an anonymous account. That's a random ID and nothing else. The game server (Supabase, in the US) stores, for each room you're in:

- the room code and which seat is yours
- every move in the game, and the house rules the host picked
- votes about a player who left, and when the room last changed

Only the players in a room can read it. Your phone keeps the sign-in token so you stay the same player between launches.

If you report someone for what they said in voice, the server keeps the room code, your ID and theirs, and the reason you picked. Only I can read reports. Blocking someone stays on your phone, and the server never hears about it.

Voice chat
----------

Voice only turns on when you tap Join voice, and that's also when the app asks for the microphone. On Android it asks to show a notification too, since Android needs one while the mic is on in the background.

Your voice goes straight from your phone to the other players' phones. It never passes through my server and nothing records it. To connect, the phones swap their network addresses through the game server (passed along, not saved), and they ask a public address service run by Google or Cloudflare. That means the other players in the room, and those two services, can see your IP address while you talk.

How long it stays
-----------------

The server deletes a room 30 days after its last move, and a report after 90 days. Your anonymous account stays until you delete it.

Deleting your data
------------------

Tap Delete my data at the bottom of the home screen. It deletes your account and the reports you made or that are about you, and takes you out of every room you're in. Rooms where you were the only person go completely. If a game is still going, it carries on without you, and your seat stays on the board without anything that points back to you. If you've already uninstalled the app, there's nothing left that says which account was yours, so I can't find it for you. Its rooms still go after 30 days.

Kids
----

The app doesn't ask anyone's age, and it keeps the same few things above for everyone.

Changes and contact
-------------------

If this changes, I'll update the date at the top. Questions or deletion requests: adherodgames@gmail.com.
