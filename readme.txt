This gh-pages branch is used to publish documentation using http://pages.github.com/.

Since the documentation is large and generated, we're not really interested in storing diff's; that's why we only have a single commit on this branch. I achieve this by doing a "baseless commit"; see git-baseless-commit file.

Currently, my workflow is:

 1. run publish.bat to copy the build documentation
 2. do the baseless commit
 3. push (force overwrite)

This could be further automated, but for now it suffices.

