# To make changes to your website
## First, get the website cloned to your local system
- Install an IDE like [Visual Studio Code](https://code.visualstudio.com/)
- Install the ["Live Server" extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) by Ritwick Dey (click the four boxes on the left sidebar in VS Code--it should be the 5th icon down--and search for it, then install). This will let you preview any changes you make to the site live.
- Sign up for an account on Github [here](https://github.com/signup), and let me know what email you used when you do. I'll add you as a contributor on the repository, which will let you submit changes to it.
- Then, snag yourself the [GitHub Desktop client](https://desktop.github.com/) and log in. 
- In GitHub Desktop, go to "File > Clone Repository" and select the URL option. The URL is `maximilianhart/LayCarmelitesFL.org`. Decide where you want to store it on your computer, then click "Clone." You now have a local copy of the website that's connected to the live repository here on GitHub!

## Making changes locally

### Every time you go to make changes, _**before you make any changes**, check to see if there are any changes that have been made on the remote branch (the one on GitHub). 
- To do this, click "Fetch origin" and if there are any changes, "Pull origin with rebase" so your local copy is synced up. If anything wonks out, get in touch.
- Now you're good to make any changes you'd like! 
- To make a new page, copy the `NEWPAGETEMPLATE.html` file, rename the new one, and make whatever changes you'd like under the `<!-- Content -->` tag. I'd recommend [this online HTML editor](https://html-online.com/editor/) to make your life easy.
- Save often! You can use the same Live Server extension to see your changes as you save them to the file.
- When you're done, edit whatever pages on the site that you want to have pointing to your new page.
- Once you're done, head back to GitHub desktop. You'll see on the left the files you've changed. 
- Write a quick summary (it's required) of what's changed, and then click "Commit to main." Now your changes have been saved to the local repository (it's different than just saving the files individually).

## Pushing your changes to the live website
When you're all done making changes locally and you're ready for them to go live to the site:
- Pull down from origin one more time just to be safe
- Resolve any conflicts (this will only happen if we're somehow both working on the site at the same time)
- Then, just click "Push origin" in Github Desktop. 

Wait a few minutes for the website to refresh, and you're all set! 

## Useful help pages:
- [Getting started with GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop)
- [Cloning and forking repositories from GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)
- [Pushing changes to GitHub from GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/pushing-changes-to-github-from-github-desktop)
