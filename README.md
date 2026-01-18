# Scene Reference Attribute
> [!IMPORTANT]
> This is a separate fork. The original repository can be found here: https://github.com/KyleBanks/scene-ref-attribute

Unity C# attribute for serializing **component and interface references** within the scene or prefab during `OnValidate`, rather than using `GetComponent*` functions in `Awake/Start/OnEnable` at runtime. 

This project aims to provide:

- a simple set of tags for declaring dependency locations
- resolution, validation and serialisation of references **(including interface types!)**
- determinate results so you never have to worry about Unity losing your references, they'll always be safely regenerated

## Installation

*(written for Unity 6.3, but these steps will be similar for other versions)*

### Recommended: Git URL

This package can be easily installed from GitHub using its git URL:

1. **Open Package Manager:** Window -> Package Management -> Package Manager
2. **Add Package:** Plus Button *(top-left corner)* -> Install package from git URL
3. **Copy and Paste this URL:**
```
https://github.com/mgranddev/scene-ref-attribute.git?path=/package#v0.1.0
```

### Scoped Registry (GitHub Packages)

> [!IMPORTANT]
> This is an advanced installation process.

You can also install from GitHub Packages:

**Scoped Registry Config**
- **Name:** GitHub Packages (@mgranddev)
- **URL:** https://npm.pkg.github.com/@mgranddev
- **Scope(s):** dev.mgrand

**Package Installation**
- **Name:** dev.mgrand.scene-ref-attribute

You must have a GitHub personal access token (classic) configured for this to work.

For further details, see this discussion: https://discussions.unity.com/t/using-github-packages-registry-with-unity-package-manager/784073

## Package Location

The package contents can be found in the `package` directory. For further details about this package, please see [`package/README.md`](package/README.md).
