# Godot Core System

<div align="center">

[English](README.md) | [简体中文](README_zh.md)

![Godot v4.4](https://img.shields.io/badge/Godot-v4.4-478cbf?logo=godot-engine&logoColor=white)
[![GitHub license](https://img.shields.io/github/license/Liweimin0512/godot_core_system)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Liweimin0512/godot_core_system)](https://github.com/Liweimin0512/godot_core_system/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Liweimin0512/godot_core_system)](https://github.com/Liweimin0512/godot_core_system/issues)
[![GitHub forks](https://img.shields.io/github/forks/Liweimin0512/godot_core_system)](https://github.com/Liweimin0512/godot_core_system/network)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A highly modular and extensible core system framework designed for Godot 4.4+

[Getting Started](#getting-started) •
[Documentation](#documentation) •
[Examples](#examples) •
[Contributing](CONTRIBUTING.md) •
[Support](#support)

</div>

## ✨ Features

- 🎮 **State Machine System** - Flexible and powerful state management for game logic
- 💾 **Serialization System** - Easy-to-use save/load functionality with config management
- 🎵 **Audio System** - Comprehensive audio management with categories and transitions
- 🎯 **Input System** - Unified input handling with action mapping and event management
- 📝 **Logger System** - Detailed logging system with multiple output channels
- 🎨 **Resource System** - Efficient resource loading and management
- 🎬 **Scene System** - Scene transition and management made easy
- 🔧 **Plugin Architecture** - Easy to extend and customize
- 📱 **Project Settings Integration** - Configure all systems through Godot's project settings
- 🛠️ **Development Tools** - Built-in debugging and development tools

## 🚀 Getting Started

### System Requirements

- Godot Engine 4.4+
- Basic knowledge of GDScript and Godot Engine

### Installation Steps

1. Download the latest release from the [releases page](https://github.com/Liweimin0512/godot_core_system/releases)
2. Copy the `godot_core_system` folder to your Godot project's `addons` directory
3. Enable the plugin in Godot:
   - Open Project Settings (Project -> Project Settings)
   - Switch to the Plugins tab
   - Find "Godot Core System" and enable it

### Basic Usage

```gdscript
extends Node

func _ready():
    # Access managers through CoreSystem singleton
    CoreSystem.state_machine_manager  # State Machine Manager
    CoreSystem.save_manager          # Save Manager
    CoreSystem.audio_manager         # Audio Manager
    CoreSystem.input_manager         # Input Manager
    CoreSystem.logger               # Logger
    CoreSystem.resource_manager     # Resource Manager
    CoreSystem.scene_manager        # Scene Manager
```

## 📚 Documentation

Detailed documentation for each system:

| System | Description | Documentation |
|--------|-------------|---------------|
| State Machine System | Game state management and transitions | [View Docs](docs/state_machine_system_en.md) |
| Serialization System | Game save and config management | [View Docs](docs/serialization_system_en.md) |
| Audio System | Sound and music management | [View Docs](docs/audio_system_en.md) |
| Input System | Input control and event handling | [View Docs](docs/input_system_en.md) |
| Logger System | Logging and debugging | [View Docs](docs/logger_system_en.md) |
| Resource System | Resource loading and management | [View Docs](docs/resource_system_en.md) |
| Scene System | Scene switching and management | [View Docs](docs/scene_system_en.md) |

## 🌟 Example Project

Visit our [example project](examples/) to understand the framework's practical applications and best practices.

## 🤝 Contributing

We welcome all forms of contributions! Whether it's new features, bug fixes, or documentation improvements. See our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Support & Help

If you encounter any issues or have suggestions:

1. Check the [detailed documentation](docs/)
2. Search through [existing issues](https://github.com/Liweimin0512/godot_core_system/issues)
3. Create a new [issue](https://github.com/Liweimin0512/godot_core_system/issues/new)

### Community

- Join our [Discord Community](https://discord.gg/s7cnrHWA)
- Follow us on [itch.io](https://godot-li.itch.io/)
- Star ⭐ the project to show your support!

## 🙏 Acknowledgments

- Thanks to all developers who contributed to this project!
- Special thanks to every student at [Li's Game Academy](https://wx.zsxq.com/group/28885154818841)!
- Built with ❤️ by the Godot community

---

<div align="center">
    <strong>Built by Liweimin0512 with ❤️</strong><br>
    <sub>Making game development easier</sub>
</div>