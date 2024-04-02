# Witch Hunter

Witch Hunter: A Multiplayer Horror Game is developed to present an entaining and exciting
horror game. It is inspired by medieval beliefs that demons can shape-shift into various
animals and reside in the dark, eerie forests.

In this game, players are divided into two factions: the Witch Hunters and the Witch.
The Witch Hunters must work together to survive and perform rituals to eliminate the Witch.
They must capture demonized deers, using sacred knives and traps. Then, they must use the
captured deers’ blood to perform rituals. Meanwhile, the Witch aims to hinder and deceive
the opposing faction by transforming into demonized deers and using magic to attack.

The game is developed using Unreal Engine to immerse players in a realistic experience
through a first-person perspective. It presents an exciting and frightening experience.

![breath_of_death](https://github.com/PutawanDE/WitchHunter/assets/31311349/b538c48e-2fe8-4a00-94a1-697794c05e93)

![ritual-complete](https://github.com/PutawanDE/WitchHunter/assets/31311349/d63e6e03-6740-44b3-8ff7-370006efed41)


## Details

Witch Hunter is a senior project for  Degree of Bachelor of Engineering, Department of Computer Engineering,
Faculty of Engineering, Chiang Mai University, 2023. It is developed Tanadol Deachprapakorn and Purich Seenuallae with Aj. Karn Patanukhom as project advisor.
[See project details](https://project.cpe.eng.cmu.ac.th/projectDetail/855).

## How to run from source in Editor?

1. Install Unreal Engine version 5.1.1
2. Clone this repo.
3. Install [Regex in Blueprints](https://www.unrealengine.com/marketplace/en-US/product/regex-in-blueprints?sessionInvalidated=true) plugin and enable it.
4. Double-click `WitchHunter.uproject` to open this project.
5. Enter `net.AllowPIESeamlessTravel true` into Console Command to enable Server Seamless Travel in Editor.
6. Click the three-dot menu on Play menu to Change Play Mode and Play Settings.
7. Set the Number of Players to three.
8. Go to net mode and make sure it is Play As Standalone.
9. Set Play mode to "New Editor Window (PIE)".
10. Click Play.
11. Type `~` on any PIE window to enter command.
12. Use command `open 127.0.0.1` to join room.

## How to run from Build?

1. Download the Windows Installer in Github release section.
2. Open and continue with the Installation wizard.

## How to Play?

[Gameplay Video](https://www.youtube.com/watch?v=8bLsv8O-AGk&list=PLDbf2zZ3BX8Kd9n4L1BYlkORXF2isnZsh&index=1)

### Hosting

1. The game is LAN only, however you can use VPN, tunneling e.g. Hamachi, Tailscale, Zerotier.
2. Three persons per room only. One must be the host, and the other two must join by IP address.
3. The host must give their IP address to the other two players. The IP address shown in game is the host's local IP address.
4. Need 1 witch and 2 hunters to start the game. The host must press START.

### Witch

1. Witch must kill all hunters before they successfully perform 6 rituals.
2. Witch can possess any deer on the map to disguise and lure the hunters.
3. Witch can see deers, if the deer is running then there are hunters nearby.

### Hunter

1. Hunter must perform the rituals by capturing deers and using their blood in rituals.
2. Hunter must catch deers by throwing sacred knives, or using trap. Deers are easily frightened by sounds, so be discreet by crouching.
3. After Hunter catch the deer, they must retrieve its blood.
4. Then, Hunter can perform rituals at any ritual points using the deer's blood.
5. Hunters must perform the ritual 6 times, each time last 30 seconds.
6. Hunter can perform the rituals on the same ritual point.
7. Hunter can cancel the ritual anytime by pressing the `E` key.
8. After they successfully perform a ritual, they gain HP.
9. Hunter can be attacked 3 times.
10. After they are dead, they will become a spirit and can revive by getting back to their dead body.
11. Hunter can revive only 1 time.
12. Hunter can stun Witch by throwing sacred knife, or placing it on the ground and let the Witch step on.
13. If both of them die at the same time, then they are lost.
14. If both of them can't perform 6 rituals within the time limit, they are lost.

![Witch-Hunter-Manual](https://github.com/PutawanDE/WitchHunter/assets/31311349/266ba401-f2ed-41bf-a119-620f4faf9b90)

