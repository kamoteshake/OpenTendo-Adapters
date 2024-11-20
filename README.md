# OpenTendo-Adapters
Some components of OpenTendo are already obsolete or NRND (Not Recommended for New Design). OpenTendo-Adapters is trying to solve this issue by using a modern equivalent of the OpenTendo components with different footprints and adapting it OpenTendo.

> [!NOTE]
> If for some reason you can't find the components listed in the BOMs and/or decided to find your own, I recommend looking at the `Datasheets` folder. I've included the datasheets of the components used in OEM NES. Look for components that are close to the original component from OEM NES spec wise and that fits on the footprint in the adapters (or you could always fork this and update your own adapter 😉).


## File Structure
```
.
├── <Reference> Adapter  # Contains all files for a specific adapter.
|   |                      "Reference" is based from OpenTendo (i.e. X2 Adapter).
|   ├── BOM              # Contains the bill of materials.
|   ├── Datasheets       # Contains the datasheets of component/s used in the OEM NES
|   |                      on the referenced footprint of OpenTendo.
|   ├── Gerber Files     # Contains The gerber files needed for fabrication.
|   └── KiCad            # Contains all files necessary to open the project in KiCad. 
```

## License
Licensed under the TAPR Open Hardware License ([www.tapr.org/OHL](www.tapr.org/OHL))
