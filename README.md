# PresenceHub-Plugins

This repository hosts plugin packages for PresenceHub.

The main app downloads `plugin-index.json`, reads the available plugins, and fetches each plugin package from its release path.

## Structure

- `plugin-index.json`  
  The public list of available plugins

- `plugins/`  
  Plugin package folders

Each plugin should have its own folder and versioned package layout.

## Example

plugins/
└── youtube/
    └── 1.0.0/
        ├── manifest.json
        ├── plugin.apk
        ├── checksum.sha256
        └── signature.sig
