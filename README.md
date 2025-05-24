March 22nd, 2025 / Release Version v.0.6.6
	
	FOMOD
	- added 54 "Minimalist Companion UI 1.3"
	- 51-52 "Dynamic Dialog UI" no more optional
	
	CORE
	- moved files to relative modules and removed unused files
	
	MAIN MENU
	- 12 added "ui_actor_main_menu_options.xml" \ui\textures_descr to update options buttons
	
	INVENTORY
	- 23 removed "ui_actor_menu_factions.dds" and moved faction textures to "ui_actor_menu.dds"
	- 24 updated "textures_descr\ui_actor_menu.xml"
	- 25 updated "ui_actor_menu.dds"
	- 26 updated "textures_descr\ui_actor_menu.xml"
	- 29 updated "ui_actor_menu.dds"
	- 
	- HUD
	- 53 updated "maingame.xml" "maingame_16.xml" files and removed Faction HUD versions to increase compability
	- 53 updated pos "ui_hud.xml"
	- 55 "Alticons" removed "ui_hud.xml" file to increase compability, updated "alticons.script" pos to x-0 y-0 self.dialog:SetWndPos( vector2():set(pos.x - 60, pos.y - 8)) and size_adjust = 1.00
	
	FACTION HUD
	- 61 removed eGUI HUD module and updated main module files with it

March 14th, 2025 / Release Version v.0.6.5

	CORE
	- 01 removed "new_game" folder and it's content
	- 01 updated "ui_hud_hit_mark.dds" "ui_hud_hit_mark.thm"
	- 01 updated all "ui_actor_hint_wnd.dds"
	
	MAIN MENU
	- 12 removed "ui_options_sliders.dds"
	- 11 main menu themes suggested by @folk
	- "track_3.ogg" replaced with Metro 2033 Intro
	- "track_13.ogg" Metro Last Light - Main Theme 
	- "track_14.ogg" Metro 2033 - Good Ending
	- "track_15.ogg" Metro Last Light - Reminiscence Intro
	- Localization EN RU "ui_st_options.xml" added ui_mm_originals and ui_mm_disclaimer
	- Main Menu and MCM "ui_mm_main.xml" "ui_mm_main_16.xml" added ui_mm_originals and static_disclaimer 
	
	INVENTORY
	- 21 New sorting tabs removed "ui_actor_menu_new_tabs.dds"
	- 23 removed "ui_actor_menu_new_tabs.dds"
	
	HUD
	- 53 HUD added "ui_light_gem.xml" file for Stealth Overhaul position and removed "textures\ui\lightgem" folder and it's content
	
	PATCHES AND FIXES
	- added RU version "ui_new_game_popup"
	- 92 bypass patch for bvcx's "BHS Rework" addon
	- 93 patch for "BHS Redux EFP style"
	- ultrawide patch added "maingame_pda_msg" "maingame_pda_msg_16" pda text position fix by @𝐋𝐚𝐳𝐲𝐑𝐞𝐝𝐂𝐚𝐭

Jul 22nd, 2024 / Release Version v.0.6.4

	INVENTORY
	- added "Skinnin With Space" by Nitpicker
	- updated "ui_workshop.script" for "Hideout Furniture" crash
	
	HUD
	- "Quest Arrow" disabled "modxml_AL_MapSpots.script" "modxml_AL_StashMarkers.script"

