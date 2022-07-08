---
id: 4kaa0j0a3t02zjvgtd476nd
title: '0.101'
desc: ''
updated: 1656501483390
created: 1656411101601
---

Dendron 0.101 has sprouted  🌱

June 28, 2022

Last week, we launched on [product hunt](https://www.producthunt.com/posts/dendron-v100) and asked folks leave feedback. Thanks to the community, Dendron ended as the 5th most upvoted product of the day. Thank you everyone for your support 🙇‍♂️

**Depth Filter for Local Graphs:** Want to see the bigger picture? The graph depth filter now lets you control how much context you see in the [[Graph Panel|dendron://dendron.dendron-site/dendron.topic.sidebar.graph-panel]]
- More Information: 
    - [[Other Filters|dendron://dendron.dendron-site/dendron.topic.graph-view#other-filters]]
    - [[Graph Depth|dendron://dendron.dendron-site/dendron._ref.web-ui#graph-depth]]

**Improved Note Traits:** Rust isn't the only language with traits! We've made a bunch of improvements to traits, including hot reloading, the ability to apply a template, bundling libraries like lodash and luxon, as well as better docs and error handling. 
- More Information: [[Traits|dendron://dendron.dendron-site/dendron.topic.traits]]

## Highlights
- feat(views): view more note links in local graph panel with depth customization

- enhance(structure): improved note traits

## Everything Else
- enhance(workspace): `Vault Add` command warns for unsupported transitive dependencies
- enhance(workspace): vaults always use UNIX style separators in config files
- enhance(workspace): validate dendronrc.yml and emit error if invalid
- enhance(edit): add match helper for hb templates
- enhance(workspace): improve phrasing of sync message
- enhance(workspace): support single-vault workspace vaults for self contained vault migration 
- enhance(edit): reduce lag on autocomplete by adding a debounce
- enhance(sync): adding import hint to tutorial
- fix(workspace): try to patch `EPERM` issues for windows
- fix(workspace): adding an existing remote vault avoids creating workspace files 
- fix(publish): issue publishing note with ref without a code-worksapce file
- fix(cli): dendron publish --help to display full list of arguments 
- fix(workspace): error when native workspaces are initializing
- fix(publish): compile error with no banner present
- fix(structure): hot reload in note traits + no template by default

## Community

### TIL Highlights

> These are highlights from the [[Dendron Discord|dendron://dendron.dendron-site/community.discord.channels]] `#today-i-learned` channel.

- 💡 `icanteven#0264` shared a link to the additional benefits around GitLab land. [Link to Message](https://discordapp.com/channels/717965437182410783/904891933284007966/988905979695472640).

### Dendron Reading Series

This week's entry in the [[Dendron Reading Series|dendron://dendron.dendron-site/community.events.reading-series]]

[[My awakening moment about how smartphones fragment our attention span|dendron://dendron.dendron-site/community.events.reading-series.2022.06.28]]

### Event Reminders

- **Greenhouse Talks:** Visit the [[Greenhouse Talks|dendron://dendron.dendron-site/community.events.greenhouse]] for notes from previous sessions.
    - Next: [Fri, Jul 30, 04:00 PM PST / 00:00 UTC](https://link.dendron.so/luma)
    - [Greenhouse Talk Recordings - YouTube Playlist](https://link.dendron.so/greenhouse)
- **Office Hours:** Visit the [[Office Hours page|dendron://dendron.dendron-site/community.events.office-hours]] for notes from previous sessions.
    - Next: [Wed, Jul 06, 09:00 AM PST / 17:00 UTC](https://link.dendron.so/luma)
    - [Office Hour Recordings - YouTube Playlist](https://link.dendron.so/6yPa)
- **Community Teatime:** Drink tea, eat food, and hangout with the Dendron crew!
    - Next: [Thu, Jul 07, 11:00 AM PST / 19:00 UTC](https://link.dendron.so/luma)
- **New User Tuesdays:** Visit the [[New User Tuesdays page|dendron://dendron.dendron-site/community.events.new-user-tuesdays]] for notes from previous sessions.
    - Next: [Tue, Jul 12, 8:30 AM PST / 16:30 UTC](https://link.dendron.so/luma)

### Thank You's

A big **thanks** to the following gardeners that brought up issues, contributions, and fixes to this release :man_farmer: :woman_farmer: 
Visit [[Discord Roles|dendron://dendron.dendron-site/community.discord.roles]] for more information.

- [Arne Vanheesbeke](https://github.com/avhb) `@avhb#0567`
    - [improve phrasing of sync message](https://github.com/dendronhq/dendron/pull/3115)
    - #role.horticulturalist

- [Derek Ardolf](https://github.com/ScriptAutomate) `@icanteven#0264`
    - [Self Contained Vaults throw initialization errors with latest Dendron version, but still function](https://github.com/dendronhq/dendron/issues/3122)

- [Ryan Hill](https://github.com/rlh1994) `@rlh1994#9754`
    - [Align cli to template](https://github.com/dendronhq/dendron-site/pull/551)
    - [Need to reload VScode to have new backlinks show in preview](https://github.com/dendronhq/dendron/issues/3143)

- [Aaron Meese](https://github.com/ajmeese7) `@ajmeese7#4835`
    - [Update dendron.topic.publish.config.siteHierarchies.md](https://github.com/dendronhq/dendron-site/pull/552)
    - [Added a space between words](https://github.com/dendronhq/dendron-site/pull/554/)
  
- [cquick01](https://github.com/cquick01)
    - [Nested unordered bullets aren't rendering properly in preview](https://github.com/dendronhq/dendron/issues/3139)
    - #role.bugcatcher
  
- [Funnym0nk3y](https://github.com/funnym0nk3y) `@funnym0nk3y#2324`
    - [Autosuggestion of notes fails](https://github.com/dendronhq/dendron/issues/3144)

- [Adam Gluck](https://github.com/aglucky) `@glucinater21#0869`
    - [Root backlink not working](https://github.com/dendronhq/dendron/issues/3156)
    
## Changelog
![[changelog#01010,1:#01000]]
