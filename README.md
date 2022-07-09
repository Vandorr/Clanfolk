# Translation repository for Clanfolk
Commit translations for Clanfolk into this repository to have include them to the game!


# Current languages in the game
 * English: Main version by Blorf 
 * French: Translated by official
 * German: Translated by official
 * Simplified/Traditional Chinese: Translated by official
 * Italian: Translated by official
 * Spanish - Spain: Translated by official
 * Japanese: Translated by official
 * Korean: Translated by official
 * Polish: Translated by official
 * Portuguese Brazil: Translated by official
 * Russian: Translated by official 
 * Czech: 
 * Romanian: Dl.Vulpe
 * Turkish: Deimos
 * Hungarian: Estilla, Vandorr


# About Clanfolk
 * Discord: https://discord.gg/JSWxF6YShm
 * Official website: https://minmax-games.com/Clanfolk/
 * Steam: https://store.steampowered.com/app/1700870/Clanfolk/


# How to
* In order to gain access to this repo, please visit us Discord (https://discord.gg/JSWxF6YShm and contact vandorr#0626).

# Tips

V 0.101 Beta Only: 
This version only contains an upgrade to the localization system.  There has been a lot of community interest in localization recently, and I needed to upgrade the system to make the Localization of the new Demo more streamlined.  So here we go, new features for those who are interested:
- The entries section of the localization file now contains the key for quick reference [Key]>"Entry Text"
- This should make deciphering the context of the translation quicker without having to look it up in the keys table.
- When a new entry has been Added, it will look like this [Key]>[New]>"Entry Text"
- When it has changed [Key]>[New]>"Entry Text New"[OLD]>"Entry Text"
- Note, the old entry text will be used until it has been translated to the new text.
- When updating the language file, searching for [NEW]> Will find you all the additions and changes.
- When translating an entry, remove the [NEW]> text and just leave the [key]>"Entry Text".
- Each time I make changes, your translation files will be updated with those changes and the entries will be marked with [New]> automatically
- Many new blank entries for descriptions have been added for the cases where English does not need a description, but it may be helpful in your language.  It is fine to leave these blank if not needed
- Afflictions and Quirks now respect Male/Female translations.  So for example if Lazy had two different words in your language translate it like this [Lazy]>Male Lazy[MF]Female Lazy
- This also works for descriptions
- Some entries that are no longer valid or that are not valid in the current build are now moved to the end of the file and marked with [REM]>  No need to translate these.  Best not to delete them though as they may be removed in the Demo version but added in the Full Version.
- There are 2 new lists called refDoNotChangeKeys, and refDoNotChangeEntries.  These are used to allow the localization code to figure out what changes to mark as [New]> so please don't edit these.  All edits should happen in "entries"
- All the indexes are now the same across all languages.
Important note: The translation CHANGE detector will only work on the next version.  This version it is saving a base copy of the English translation to compare against, but going forward it will mark changes with [NEW]> as it should.
Also: Please back up your translation files just in case as I tested this a bunch but it is a really complex system and it does overwrite your file each time it updates.
TLDR: Just look for [New]> now.  The file is magic 


Thank you for contributing translation! :)

 Blorf & Vandorr
