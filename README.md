# zNametags
Per-player nametag library for bukkit

This is a small library that allows per-player scoreboard team prefixes and suffixes via packets and reflection.

The API is simple,
simply call NametagManager.setup(player) on join,
and NametagManager.remove(player) on quit.

now, to gain access to a NametagPlayer simply call the getPlayer method from the NametagManager class.

Once you have access to your NametagPlayer, you can start setting Nametags.
Now, I suggest having FINAL nametags rather than instantiating a new one every time you want to set a nametag.

From there you can simply call the setNametag method from the NametagPlayer and you're set!

