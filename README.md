PommelWiki is a fork of PmWiki focused on SEO friendliness and non-English content.

The project is named after Coco Pommel — a “My Little Pony: Friendship is Magic” character.

Its codebase is forked from PmWiki 2.2.139. Planned and made changes are consisting of:

- First stable release.
  - [X] UTF-8 character encoding is enabled by default.
  - [ ] Lowercase URLs with hyphens as separators are enabled by default.
  - [X] Responsive skin is the only option and enabled by default.
  - Unneeded scripts are either deleted or moved to the cookbook.
    - [X] guiedit.php - ugly, deleted.
    - [ ] wikiwords.php - doesn't work with UTF-8 properly, deleted.
    - [X] creole.php - conflicts with Markdown, deleted.
  - [ ] Documentation has been moved out of the wiki and doesn't come with the sites.
  - [ ] Markdown syntax has been added and has replaced the standard markup.
  - [X] Containerization using Dockerfile.
  - [X] Properly working wikilinks with dots. https://www.pmwiki.org/wiki/Cookbook/DotsInLinks

The original README text is below.

---

```
This is the README.txt file for PmWiki, a wiki-based system for
collaborative creation and maintenance of websites.

PmWiki is distributed with the following directories:

  docs/           Brief documentation, sample configuration scripts
  local/          Configuration scripts
  cookbook/       Recipes (add-ons) from the PmWiki Cookbook
  pub/skins/      Layout templates ("skins" for custom look and feel)
  pub/css/        Extra CSS stylesheet files
  pub/guiedit/    Files for the Edit Form's GUIEdit module
  scripts/        Scripts that are part of PmWiki
  wikilib.d/      Bundled wiki pages, including
                    * a default Home Page
                    * PmWiki documentation pages
                    * some Site-oriented pages

After PmWiki is installed the following directories may also exist:

  wiki.d/         Wiki pages
  uploads/        Uploaded files (page attachments)

For quick installation advice, see docs/INSTALL.txt.

For more extensive information about installing PmWiki, visit
  http://pmwiki.org/wiki/PmWiki/Installation

For information about running PmWiki in standalone mode without
requiring a webserver, visit
  http://pmwiki.org/wiki/Cookbook/Standalone

PmWiki is Copyright 2001-2006 Patrick R. Michaud
pmichaud@pobox.com
http://www.pmichaud.com/

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

The GNU General Public License is distributed with this program
(see docs/COPYING.txt) and it is also available online at
http://www.fsf.org/licensing/licenses/gpl.txt .
```
