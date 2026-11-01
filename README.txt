FriendRadar Pro 26.2 - independent Fabric mod source (UNCOMPILED, UNTESTED)

FEATURES:
- Nearby player HUD in action bar, refreshed every 10 ticks
- Closest player name, distance in blocks, nearby player count
- R: enable/disable HUD
- G: cycle 16/32/64/128 block range
- H: add/remove closest nearby player from friends
- Attempts to cancel client-side attacks on marked friends via Fabric AttackEntityCallback
- Settings saved in config/friendradarpro.properties

BUILD ON WINDOWS:
1. Install JDK 25 and Gradle 9.5.1, and ensure both are on PATH.
2. Open a terminal in this folder.
3. Run: gradle build
4. If build succeeds, find build/libs/friendradar-pro-26.2-2.0.0.jar
5. Place the JAR in .minecraft/mods along with compatible Fabric API.

IMPORTANT:
- This is SOURCE CODE, not a working .jar.
- Version numbers and Minecraft 26.2 mappings have not been verified.
- Building may require adapting Fabric API or Minecraft signatures.
- Friend attack cancellation is client-side and not a server-enforced PvP rule.
- Action-bar display is not a graphical compass or configuration GUI.
- The user must test on their exact Minecraft and Fabric version.
