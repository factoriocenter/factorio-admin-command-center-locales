# Factorio Admin Command Center Locales

Additional language support for [Factorio Admin Command Center](https://github.com/factoriocenter/factorio-admin-command-center).

| Engine | Locale package | FACC package |
| --- | --- | --- |
| Factorio 2.1 | 1.4.0 | 4.4.0 |
| Factorio 2.0 fallback | 1.3.9 | 4.3.3 |

Both packages contain the same translations. Factorio accepts only one major/minor engine version in `info.json`, so install the package matching your game.

The **Zip and Upload Mod** GitHub workflow builds and attaches both ZIPs when creating a release or running it manually. Its package generation step is self-contained.

The default manifest targets 2.1; `compatibility/2.0.json` supplies the fallback metadata. Both packages include the same completed translations, planet teleport help, and corrected setting descriptions across all seven companion languages.
