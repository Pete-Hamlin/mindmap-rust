# mindmap-rust

Collecting all your tagged knowledgebase in one convenient place.

## Justification - Why does this exist?

Many tools provide ways of storing knowledge of various different formats in very similar way. Most notably to me, most of my knowledge stores support tagging data a a loose relational system. Notable examples of these are:
- **Browser bookmarks** - firefox bookmarks
- **Online link storage/backup** - linkace
- **Read it late lists** - Pocket, wallabag
- **Various note taking apps** - Zettlr, Joplin, vscode foam (Markdown w/frontmatter)
- **TODO lists** - todo.txt (various), taskwarrior
- **Media libraries** - Jellfin, kodi, calibre

All of these provide similar formats for categorising this data, but does not reconcile it to one central reference point (i.e data is still siloed). For me, this creates the following reasons to create this software:
- In order to similate a "second brain" principle, it would be great to be able to search all of a curated list of services by keyword or tag (i.e searching `rust` will bring back results from everything related to rust)
- Provide an extendable/pluggable interface to attach these data sources
- Cache results of API queries/result indexing to provide quicker search results (and not hammer APIs so aggressively)
- Provide a useful and attractive way to present all related data to a given search back to the user
- I have also had a burning desire to try and write something in rust for some time, and this is a great opportunity to do so.