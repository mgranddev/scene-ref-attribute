# Scene Reference Attribute
> [!IMPORTANT]
> This is a separate fork. The original repository can be found here: https://github.com/KyleBanks/scene-ref-attribute

Unity C# attribute for serializing **component and interface references** within the scene or prefab during `OnValidate`, rather than using `GetComponent*` functions in `Awake/Start/OnEnable` at runtime. 

This project aims to provide:

- a simple set of tags for declaring dependency locations
- resolution, validation and serialisation of references **(including interface types!)**
- determinate results so you never have to worry about Unity losing your references, they'll always be safely regenerated

The package contents can be found in the `package` directory. For further details about this package, please see [`package/README.md`](package/README.md).