June 4th, 2024 / Release Version v.0.6.3

	CORE
	- new module "MCM" EGUI mod conf menu
	- various text fixes
	- updated all "ui_actor_hint_wnd.dds" for module seperations
	- added to "Portraits" "Unlocked Portraits by VodkaChicken"
	
	MAIN MENU
	- updated all "ui_mm_main" files
	- 11 "Dynamic Backgrounds" added "Metro Exodus - Race Against Fate" soundtrack for mm and fixed missing track_11 from the script
	- 11 "Dynamic Backgrounds" updated few background images
	- 11 re-compressed "enhancedgui_12.dds"  file causing crash in dx10
	- updated credits
	- 12 disabled "ui_options.script" to prevent patches
	
	INVENTORY
	- module 21 "Immersive Sleep" is now optional
	- removed module 22 "Workshop" and renamed module "Details Screen" to "Workshop"
	- 22 "Workshop" added S2 style "Mutant Loot, Cooking, Workshop" based on "UI Rework by @Sota"
	
	HUD
	- rescaled debug mode icon
	- 52 "Compass" removed inner circle and dots
	- 52 "Ammo and Companion Wheel" added vanilla cfg files for "ui_wheel_ammo" "ui_wheel_companion"
	- 52 "Quest Arrow" added bypass patches for "ReworkedStashQuestMapMarkers" "QuestArrow" no longer require modded exes to work
	- 53 "HUD" "ui_hud.xml" reverted original companion list
	- 53 "HUD" disabled "actor_effects.script" to increase compability. autohide stamina on
	- disabled module 52, moved 54 "MinimalistCompanion"
	
	PATCHES AND FIXES
	- updated MCM banner pos
	- 71 "Localization RU" texts fixes by @дедушка Ли
	- 71 "Localization SPA" patch by vdltman
	- "WarfareALifeOverhaul" patch
	- 81 cfg "ui_options_16.xml" to GAMMA patch for button alignment
	- patch "GAMMA Artefacts Reinvention"
	- "Desolation" Patch by @Wawwior and @sooper + WarfareALifeOverhaul Patch can be found inside
	- "Anthology" patch
	- "local enable_contact_offline = true to false"
	
	INCLUDED ADDONS
	- included "Parts In Tooltip" by TheMrDemonized

Nov 20th, 2023 / Hotfix v.0.6.2
	
	- module 21 "New Sorting Tabs" disabled "m_bolt.ltx" to prevent problems with bolt animations
	- removed patch module "GAMMA Damien's Bolt Fix" fixed bolt overwrite

Nov 19th, 2023 / Release Version V.0.6.1 HOTFIX
	
	CORE
	- core updated "ui_hud.dds"  texture throw speed texture to white color
	- new module "Localization"
	
	MAIN MENU
	- module 12 added "ui_st_mm.xml" "ui_st_options.xml" russian texts by @дедушка Ли and moved all text folder to new ""Localization"
	- updated credits screen
	
	INVENTORY
	- module 25 added "hts_inventory_bars.script" from  "Hunger Thirst Sleep UI by xcvb" to prevent broken bars.
	- new patch module 80 "Supply level" or "Faction Based Economy" patch for gamma, "inventory.script" used from "GAMMA" without problems
	
	HUD
	- disabled module 51 "Body Dots on Minimap"
	- module 53 "HUD" added "map_spots_campfires.xml" for "Campfires on Map" and removed patch module "Display Campfires on Map" not required
	- new module 90 "GAMMA Damien's Bolt Fix" patch for "New Sorting Tabs"
	- [DISABLED] new module "GAMMA Ishmaeel's Kill Tracker"
	- readded "Body Health System" ammo counter
	- updated module 52 "Quest Arrow" removed "map_spots_relations.xml" "PAW and Ishmaeel's Kill Tracker"patches not required anymore.
	
	21:9 UPDATES
	- updated module 91 "NPC Counter and Sound" counter text pos fix  21:9  by @Hunlight
	- updated module 91 added "alticons.script" fix for 21:9 pos by @Hunlight
	
	- included "Faction Identification UI"  by CrookR

