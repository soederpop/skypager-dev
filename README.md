# Skypager Dev Folder

The skypager framework's build tooling uses skypager itself.

The current version still uses build scripts from an earlier branch, so this project
exists to provide those dependencies through the node_module/ parent folder resolution
mechanism, and allows me to remove the link via devDependencies since the plan is to update
the build tooling to remove this discrepancy.

Mainly the difference is that we're not as up to date with webpack and babel's latest versions as we'd like to be.

