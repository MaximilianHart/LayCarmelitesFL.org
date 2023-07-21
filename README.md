## To see a preview version of the website

To view this website before it's live, you'll need an IDE like [Visual Studio Code](https://code.visualstudio.com/), and a way to preview the files. You can do this in VS Code using the ["Live Server" extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) by Ritwick Dey (click the four boxes on the left sidebar in VS Code--it should be the 5th icon down--and search for it, then install).

Then, to get the files down to your computer easily, just click the "<> Code" button above, download the ZIP file, extract it in a folder, and then open that folder in VS Code. Right click the `index.html` page, then "Open with Live Server." It should open locally in a browser and you'll be able to browse the website as if it was live on the Internet. Resize the page, and you'll see the website react responsively.

(Once the site is live, of course, you'll also be able to see it on https://LayCarmelitesFL.org.)

## To make changes to the website

Sign up for an account on Github [here](https://github.com/signup), and let me know what email you used when you do. I'll add you as a contributor on the repository, which will let you submit changes to it.

Then, snag yourself the [GitHub Desktop client](https://desktop.github.com/) and log in. Go to "File > Clone Repository" and select the URL option. The URL is `maximilianhart/LayCarmelitesFL.org`. Decide where you want to store it on your computer, then click "Clone." You now have a local copy of the website connected to the one on GitHub! (You can delete the ZIP downloaded one now.)

First, every time you go to make changes, ***before you make any changes***, check to see if there are any changes that have been made on the remote branch (the one on GitHub). Click "Fetch origin" and if there are any changes, "Pull origin with rebase" so your local copy is synced up. If anything wonks out, get in touch.

Now you're good to make any changes you'd like! There's a `NEWPAGETEMPLATE.html` file you can copy and write a new page in if you need one, then edit whatever page you want to have pointing to it. Save often, of course! You can use the same Live Server extension to see your changes as you save them to the file.

Once you're done, head back to GitHub desktop. You'll see on the left the files you've changed. Write a quick summary (it's required) of what's changed, and then click "Commit to main." Now your changes have been saved to the local repository (it's different than just saving the files individually).

When you're all done making changes locally and you're ready for them to go live to the site, Pull down from origin one more time just to be safe, resolve any conflicts (this will only happen if we're somehow both working on the site at the same time), and then just click "Push origin" in Github Desktop. 

Wait a few minutes for the website to refresh, and you're all done!

## Useful help pages:
- [Getting started with GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop)
- [Cloning and forking repositories from GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)
- [Pushing changes to GitHub from GitHub Desktop - GitHub Docs](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/pushing-changes-to-github-from-github-desktop)
