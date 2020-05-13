# Towny

Towny is our block protection plugin. Players group together into `Towns` that can then claim chunks that prevent outsiders from building in these chunks. Towns can also group together into `Nations`.

## Basic Commands

You can join towns after they invite you with `/accept (town name`), or join an open one with `/t join (name)`. If you find a plot that is marked for sale, and you have the money to claim it, ask the mayor or an assistant if you can have it, and use `/plot claim` if so. If you find a town to be on the negative side, you can leave with `/t leave`. Make sure to follow any additional rules or building codes your town might have. You can chat with your town specifically with `/tc`, and you can teleport to it at any time (excluding when in combat) with `/t spawn`. You can add friends to your plots using `/res friend add (name)` and you can set permissions for that friend using `/plot set perm friend (build, destroy, or switch) (on or off)`.


## Creating a Town

To create a town you need a total of $10,000. Don't let this amount fool you, though, as you will need a minimum of $5 extra to keep your town up for a single day if you only remain with the home chunk. Speaking of chunks, you can use f3+g, pressing both at once, to see the chunk map, in which the towny plugin bases claims off of. Once you create your town, use `/t new (name)`, you should use `/t deposit (most of your money)` in order to keep the town running and allow for additional claims. Each town's bank can hold up to $1,000,000. Outposts, (claims not attached to your town border, you can create these with `/t claim outpost`), cost $2.5k. Most basic information, such as a resident list, town size, and your town balance can be found using `/t`. Pvp is automatically enabled within a town, and you can use `/t toggle pvp` to turn it off. Many players have trouble making nether portals when they start, and that can be fixed using `/plot toggle fire` on the plot you want to make the portal on. You can also `/t toggle explosion`, `taxpercent`, `open` (which allows anyone to use `/t join` with your town), `mobs`, and `jail` to jail players in your town. You can also `/plot toggle` mobs, pvp, fire, and explosions. You can teleport to your town (or any other town within your nation) with `/t spawn`, or `/t spawn (name)`.

You can invite players to your town using `/t invite (name)`, and they can accept this invite using `/accept (town name)`. You can give players their own plots using `/plot forsale (amount you want to sell for)` on a claimed chunk, and they can use `/plot claim` to claim it. You can kick players from your town using `/t kick`, and remove plots from being for sale using `/plot nfs`. You can name plots using `/plot set name (name)`, and you can set plots to be a specialized type (inn, farm, embassy, jail, shot, and arena) using `/plot set` (one of the aforementioned types). Embassy type plots can be claimed by players outside of your town after being set for sale. You can promote players to senior positions, such as banker, assistant, or helper using `/t rank add (name) (rank)`. You can set player taxes using `/t set taxes (amount)`. You can change your town spawn using `/t set homeblock`, and then `/t set spawn`.

## Permissions

The Towny plugin has a variety of different permissions that can be changed and altered based on build, destroy, and switch. Build and destroy perms are obvious, and the switch perm includes opening doors, trapdoors, chests, and toggling switches, buttons, and pressure plates.

These perms can be altered using `/t` or `/plot set perm (rank, being resident, outsider, friend, or ally) (build, destroy, or switch) (on/off)`. Alternatively, if you want to turn on all perms for a single class on, you can use `/t` or `/plot set perm (resident, outsider, friend, or ally) (on/off)`.

Each class for perms are different. Residents are players within your town, allies are players in your nation, outsiders are non allies or residents, and friends are people you add using the `/res friend add` command, which can add them to your plots. You can chose with plots they can use using `/plot set perm friend (build, destroy, switch) (on/off)` in order to ensure certain plots are protected.

## Nations

Many players wish to create their own nations, and that can be done with 15k and with `/n new (name)`. You can invite towns to your nation using `/n invite (town name)`, and they can accept that invite with `/t accept (town name)`. You can set titles and surnames of players using `/n set title/surname (name) (the title or surname)`. You can set a nation spawn within the capital city (being the city of the person who creates the nation) using `/n set spawn`. You can change who is nation leader using `/n set king (player name)`. You can ally other nations using `/n ally add (nation name)` so they can access your `/n spawn`, and you can enemy nations to show your distaste for them with `/n enemy add (nation name)`. You can access allied nation spawns using `/n spawn (nation name`)`. Nations can store $5,000,000 in their bank.

In order to speak specifically to either your town or nation, you can use `/tc` for town chat, or `/nc` for nation chat.