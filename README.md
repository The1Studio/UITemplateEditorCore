# TheOne Template Editor

**Core editor tools and configuration window for TheOne UITemplate**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Unity](https://img.shields.io/badge/Unity-2021.3%2B-blue.svg)](https://unity3d.com/get-unity/download)
[![UPM](https://img.shields.io/badge/UPM-Registry-green.svg)](https://upm.the1studio.org)

## Overview

This package provides the central configuration hub for all UITemplate features through the `TheOne/Configuration And Tools` menu item. It serves as the main entry point for project setup, feature configuration, and tool access.

## Features

- **Centralized Configuration Window**: Single location for all UITemplate settings
- **Feature Toggle Management**: Enable/disable UITemplate features
- **SDK Integration**: Configure third-party SDKs (ads, analytics, etc.)
- **Tool Integration**: Quick access to all UITemplate editor tools
- **Project Validation**: Verify correct project setup
- **Asset Searcher**: Powerful utility for finding and managing assets in your project

## Requirements

- Unity 2021.3 or higher
- Addressables Package 1.19.0+
- Cysharp.UniTask 2.3.0+
- Newtonsoft.Json 3.0.0+
- TheOne Extensions 1.0.0+

## Installation

### Via UPM Registry (Recommended)

Add to your `Packages/manifest.json`:

```json
{
  "dependencies": {
    "com.theone.template.editor": "1.0.0"
  },
  "scopedRegistries": [
    {
      "name": "TheOne Studio",
      "url": "https://upm.the1studio.org",
      "scopes": ["com.theone"]
    }
  ]
}
```

### Via Git URL

```json
{
  "dependencies": {
    "com.theone.template.editor": "https://github.com/The1Studio/UITemplateEditorCore.git"
  }
}
```

## Usage

### Opening the Configuration Window

**Menu**: `TheOne → Configuration And Tools`

### Main Features

#### TheOneGDKWindow

The main configuration window provides:
- Project settings management
- Feature toggles for UITemplate modules
- SDK configuration for third-party integrations
- Quick access to optimization and utility tools

#### AssetSearcher

Utility class for finding and managing assets:

```csharp
using TheOne.Tool.Core;

// Example usage
var assets = AssetSearcher.FindAssets<GameObject>("t:GameObject");
```

## API Reference

### TheOneGDKWindow

Main configuration window accessible via Unity menu.

### AssetSearcher

Static utility class for asset management operations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About The One Studio

**The One Studio** is a mobile game development company specializing in hypercasual and casual games.

- Website: [https://the1studio.com](https://the1studio.com)
- Email: contact@the1studio.com

## Related Packages

- [UITemplate](https://github.com/The1Studio/UITemplate) - Complete Unity UI framework
- [Unity Optimization Tools](https://github.com/The1Studio/UnityOptimizationTools) - Project optimization toolkit
- [TheOne LocalData](https://github.com/The1Studio/UITemplateLocalData) - Local data management
- [TheOne Localization](https://github.com/The1Studio/UITemplateLocalization) - Localization tools
- [TheOne Project Migration](https://github.com/The1Studio/UITemplateProjectMigration) - Auto-migration system

## Support

- [GitHub Issues](https://github.com/The1Studio/UITemplateEditorCore/issues)
- [Documentation](https://github.com/The1Studio/UITemplateEditorCore#readme)

---

<div align="center">

Made with ❤️ by **The One Studio**

</div>
