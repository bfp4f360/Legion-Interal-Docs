---
id: overview
title: Overview of the site
---

So you are probably wondering, "How the hell does this all work?". Well to show how it works take a peep at [this](https://github.com/bfp4f360/swls-test-internal-doc) repo, its the repo for this site!

Under the `\docs` folder is where all the docs are, *wowe so special*. For example this file is under `\docs\Overview.md`. Just adding it to the folder makes it accessable via link, for example you can get to [this](hiddenDoc) doc, but it doesnt show up on the sidebar. So how can we add that? Well easy! Head over to `sidebars.js` in root and add the `id` field to the array.

This site also auto deploys whenever you commit! You can change how that works too!.