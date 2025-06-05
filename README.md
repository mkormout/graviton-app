# Graviton Github Pages Repo

Graviton game Github pages repository.

## Release

The files are being automatically updated after push to https://github.com/mkormout/graviton main branch.

After release index.html needs to be updated by adding:
```html
<script src="coi-serviceworker.min.js"></script>
```

It handles some missing stuff for Godot:
Cross Origin Isolation - send correct headers
SharedArrayBuffer - send correct headers
