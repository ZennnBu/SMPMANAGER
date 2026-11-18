# WOWManager
Standalone Paper plugin project targeting Paper 1.21.11 / Java 21.

## Build
Install Maven and run `mvn package`. The output jar will be `target/WOWManager-1.0.0.jar`.

## Commands
- `/announcement <message>`
- `/setspawn`
- `/spawn`
- `/rank create <name>`
- `/rank delete <name>`
- `/rank set <player> <rank>`
- `/rank remove <player>`
- `/rank list`
- `/scoreboard` (toggle)
- `/scoreboard reload` (admin)

Admin commands require `wowmanager.admin` (default: operators).
Ranks currently provide prefixes and permission attachments. Rank inheritance, suffix display, tab formatting, economy, kills/deaths and persistent live scoreboard refresh are planned for the next iteration.
