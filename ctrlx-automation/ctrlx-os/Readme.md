# json-schema for ctrlX OS

This folder contain json-schema used in the ctrlX OS context.
They can be used to validate json or yaml files, dependant on the specific schema.

## FOSS Information Schema ([fossinfo.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/fossinfo/fossinfo.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/fossinfo/fossinfo.v1.schema.json
```

The fossinfo file is used to provide information about Free and Open Source Software (FOSS) used in an app to comply with Open Source Obligations. The content of the file is provided as part of the general Open Source Software Information on ctrlX OS when the app is installed. It allows the user of the system to comprehend the use of Open Source Software in the product.

#### Usage

The file needs to be provided as part of the package-assets of the app and must follow the naming convention as follows:

`package-assets/<app-name>/<app-name>.fossinfo.json`

Example:

`package-assets/ctrlx-myapp/ctrlx-myapp.fossinfo.json`

#### Example

[sample.fossinfo.json](./apps/fossinfo/sample.fossinfo.json)

## Package-Manifest Schema ([package-manifest.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/package-manifest/package-manifest.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/package-manifest/package-manifest.v1.schema.json
```

The package-manifest contains metadata of the app that is used by ctrlX OS. It allows a seemless integration of the app into the ctrlX OS system. Some of the manifold possibilities of the package-manifest are:

- Sidebar integration
- Reverse Proxy integration
- Widget declaration
- Scope declaration

#### Usage

The package-manifest file needs to be provided as part of the package-assets of the app and must follow the naming convention as follows:

`package-assets/<app-name>/<app-name>.package-manifest.json`

Example:

`package-assets/ctrlx-myapp/ctrlx-myapp.package-manifest.json`

For more information how to use the package-manifest in your app check out the Software Development Kit for ctrlX AUTOMATION Documentation: [https://boschrexroth.github.io/ctrlx-automation-sdk/package-assets.html#the-package-manifest](https://boschrexroth.github.io/ctrlx-automation-sdk/package-assets.html#the-package-manifest)

#### Example

[example.v1.package-manifest.json](./apps/package-manifest/example.v1.package-manifest.json)


## Setup Schema ([setup.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/rexroth-setup/setup.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/rexroth-setup/setup.v1.schema.json
```

The setup files is used to transfer a device configurations between multiple devices or to create a configuration to deploy a specific configuration to multiple devices.


## Configuration Schema ([configuration.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/solutions/configuration.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/solutions/configuration.v1.schema.json
```

The configuration file contains meta data of a ctrlX OS configuration, e.g. access rights for appDirectories.

#### Example

[example.v1.configuration.json](./solutions/example.v1.configuration.json)

## Diagnostics Schema ([diagnostics.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/diagnostics/diagnostics.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/diagnostics/diagnostics.v1.schema.json
```

The diagnostics file contains diagnostics messages (main and detail) including the assoziated texts. Per language it an indiviual file is required.

#### Example

[example.diagnostics.en-US.json](/ctrlx-automation/ctrlx-os/diagnostics/example.diagnostics.en-US.json)

### 

## Validation Schemas

### Port List Description Schema ([portlist-description.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/portlist-description/portlist-description.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/portlist-description/portlist-description.v1.schema.json
```

Required for the app validation process. Provides information about open ports of an app.

#### Example

[example.portlist-description.v1.json](/ctrlx-automation/ctrlx-os/apps/validation/portlist-description/example.portlist-description.v1.json)

### Slot and Plug Description Schema ([slotplug-description.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/slotplug-description/slotplug-description.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/slotplug-description/slotplug-description.v1.schema.json
```

Required for the app validation process. Provides information about used snapcraft interfaces (slots & plugs) of an app.

#### Example

[example.slotplug-description.v1.json](/ctrlx-automation/ctrlx-os/apps/validation/slotplug-description/example.slotplug-description.v1.json)

### Unix Socket Description ([unixsocket-description.v1.schema.json](https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/unixsocket-description/unixsocket-description.v1.schema.json))

```
https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-os/apps/validation/unixsocket-description/unixsocket-description.v1.schema.json
```

Required for the app validation process. Provides information about used unix sockets of an app.

#### Example

[example.unixsocket-description.v1.json](/ctrlx-automation/ctrlx-os/apps/validation/unixsocket-description/example.unixsocket-description.v1.json)

## About

Copyright © 2020-2024 Bosch Rexroth AG. All rights reserved.


<https://www.boschrexroth.com>

Bosch Rexroth AG  
Bgm.-Dr.-Nebel-Str. 2  
97816 Lohr am Main  
GERMANY  

## Licenses

MIT License

Copyright (c) 2020-2024, Bosch Rexroth AG

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
