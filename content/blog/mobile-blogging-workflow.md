+++
title = "Mobile Blogging Workflow"
date = "2020-03-16"
tags = "technical, howto"
cover = "img/mobile-workflow.png"
description = "I have finally found a mobile workflow for blogging."
+++

I have finally found a mobile workflow for blogging. I can now write posts on my phone when I have a few moments to spare. The workflow is simple.
1. Write an entry in the Textastic app
2. Open Working Copy and commit/push changes
3. Netlify detects change in Github repository and deploys new Hugo site

To setup this workflow:

- Create a site on your computer using a static site generator. I use Hugo.
- Create an empty repository in Github
- Push your local Hugo site environment to the empty Github repository. 
- Connect your Github account to Netlify. 
- Install Working Copy on your iPhone and pull your repository. 
- Enable Working Copy as an external folder in the iOS Files app. 
- Install Textastic and open the site repository located within the Working Copy external folder. 
- Any changes made within the site directory while in Textastic will update Working Copy. 
- Commit/Push your changes in Working Copy when ready. 
- Netlify will automatically update your website. 

I have been wanting to start a blog for a while now and this mobile workflow gave me the push I needed to officially begin. 