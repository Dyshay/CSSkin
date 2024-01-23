# CSSkin

CS Skin is a simple plugin to set Skin weapon on CS2

# Features

- Weapons
- Knife

# Interface

MySQLMM will expose an interface in `OnMetamodQuery` which can then be queried with `(IMySQLClient*)g_SMAPI->MetaFactory(MYSQLMM_INTERFACE, &ret, NULL);` by other plugins.
Interface definition can be found in `src/public`.

## Compilation

### Requirements

- [Metamod:Source](https://www.sourcemm.net/downloads.php/?branch=master) (build 1219 or higher)
- [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp/releases/latest) (1.0.153)
- [MongoDB](https://www.mongodb.com/)
- [SkinBridge](share soon)

### Instructions

- In **`addons/counterstrikesharp/configs/core.json`** set **FollowCS2ServerGuidelines** to **`false`**
  
