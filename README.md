## What?

This is a Node-Red image with the passport-openidconnect NPM package added to it.

## How

The GitHub repository is monitored by renovate for updates to the Node-RED image. If there is a new version, renovate automatically raise a Pull Request (PR) in the repo. The GitHub Action will try to build the image from Dockerfile. If this is successful, the PR will get automatically merged which means the change will get incorporated into the repo.

Any change to file in the main branch related to the build process will cause GitHub Action to build the image and push it to the repository.
