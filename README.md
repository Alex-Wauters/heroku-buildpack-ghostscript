# Heroku Buildpack for Ghostscript (full version)

Currently installs Ghostscript 9.53.3 on Heroku Cedar. This buildpack takes the binary available at https://www.ghostscript.com/download/gsdnld.html

To update, fork this buildpack and retrieve the version from the list on https://github.com/ArtifexSoftware/ghostpdl-downloads/tags

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/Alex-Wauters/heroku-buildpack-ghostscript.git

    # Push changes to deploy
    $ git push
