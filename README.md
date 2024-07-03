# CtlReferences Library

This library is a LabVIEW add-on to help manage front panel references.

It is a by reference wrapper of a reference dictionary.  On initialization it will parse the specified front panel for any control references and add them to the dictionary by name.

Downstream the references can be pulled out for use by the control name.  Type coercion is included in the VIM API.
Additionally, "quick" API access is included for common actions like hide/show & enable/disable controls.

This has only been tested on Windows systems, but should be compatible with linux.  

This is currently written in LabVIEW 2020 and should be maintained there for compatibility with the Map data type released that year.
There is a secondary (older) class that could be used which utilizes Variant Attributes instead of Maps, and could be backported to previous versions.

There are no 3rd party dependencies.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

To contribute to this toolkit, you will need 32-bit LabVIEW 2020.

## Credits

CtlReferences LabVIEW library is an open source project maintained by Viviota and licensed by the MIT license

## License

CtlReferences LabVIEW library is distributed under the open source MIT license providing everyone right to use and distribute both souce code and compiled versions of this toolkit. See LICENSE.md file for details.