# the-gammons.net
This is my personal Family History website.

It was created by using [HTTrack Website Copier](https://www.httrack.com/) to clone my old website (originally created with Netobjects Fusion). The website has now been converted to [Jekyll](https://jekyllrb.com/). It also uses the Jekyll blog functionality so that every major update can be announced in the "News" feed, and people can monitor that for updates.

The website source is now stored online in my [Github repository](https://github.com/RossGammon/the-gammons.net/). This allows other family members to contribute information & corrections directly. This can be done on the Github website, by editing the files online and creating a Pull Request, or by creating an Issue for me to fix.

Alternatively, contributions can be produced locally by cloning the git repository. See the INSTALL file for instructions.

I also include my Family Tree which is produced using the [Gramps](https://gramps-project.org/) Narrative Web Report. This can be found at [Ross's Family Tree](http://www.the-gammons.net/RossFamilyTree).

## To prepare and upload a new version of the website:
 * In Gramps use the NavWeb report to generate a new report in a known directory.
 * Copy the Navweb files to the RossFamilyTree tree directory of the git repository.
 * Commit the changes with $ git commit
 * Make whatever other changes you want to the Jekyll site and commit them.
 * Build the Jekyll site with $ jekyll build
 * If the changes were significant, check the website is working locally with $ jekyll serve
 * Run html-proofer locally to check links etc. (or wait for Travis to do it after you "push" in the next step).
 * Push the changes to Github with $ git push
 * Upload the contents of the _site directory to the website location using Filezilla or anothr FTP application.
