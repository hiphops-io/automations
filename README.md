# Automations

Shared automations for Hiphops

External automations are very welcome, just create a PR!

## About

Hiphops automations are re-usable bundles of code that can be imported and ran by Hiphops.

An automation requires:
- A valid `main.hops` file
- A `manifest.yaml`
- Any other file resources required to run the automation (e.g. `template.html` or `Dockerfile` etc)

They have the following structure:
```
/automation_name
 - main.hops
 - manifest.yaml
 - ... other files
```

An automation cannot contain directories. All files must appear in the root of the automation's directory.