Nov 15th, 2023 / Release Version v.0.6
	
	CORE
	- fixed corrupt "ui_con_checker_interface.dds" file causing the crash while interacting with recipes in dx10 and changed with stalker 2 style
	- added texts to "ui_new_game_popup.dds" "isg, sin and zombified"
	- "ui_con_checker_interface.dds" S2 style crafting notes
	- "prop_agit.dds" "wm_pl_1.dds" "wm_pl_3.dds" new posters
	- "ui_actor_menu_factions.dds" reworked stash icon
	- updated "ui_actor_menu.dds"
	- added s2 style "ui_loot_interface.dds" by @Hunlight
	- removed "item_merger.dds"
	
	MAIN MENU
	- added addon banners to mcm
	- removed optional intro disabler patch
	- "ui_options.xml" st_tree height="25" to "27"
	- updated keybind hover "ui_common.dds" for clean visibility
	- lowered main menu music volume
	- fixed the issue where mcm button is missing for 21:9
	- corrected toggle placement for "Jabbers Soulslike"
	- module 12 "ui_st_screen.xml" added text "LOST TO THE ZONE" and updated various texts
	- module 13 "en\ru ui_st_credits.xml" "ui_credits_base.xml" updated names
	
	INVENTORY
	- Inventory modules are no longer optional
	- small improvements for inventory
	- added "Immersive Sleep" "actor_status_sleep.script" patch to htsui for missing bar. moved original script to resc
	- added "FFDA patch" for "Immersive Sleep"
	- added optional simplified status bars
	- added "GAMMA Sleep Balance"
	- *module 22 "Details Screen" added missing melter icon texture_descr "G.A.M.M.A. Artefacts Reinvention" to "ui_item.xml"
	- module 25 updated "ui_actor_menu.dds"
	HUD
	- NPC Counter is now disabled by default, and added as optional.
	- moved "ab_move_notification.script" to pda module
	- moved "ui_actor_hint_wnd.dds" to hud folder, vanilla version exists in core
	- updated "ui_hud.xml" artifact belt and status icon positions in hud
	- improved compass visibility
	- updated hud text positions
	- added 7 optional faction themed hud
	- added quest marker for compass
	- added compability for "alticons" with "HUD icons time"
	- module 52 moved "Reworked Ammo Wheel" scripts to resc
	- module 53 added monkey patch "zzz_player_injuries_disabled.script" to disable "Body Health System" addon by @strangerism
	- module 53 added new Hit Direction Marker "ui_hud_hit_mark.dds" by @semfeliks
	- module 91 "Body Health System" "maingame.xml" "maingame_16.xml" changed ammo counter with EGUI, added monkey patch - "zzz_player_injuries_disabled.script" to enable addon
	- new patch 91 "BHS Realistic Overhaul"
	- new patch 91 "Display Campfires on Map" added #include "ui\map_spots_campfires.xml" to "map_spots.xml" "map_spots_16.xml" for "Display - - Campfires on Map" compability over "Quest Marker"
	- new patch 91 "PAW - Personal Adjustable Waypoint"
	
	INCLUDED ADDONS
	- included "Dynamic Dialog" by TheMrDemonized
	- included  "Better stats bar" by TheMrDemonized
	- included "New Mutant part and meat" by TDLemon
	- included "Alternative icons" by Strogglet15
	- included "Body dots on minimap" by RavenAscendant
	- included "HUD icons time"  by bvcx
	- included "Immersive Sleep" by tkcrits
	- included "New sorting tabs" by Bartoche70
	
	PATCHES AND FIXES
	- removed module 71 "DX8 Patch" and changed module 11 wallpapers with DX8 images
	- new module 89 "GAMMA Keybinds fixes" added "BetterStatsBars" patch
	- updated module 91 "Ultrawide [21x9]"
	- removed module 92  "PATCH - GAMMA"


Jul 17th, 2023 / Release v.0.3
		
	- compass core code is updated and not requires any addon.
	- compass  "contact sound" is separated, high-pitch noise will work when there's contact and the low-pitch will work when the contact is - - lost. - - local enable_contact_sound = true  changed from false to true
	- Added option to disable npc counter text and sound.
	- added presets for settings and mcm.
	- created vanilla version of Inventory.
	- added faction and rank overlays patch
	- added hunger thirst sleep ui patches versions 0.71 - 1.01
	- better stats bars companilibity patches added  for htsui 0.71
	- added hunger thirst sleep UI 0.61 patch
	- added new sorting tabs + htsui patch.
	- Jul 24th, 2023 / Release version v.0.4
		
	- hud status icons are fixed and hud components now optional.
	- re-added presets to the settings, updated credits.
	- added dx8 patch for main menu backgrounds.
	- rank icons, stash icons fixed.
	- added patch for "Arszis Radiation Overhaul" "Immersive Sleep" "GAMMA modpack"
	- Aug 5th, 2023 / Release version v.0.5 [DLTX]
		
	- updated dynamic backgrounds to DLTX, backgrounds and music will change more frequently and no more system.ltx related problems.
	- gamma patch is now cover all the files inside for easier installation.
	- added mcm logo for mcm users in mainmenu and mcm.
	- "knife pistol binoc slot" included, thanks to RavenAscendant for giving permission.
	- removed "ui_main_menu.script" and added "modxml_credit_button_patcher_mcm.script" for better MCM compability.

Jul 7th, 2023 / Mod files deleted until next release.

Jul 5th, 2023 / Release version v.0.2 + FOMOD installer.
		
	- healthbBar is fixed. updated file texture_descr\ui_actor_menu.xml
	- added 21:9 Inventory patch by Aster
	- russian version credits now updated and fixed texts in Faction select screen.
	- to prevent crashes added patches for Hunger Thirst Sleep and Bolt.

Jul 1st, 2023 / First release, version [ALPHA]. 
Jun 17th, 2023 / Deleted old files. preparing mod for Alpha release.
Jun 11th, 2022 / First release of the project.
