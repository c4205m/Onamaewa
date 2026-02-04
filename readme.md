# Onamaewa - Batch Asset Renamer for Lens Studio

<img src="https://images.ctfassets.net/ub38vssza5h3/7FynBv68WKAHYYAe7XQhlk/dfa0ebd5e13c3bdd5b0f34345e65170f/LS.png" width="100" height="100" alt="Lens Studio">

A batch renaming tool for Lens Studio that helps you maintain consistent naming conventions across your project assets.

## Features

- **Type-based Prefixing**: Automatically adds standard prefixes based on asset type (e.g., "M_" for Materials, "T_" for Textures)
- **Case Conversion**: Convert between multiple naming conventions:
  - PascalCase
  - camelCase
  - snake_case
  - kebab-case
- **Sequential Numbering**: Add sequential numbers as either prefix or suffix
- **Find & Replace**:  Search and replace functionality with regex support
- **Bulk Operations**: Rename multiple assets at once with preview
- **Asset Type Support**: Works with all major Lens Studio asset types

## Supported Asset Types

| Category    | Prefix | Example Types |
|-------------|--------|---------------|
| Animation   | ANM_   | AnimationAsset, AnimationCurveTrack |
| Material    | M_     | Material |
| Mesh        | SM_    | FileMesh, FaceMesh, BodyMesh |
| Texture     | T_     | FileTexture, RenderTarget, DeviceCameraTexture |
| Tracking    | TRK_   | FaceTrackingScope, HandTracking3DAsset |
| Prefab      | PF_    | ObjectPrefab |
| Script      | S_     | JavaScriptAsset, TypeScriptAsset |
| Shader      | Mf_    | ShaderGraphPass |
| VFX         | VFX_   | VFXAsset |

## Usage

1. Select one or more assets in the Asset Browser
2. Right-click and navigate to `Onamaewa | Batch Rename`
3. Choose your renaming operation:
   - **By Type Convention**: Apply standard prefixes
   - **Find and Replace**: Search/replace text in names
   - **Add Index Prefix/Suffix**: Number your assets sequentially
   - **Case Conversion**: Change naming convention style

## Preview Before Renaming

All operations show a preview dialog before making changes, allowing you to:
- Review all changes
- Toggle individual renames on/off
- Cancel if anything looks incorrect

## Important Notes

- Renaming operations **cannot be undone** in LS - always review changes before confirming
- Some asset types (like environment maps) may not be detected properly
- For best results, organize assets before bulk renaming

## Contributing

Pull requests are welcome! Please open an issue first to discuss proposed changes.

---
Made by a developer who's still figuring things out
