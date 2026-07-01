# Remote Catalog Host

Upload this whole folder to a static host.

The game should point `RemoteCatalogLoader > Catalog Url` to:

```text
https://your-host-url/catalog.json
```

Update flow:

1. In Unity, run `PhotoCard Collecting > Export Remote Catalog JSON`.
2. Copy `Assets/GameData/RemoteCatalogExport.json` over this folder's `catalog.json`.
3. Upload/redeploy this folder.
4. Open the hosted `catalog.json` URL in a browser to confirm it shows JSON.
5. Use that hosted URL in `RemoteCatalogLoader`.
