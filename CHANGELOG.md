# 0.7.7
* Further improve CK2 localisation
* Add "starts_with" setting for config rule types
* Support multiple "path" settings for config rule types
* Support config rule types localisation being references to loc keys inside
# 0.7.6
* Improve CK2 localisation
# 0.7.5
* Fix CK2 loading
* Only load cached files if necessary
* Add CK2 DNA/Properties
# 0.7.4
* Better handling of changes to localisation files (update validation properly)
# 0.7.3
* Add support for CK2
# 0.7.2
* Validation context switches in localisation
* Reduce errors in debug output
# 0.7.0
* Complete EU4 support
* Prevent validation of vanilla files
* Make errors a little clearer
# 0.6.24
* Add completion for `@` script variables
* Add more detailed localisation in the hover tooltip for types (mainly eu4 for now)
* Sort completion list, moving items used in the same file to the top
# 0.6.23
* Significant performance improvements
# 0.6.22
* Enabled Code Outline
# 0.6.21
* Configure localisation commands from a config file called `localisation.cwt`
* Add modifier categories for HOI4
# 0.6.20
* Support other languages for EU4/HOI4
# 0.6.19
* Fix localisation of types
* Validate on swapping file
# 0.6.18
* Add "manual" setting for "rules_version", which combined with "rules_folder" to use a specific folder for config rules
* Provide completion for "event_target:"
* Add error for localisation that refers to itself
* Add stellaris building cap modifiers
# 0.6.16/17
* Add vanilla caching process for EU4 and HOI4
# 0.6.15
* Performance improvements
* Validation of localisation strings for EU4
# 0.6.14
* Add localisation for EU4/HOI4
# 0.6.13
* Update to 2.2.2
# 0.6.12
* Improved scope checking for effects/trigger/modifiers
# 0.6.11
* Automatically restart on rules update
* Improved validation of flags
# 0.6.10
* Add a warning when a file is opened instead of a mod folder
* Add features for rules: localisation can now be defined on types
# 0.6.9
* Add features for rules: `variable_field`
# 0.6.8
* Add some generated 2.2 modifiers
# 0.6.7
* Update to Stellaris 2.2
# 0.6.6
* Performance hotfix
# 0.6.5
* Add `folders.cwt` to manually override folders to be validated
# 0.6.4
* Fix crash when cachefile missing
# 0.6.3
* Add ability to cache vanilla files for Stellaris/EU4/HOI4 to use instead of embedded files
  Ctrl-Shift-p "cwtools: Generate cache"
