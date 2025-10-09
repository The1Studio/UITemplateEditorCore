# UITemplate Editor Core

**Core editor tools and configuration window for TheOne UITemplate**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Unity](https://img.shields.io/badge/Unity-2021.3%2B-blue.svg)](https://unity3d.com/get-unity/download)
[![UPM](https://img.shields.io/badge/UPM-Registry-green.svg)](https://upm.the1studio.org)

## Overview

UITemplate Editor Core provides the foundational editor infrastructure for TheOne UITemplate framework. It includes centralized configuration management, asset utilities, and integration points for all UITemplate features.

## Features

- **TheOneGDKWindow**: Centralized configuration and tools window
- **AssetSearcher**: Powerful asset search and management utilities
- **Configuration Management**: Project-wide settings and preferences
- **Integration Ready**: Seamless integration with UITemplate features

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

Access the main configuration window via:
**Menu**: `TheOne → Configuration And Tools`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About The One Studio

**The One Studio** is a mobile game development company specializing in hypercasual and casual games.

- Website: [https://the1studio.com](https://the1studio.com)
- Email: contact@the1studio.com

## Related Packages

- [UITemplate](https://github.com/The1Studio/UITemplate) - Complete Unity UI framework
- [Unity Optimization Tools](https://github.com/The1Studio/UnityOptimizationTools) - Project optimization toolkit
- [TheOne Features](https://upm.the1studio.org) - Modular feature packages

## Support

- [GitHub Issues](https://github.com/The1Studio/UITemplateEditorCore/issues)
- [Documentation](https://github.com/The1Studio/UITemplateEditorCore#readme)

---

<div align="center">

Made with ❤️ by **The One Studio**

</div>
