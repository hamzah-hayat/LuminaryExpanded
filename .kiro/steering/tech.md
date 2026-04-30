# Tech Stack

## Platform
- **Game**: Stellaris (Paradox Interactive grand strategy game)
- **Engine**: Clausewitz Engine
- **Scripting Language**: Paradox Script (custom declarative scripting language using curly-brace blocks)
- **Target Version**: Stellaris v4.3.*

## Build & Deployment
There is no build system or compilation step. The mod is loaded directly by the Stellaris launcher from the mod folder. Deployment is via Steam Workshop upload or manual folder copy.

## File Formats
- `.txt` — All game script files (events, traits, situations, effects, etc.)
- `.yml` — Localisation files (UTF-8 with BOM, YAML-like format)
- `.mod` — Mod descriptor (key-value pairs)

## Key Conventions
- Event IDs use the `paragon` namespace (e.g., `paragon.5001`, `paragon.5080`)
- Custom mod events use IDs in the 5000-6999 range
- Script variables use `@` prefix for constants (e.g., `@base_agenda_cost = 7000`)
- Localisation keys use colon-number suffix for priority (e.g., `key:0 "text"`)
- Localisation supports inline references like `$other_key$` and scope commands like `[Owner.Ruler.GetName]`

## Testing
No automated testing framework. Testing is done by running the mod in-game and verifying behavior through the Stellaris console and observation. Use the Stellaris error log (`Documents/Paradox Interactive/Stellaris/logs/error.log`) to check for script errors.
