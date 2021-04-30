# json-schema for ctrlX CORE

This folder contain json-schema used in the ctrlX CORE context.
They can be used to validate json files.

## Schemas

### fossinfo

Reference: https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-core/apps/fossinfo/fossinfo.v1.schema.json

The fossinfo file of an app is used to extend open source component list of the control.

- HINT: The fossinfo file is expected at: `package-assets/<package-name>/<package-name>.fossinfo.json`.
- IMPORTANT compatibility issue: In controls with app.deviceadmin <= 1.8, the final fossinfo file must only contain the components array as root element.

### package-manifest

Reference: https://json-schema.boschrexroth.com/ctrlx-automation/ctrlx-core/apps/package-manifest/package-manifest.v1.schema.json

The package-manifest contains meta data of a ctrlX CORE App and to seemless integrate it into the ctrlX CORE system

#### Changelog

<table>
  <tbody>
    <tr>
      <th>Version</th>
      <th>Implemented</th>
      <th>Changes</th>
    </tr>
    <tr>
      <td valign="top"><a href="./apps/package-manifest/package-manifest.v1.1.schema.json">package-manifest.v1.1.schema.json</a></td>
      <td valign="top">v0108</td>
      <td valign="top">
        <ul>
          <li>Documentation part: provide link to further documentation</li>
          <li>Update json-schema version</li>
          <li>Introduce url field in commandRequest, execution field is deprecated</li>
          <li>Target property for links</li>
          <li>Introduce certificate store for central certificate & key management</li>
          <li>Minor improvements</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td valign="top"><a href="./apps/package-manifest/package-manifest.v1.0.schema.json">package-manifest.v1.0.schema.json</a></td>
      <td valign="top">v0106</td>
      <td valign="top">
        <ul>
          <li>Initial Release</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## About

Copyright © 2020-2021 Bosch Rexroth AG. All rights reserved.


<https://www.boschrexroth.com>

Bosch Rexroth AG  
Bgm.-Dr.-Nebel-Str. 2  
97816 Lohr am Main  
GERMANY  

## Licenses

MIT License

Copyright (c) 2020-2021, Bosch Rexroth AG

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
