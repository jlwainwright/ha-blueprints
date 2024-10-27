# 🏠 Home Assistant Blueprints Collection

A curated collection of high-quality Home Assistant blueprints for various automation needs. Each blueprint is thoroughly documented and maintained.

## 📑 Available Blueprints

### Security
- [Paradox Zone Parser](./security/paradox_zone_parser/README.md) - Create entities from Paradox alarm zone MQTT messages

<!-- Add new blueprints here -->

## 🔧 Installation

### Using My Home Assistant
1. Click the "Add Blueprint" button in each blueprint's README
2. Follow the blueprint-specific configuration instructions

### Manual Installation
1. Copy the desired YAML file from the appropriate directory
2. In Home Assistant, go to `Configuration -> Blueprints`
3. Click the `Import Blueprint` button
4. Paste the raw YAML URL and import

## 📁 Repository Structure
```
ha-blueprints/
├── LICENSE
├── README.md
├── security/
│   └── paradox_zone_parser/
│       ├── README.md
│       └── paradox_zone_parser.yaml
├── media/                    # Blueprint screenshots and demos
│   └── paradox_zone_parser/
├── lighting/                 # Future category
├── climate/                  # Future category
└── utilities/               # Helper blueprints and tools
```

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting changes.

### Blueprint Requirements
- Complete documentation with setup instructions
- Error handling for all inputs
- Clear version history
- Example configurations
- Testing instructions

## 📝 License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Support

If you find these blueprints helpful:
- Star this repository
- Report issues in the Issues tab
- Share with the Home Assistant community

## 🔄 Version Control

Each blueprint follows semantic versioning (MAJOR.MINOR.PATCH):
- MAJOR: Breaking changes
- MINOR: New features, backwards-compatible
- PATCH: Bug fixes, backwards-compatible

## 📅 Maintenance

This repository is actively maintained. For each blueprint:
- Security fixes are prioritized
- Breaking Home Assistant changes are addressed promptly
- Feature requests are evaluated regularly

## 🔗 Useful Links

- [Home Assistant Blueprints Documentation](https://www.home-assistant.io/docs/automation/using_blueprints/)
- [Blueprint Exchange Forum](https://community.home-assistant.io/c/blueprints-exchange)
- [Home Assistant Community](https://community.home-assistant.io/)
