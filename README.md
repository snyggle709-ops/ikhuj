# CesiumMC plugin source backup

Latest source backups from this chat:

- `sources/LeafChestShop/1.2.2/` — LeafChestShop 1.2.2
- `sources/WorldsGreatestModeration/1.0.3/` — WorldsGreatestModeration 1.0.3
- `sources/CesiumItemGuard/1.0.1/` — CesiumItemGuard 1.0.1 (WGM-only punishment integration)

The source exports are split into numbered `.txt` parts because of connector/file-size handling. Concatenate the parts in numeric order to reconstruct the original complete source export.

Linux/macOS example:

```sh
cat sources/WorldsGreatestModeration/1.0.3/*.part*.txt > WorldsGreatestModeration_Source_1.0.3.txt
```

Do the same for the other plugin directories.
