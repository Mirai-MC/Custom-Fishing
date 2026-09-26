# CustomFishing

CustomFishing is a customizable fishing plugin for modern Minecraft servers. It provides fishing minigames, weighted loot, conditions, actions, custom fishing environments, and an API for extending its mechanics.

This repository is a maintained fork focused on the current server stack.

## Compatibility

| Component | Supported version |
| --- | --- |
| Minecraft | 26.3 |
| Java | 25 |
| Paper API | 26.3 |
| Folia / Lophine | Supported |
| CraftEngine | 26.9.2-SNAPSHOT |
| CustomCrops | 3.6.57 |

CraftEngine and CustomCrops integrations are optional. The plugin can also integrate with other supported economy, placeholder, item, skill, quest, region, and season plugins when they are installed.

The versions above were tested together on Lophine 26.3 with its Folia region scheduler enabled.

## Features

- Configurable fishing loot, conditions, actions, mechanics, and minigames
- Custom environments such as lava fishing and void fishing
- Fishing bags, markets, competitions, and statistics
- Extensible API for custom integrations
- Folia-compatible scheduling

## Building

Install JDK 25, then run:

```shell
./gradlew clean build
```

On Windows:

```powershell
.\gradlew.bat clean build
```

The plugin JAR is generated in `target/`.

## Development API

The API module uses the following coordinates:

```kotlin
dependencies {
    compileOnly("net.momirealms:custom-fishing:2.3.26")
}
```

## Credits and license

CustomFishing was originally created by XiaoMoMi. This maintained fork is distributed under the [GNU General Public License v3.0](LICENSE).
