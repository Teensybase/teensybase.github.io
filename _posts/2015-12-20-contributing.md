---
layout: page
title: "Contributing"
category: teensybase
date: 2015-12-20 17:15:00
order: 2
---

###The right way

This involves running Teensybase on your local computer by running Jekyll. This allows for instantaneous viewing of all edits that you make before committing them to GitHub.

- Follow the instructions on the [Compile Teensybase]({{site.url}}/teensybase/compile) page to get a local instance of Teensybase running on your computer.
- To edit existing pages, edit the .md file for that page located in the /_posts directory of your local Teensybase instance.
- To create a new page, create an .md file in the /_posts directory that complies with the naming convention of *YYYY-MM-DD-pagename.md* and insert an appropriate front matter before your page content.

~~~~~
---
layout: page
title: "Example"
category: teensybase
date: 2015-12-20 17:00:00
order: 20
---

[page content here]
~~~~~
 
- Providing Jekyll is running, it will automatically pick up any changes and compile them, allowing you to refresh Teensybase in your browser to see the changes.
- Once you've finished, commit the changes back to your fork and then open a pull request against teensybase.github.io.

###The quick way to provide edits and spelling corrections

This allows you to purely use the GitHub web UI to edit pages.

- Navigate to the page you wish to edit and click the 'Edit' button in the top right corner.
- If this is your first edit, click the 'Fork this repository and propose changes' button.
- Edit the file and click 'Propose file change' when complete.
- Click 'Create pull request' to request the change to be applied against Teensybase.github.io.