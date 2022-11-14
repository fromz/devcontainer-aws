# Installation
Add the following to your .devcontainer/devcontainer.json 
```json
   "features": {
        "https://github.com/fromz/devcontainer-aws/blob/master/devcontainer-feature-aws.tgz?raw=true": {
            "version": "latest"
        }
    }
```
# TODO:
- Publish the tarball to an OCI registry as an artefact to allow versioning etc