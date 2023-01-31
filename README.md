# Bukkit-Java-Server-inoperable


Typically I host a minecraft server to a small community of players I've met. Once I was preparing to clean out my computer and moved all the server files off before I reset. However I reloaded them and now the whole thing doesn't work. The crash message I get it this:
   Running: 
   Failed to handle CraftCrashReport:
java.lang.NullPointerException: Cannot invoke "org.bukkit.Server.getName()" because "org.bukkit.Bukkit.server" is null
	at org.bukkit.Bukkit.getName(Bukkit.java:102)
	at org.bukkit.craftbukkit.v1_19_R1.CraftCrashReport.get(CraftCrashReport.java:23)
	at org.bukkit.craftbukkit.v1_19_R1.CraftCrashReport.get(CraftCrashReport.java:1)
	at net.minecraft.SystemReport.a(SourceFile:66)
	at net.minecraft.CrashReport.<init>(CrashReport.java:37)
	at net.minecraft.server.MinecraftServer.a(MinecraftServer.java:1046)
	at net.minecraft.server.MinecraftServer.v(MinecraftServer.java:991)
	at net.minecraft.server.MinecraftServer.lambda$0(MinecraftServer.java:285)
	at java.base/java.lang.Thread.run(Thread.java:833)

	Server Running: true
	Data Packs: vanilla, file/bukkit (incompatible), file/movecraft-data.zip (incompatible)
	World Generation: ERR
	Is Modded: ERR
	Type: Dedicated Server (map_server.txt)
    Any help is appreciated, even if it's some small detail I overlooked.
