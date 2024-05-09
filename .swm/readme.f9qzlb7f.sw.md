---
title: README
---
# onboard

## Local dev

# Create a new app

```bash
cd ..
npx @backstage/create-app
cd new-backstage-app

# Run the modded cli in the new app

../RELATIVE_PATH_TO_PROJECT/backstage/packages/cli/bin/backstage-cli onboard
? Do you want to set up Authentication for this project? (Y/n)
...

# Try the app with the new changes

yarn dev

```

<SwmMeta version="3.0.0"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