* Remove requirement for git
* More fixes
* More hotfixes
# 0.6.2
* Basic HOI4 support
# 0.6.1
* Hotfixes!
# 0.6.0
* Enabled rule-based validation by default. Every file in your mod now gets detailed validation!
* Enabled completion by default. Every file in your mod should get intelligent auto-completion!
* Added auto-updating rules, controlled by the setting `cwtools.rules_version`.
# 0.5.38
* Updated rules
* Potential fix for linux/osx
* Reduced severity of localisation naming validators
* Add `severity` option for rules to manually set the severity of that rule (normally lower, from error to warning)
# 0.5.37
* Improved autocompletion (should now work everywhere)
* Increased resiliancy to errors, now won't restart on error
* Performance improvements
# 0.5.36
* Performance improvements and hotfix
# 0.5.35
* Add "Reload config rules" command to reload config rules
# 0.5.34
* Hotfix vanilla embedded files
* Performance improvements
# 0.5.33
* Fix locale issue with floats
* Fix scope hover info
* Slightly improve startup speed
* Fix crash on tooltip hover
* Add validation of localisation file encoding, header and name
# 0.5.32
* Performance improvements
* Hotfix some rules
# 0.5.31
* Improved config base validation
* Validation of value clauses
* Fix prescripted_countries embedded content
* Include syntax highlighting by default
# 0.5.30
* Update to 2.1.2
* Reduce flag usage to a warning
* Improve flag usage validator coverage
* Add megastructure/planet_class model validator
# 0.5.29
* Add flag usage validator
# 0.5.28
* Update config rules
# 0.5.27
* Fix completion
# 0.5.26
* Update config rules
# 0.5.25
* Add config rules for interface/gfx/sounds/music/fonts
* Add `path_strict` option for types which prevents subfolders being searched
* Add `severity = warning` option for types which reduces errors to warnings
* Add Alliance scope
* Add `percentage` value for config rules
# 0.5.24
* Reduce false-positives for localisation_synced references
* Add remaining missing scope commands
* Update config rules
# 0.5.23
* Add improved redundant AND and OR checks
* Update config rules
# 0.5.22
* Add "Find all references" (currently only works when right clicking on a reference)
* Update config rules with most of A-M
# 0.5.21
* Update config rules
# 0.5.20
* Add "Go to definition" (currently only works for mod defined types)
* Support "FROM" scopes
* Add `replace_scope` for config rules
* Add unnecessary AND validator
# 0.5.19
* Add basic support for HOI4
# 0.5.18
* Enable improved completion by default
# 0.5.17
* Add command "Generate missing loc for all files"
# 0.5.16
* Significantly improved general performance
* Validated anomaly localisation
# 0.5.15
* Fix completion in multi-mod projects
* Improve performance of config based validation
* Fix negative value parsing
# 0.5.14
* Add tile blocker localisation
* Add static_modifier desc localisation
* Add `push_scope` for config rules
# 0.5.13
* Add planet_killer localisation and other validation
# 0.5.12
* Add scope information tooltip
* Add support for `scope` rules
* Update config rules
# 0.5.11
* Update config rules
* Add support for localisation_synced rules
# 0.5.10
* Update config rules
* Add support for <type.subtype>
# 0.5.9
* Update config rules
# 0.5.8
* Add support for 'complex_enum'
# 0.5.7
* Bugfix <types>
# 0.5.6
* Add support for `localisation` value for cwt config

