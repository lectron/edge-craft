# edge-craft
BungeeCord plugins that shows Minecraft Bukkit server motd and number of players as if ping_passthrough is on

# Inspirations
- RedisBungee

# This plugin:
- Works well with multi-proxy, one spigot server setup
- does show cached total number of players by counting the number of players in the targeted default Spigot server
- does show MOTD cached from the Spigot server in the targeted default Spigot server
- does NOT passthrough ping (it affects load performance perception when proxy is near the user but the server is far away)
- does NOT passthrough motd (it affects load performance perception when proxy is near the user but the server is far away)
- does NOT need to link your proxy servers together via any database at all
- does NOT perform load balancing of players on multiple proxies
- does NOT synchronize your BungeeCord configuration
