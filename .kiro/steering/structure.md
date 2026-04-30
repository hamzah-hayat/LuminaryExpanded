# Project Structure

```
/
├── descriptor.mod                  # Mod metadata (version, tags, supported game version)
├── thumbnail.png                   # Steam Workshop thumbnail
├── common/                         # Game data definitions
│   ├── council_agendas/            # Council agenda definitions
│   ├── on_actions/                 # Event triggers (hooks into game actions)
│   ├── script_values/              # Computed values used in scripts
│   ├── scripted_effects/           # Reusable effect blocks (like functions)
│   ├── situations/                 # Situation definitions (bidirectional progress systems)
│   └── traits/                     # Leader trait definitions
├── events/                         # Event scripts (narrative events, triggers, options)
│   └── origin_events_paragon.txt   # Main event file (overwrites vanilla)
└── localisation/
    ├── english/                    # New localisation strings
    │   └── LuminaryExpanded_l_english.yml
    └── replace/
        └── english/                # Overwritten vanilla localisation strings
            └── LuminaryExpanded_replace_l_english.yml
```

## Naming Conventions
- Mod-specific files are prefixed with `LuminaryExpanded_` (e.g., `LuminaryExpanded_scripted_effects.txt`)
- Files that overwrite vanilla keep their original names (e.g., `origin_events_paragon.txt`, `10_paragon_traits.txt`)
- Effects/Triggers/Modifiers use `le_` prefix to ensure no conflicts with vanilla scripts or other mods
- Country flags use descriptive names (e.g., `luminary_ethic_chosen`, `origin_upgrade_agendas_situation`)

## Localisation
- New strings go in `localisation/english/LuminaryExpanded_l_english.yml`
- Strings that replace vanilla go in `localisation/replace/english/LuminaryExpanded_replace_l_english.yml`
- The `replace` folder signals to the engine that these strings override base game strings

## Vanilla Overwrites
This mod fully replaces two vanilla files:
- `events/origin_events_paragon.txt`
- `common/traits/10_paragon_traits.txt`

Edited sections within these files are marked with `# LumEx` comments.