# 0.5.5
* Add support for more complicated keys in aliases for cwt config
* Add support for `type\_key\_filter` on subtypes for cwt config
# 0.5.4
* Add support for multiple rules with the same key for cwt config
# 0.5.3
* Add support for left hand side type values for cwt config (e.g. `<technology> = bool` for `tech_something = yes`)
# 0.5.2
* Add support for left hand side values for cwt config (e.g. `int = { }` for random_list `1 = { }`)
# 0.5.1
* Update config files
* Add support for .cwtools folder with config files in it
# 0.5.0
* Add support for new config file format, see https://github.com/tboby/cwtools/wiki/.cwt-config-file-guidance
* Check correct ordering of if/else/else_if
# 0.4.28
* Support opening a folder containing `.mod` files (that isn't the mod folder)
* Remove errors from list when a file is deleted
# 0.4.27
* Add nested if/else effect deprecation warning
* Add temporary if/else effect ambiguity warning
# 0.4.26
* Update to 2.1.0
* Add solar\_system\_initializer star class check
* Add anomaly migration warning
* Update validation to new anomaly format
# 0.4.25
* Add experimental completion
# 0.4.24
* Reduce memory usage
* Support syntax highlighting
* Fix vanilla syntax errors
# 0.4.23
* Add info for "REPLACE_ME" localisation
* Add localisation checks for starbase\_buildings, starbase\_modules, starbase\_types and special\_projects
# 0.4.22
* Sort generate localisation by order in file
* Override trigger\_docs and show error for pop/tile use of set\_variable and similar
# 0.4.21
* Update to stellaris 2.0.4
# 0.4.20
* Improved icon validators
* Ensure a final validation happens after changes stop
# 0.4.19
* Handle mod overwriting of vanilla files
* Add localisation tooltips
* Promote ship design validation from experimental
* Add mesh validation (experimental)
* Add graphical entity validation (experimental)
* Add ship\_size/component/section graphical entity validation (experimental)
# 0.4.18
* Add temporary error for 2.0.2 bug with after
* Add validation of ship designs, check that section slot type and component type match (behind experimental flag)
* Warn if tech has no effect (and has weight > 0)
* Fix .yml parsing bug
# 0.4.14
* Add validation of $refs$ in localisation
* Add validation of [commands] in localisation
* Add a command to create a .csv of all errors
    To use, press ctrl-shift-p, then "write all errors"
# 0.4.13
* Revert a change to localisation parsing
# 0.4.12
* Update to stellaris 2.0.2
* Check for ambiguous use of NOT operators
# 0.4.11
* Add localisation checking for opinion modifiers
* Fix localisation checking for war goals
* Check modifiers for opinion modifiers
# 0.4.10
* Significant performance improvements
* Display syntax errors immediately while validation is ongoing
# 0.4.9
* Add yes/no to autocomplete
* Add weights checking for
    * Event options
    * Agendas
    * Anomalies
    * Ascension perks
    * Bombardment stances
    * Buildings
    * Component templates
    * Country Customization
    * Country types
    * Deposits
    * Edicts
    * Ethics
    * Governments
    * Megastructures
    * Observatation station missions
    * Personalities
    * Planet modifiers
    * Policies
    * Pop faction types
    * Section templates
    * Species rights
    * Starbase buildings
    * Starbase modules
    * Starbase types
    * Technologies
    * Terraform
    * Tile blocks
    * Traditions
    * War goals
# 0.4.8
* Add localisation checking for war goals
* Add localisation checking for custom\_tooltip everywhere
# 0.4.7
* Correctly validate effects/triggers inside if, while and event_targets
# 0.4.6
* Fix bug with event\_target check when you reference an event that doesn't exist
# 0.4.5
* Improve event\_target checking to handle loops (still behind experimental setting)
# 0.4.4
* Add file "ignore" list to filter filenames that won't return validation errors
* Stop validation "random_names" as it's so non-standard
# 0.4.3
* Improve responsiveness of validation when make rapid changes (by only checking the latest version of a file not every changed version)
* Add scripted_effect event_target checking (still behind experimental setting)
# 0.4.2
* Add (experimental) event_target checking (hidden behind experimental flag)
* Add tooltip info for scripted_effects/triggers (taken from comments above definition)
# 0.4.1
* Add (experimental) modifier existence and scope checking for:
    * Buildings
    * Agendas
    * Ascension perks
    * Component templates
    * Edicts
    * Ethics
    * Governments
    * Policies
    * Ship sizes
    * Species rights
    * Starbase buildings
    * Starbase modules
    * Strategic resources
    * Technologies
    * Tradition categories
    * Traditions
    * Traits
# 0.4.0
* Add OSX support
* Update embedded interface to 2.0
* Significantly improve performance for large mods
* Add effect and trigger validation for:
    * Anomalies
    * Armies
    * Ascension perks
    * Bombardment stances
    * Buildable pops
    * Buildings
    * Bypasses
    * Casus belli
    * Diplomatic actions
    * Edicts
    * Ethics
    * Mandates
    * Megastructures
    * Observation stations
    * Personalities
    * Policies
    * Pop faction types
    * Ship sizes
    * Solar system initializers
    * Species rights
    * Starbase buildings
    * Starbase modules
    * Starbase types
    * Start screen messages
    * Subjects
    * System types
    * Technology
    * Terraform
    * Tradition categories
    * Traditions
    * Traits
    * War goals
# 0.3.3
* Fix bug with scope usage through prev
* Add simple scope commands to autocomplete
* Properly parse hsv/rgb with 4 values
# 0.3.2
* Check scope usage through "AND", "OR", etc
* Properly parse files with only values
* Properly parse "rgb"
* Give better feedback for parser errors when there is no matched brace
# 0.3.1
* Update localisation to 2.0
# 0.3.0
* Add simple autocomplete (triggers, effects, and modifiers)
* Add documentation for autocomplete (usage information and supported scopes)
* Add action to generate .yml for missing localisation keys
* Ignore missing keys that are just scripted loc (e.g. "[GetName]")
* Check correct scope of static modifiers use in has_modifier and remove_modifier
# 0.2.19
* Support scripted_variables
* Fix bug with checking variables in nested blocks
* Check correct scope of static modifiers use in add_modifier effects
# 0.2.18
* Add Stellaris 2.0 scopes
* Set 2.0 trigger_docs as default
# 0.2.17
* Check effectFile and textureFile against actual files, throw an error if the file isn't found
# 0.2.16
* Add "cwtools.errors.ignore" setting to allow ignoring of specific error codes
* Handle "hidden" prefix on scopes
# 0.2.15
* Update scope checking to support PREV and check inside scopes
* Check effects and triggers in more parts of events (options, desc triggers)
# 0.2.14
* Add experimental option to enable experimental features
* Added 2.0 effects/triggers behind experimental flag
# 0.2.13
* Check button_effects used in .gui files are defined
* Check spriteTypes used in .gui files are defined
# 0.2.12
* Fix ambient_object localisation checks
* Support recursive triggers and effects
# 0.2.10
* Add localisation_synced checking in events
# 0.2.9
* Add localisation for pop\_faction\_types
    * pft
    * pft plus "_desc"
* Add localisation for static_modifiers
    * modifier
    * modifier plus "_desc"
* Add localisation for spaceport modules
    * "sm_" plus module
* Add localisation for traits
    * trait
    * trait plus "_desc"
* Add localisation for governments
    * government key
    * ruler\_title, ruler\_title\_female, heir\_title, heir\_title\_female
    * civic
    * civic plus "_desc"
    * civic description
* Add localisation for personalities
    * "personality_" plus personality
    * peronality plus "_desc"
* Add localisation for ethics
    * ethics
    * ethics plus "_desc"
* Add localisation for planet_classes
    * planet class
    * planet class plus "_desc"
    * if colonizable
        * planet class plus "_tile"
        * planet class plus "\_tile\_desc"
        * "trait\_" plus planet class plus "\_preference"
        * preference plus "_desc"
        * planet class plus "_habitability"
* Add localisation for edicts
    * "edict\_" plus edict name
    * "edict\_" plus edict name plus "\_desc"
* Add localisation for policies
    * "policy\_" plus policy
    * "policy\_" plus policy plus "\_desc"
    * policy option name
    * policy option name plus "\_desc"
    * policy option flags
* Add more localisation for technology
    * feature_flags
    * feature\_flags + "\_desc"
* Add localisation for section_templates
    * key
* Add localisation for species\_name
    * "\_desc"; "\_plural"; "\_insult\_01"; "\_insult\_plural\_01"; "\_compliment\_01";"\_compliment\_plural\_01";"\_spawn";"\_spawn\_plural";
                                "\_sound\_01";"\_sound\_02";"\_sound\_03";"\_sound\_04";"\_sound\_05";"\_organ";"\_mouth"
* Add localisation for strategic_resources
    * resource
    * resource + "\_desc"

# 0.2.8
* Temporarily remove research leader checks
# 0.2.7
* Add localisation for armies and army_attachments
    * army name
    * army name plus "_plural"
    * army name plus "_desc"
    * attachtment is the same three but starting "army_"
* Add localisation for aura in component_templates
* Add localisation for diplo phrases
* Check technology "research_leader"'s "has\_trait" matches the technology category
* Add localisation for ship_sizes
* Add localisation for pop\_faction\_types
* Add localisation for technology gateway
* Add localisation for species_rights
    * right name
    * right name plus "_tooltip"
    * right name plus "\_tooltip\_delayed"
* Add localisation for map setup_secnarios
* Add localisation for megastructurew
    * megastructure name
    * megastrcture name plus "_DESC"
    * megastructure name plus "\_MEGASTRUCTURE\_DETAILS"
    * megastructure name plsu "\_CONSTRUCTION\_INFO\_DELAYED"
# 0.2.6
* Add more validation for technologies
    * All "research_leader" must have an area, which should match the technology
# 0.2.5
* Add localisation checks for buildings
    * building name
    * build name plus "_desc"
    * all "fail_text" under buildings
* Add localisation checks for component_templates
    * key
* Add localisation checks for traditions
    * use tradition_categories to determine traditions
    * tradition name for all
    * tradition_desc for start + traditions
    * tradition_delayed for traditions
    * tradition_effect for start and finish

# 0.2.4
* Add localisation checks for technology
    * technology name
    * technology name plus "_desc"
    * all "title" and "desc" keys under "prereqfor_desc"
* Add localisation checks for component_sets
    * component\_set's "key", but only is "required\_component\_set" is false