<img align="left" width="128" height="128" src="Readme%20Resources/App%20Icon.png">

# Bombardier

A Mac utility that downloads and extracts [Boot Camp](https://support.apple.com/en-au/boot-camp) drivers with a single click:

![Bombardier](Readme%20Resources/Bombardier.png)

Bombardier is my homage to [brigadier](https://github.com/timsutton/brigadier), a command-line utility that has saved me countless hours troubleshooting Boot Camp driver packages.

## Features

*   [x] One click download of Boot Camp drivers
    *   The Boot Camp driver disk image (**DMG**) is automatically extracted from the downloaded Package (**PKG**)
    *   You can sort / filter / search any way to help narrow down the **Mac Models** / **Boot Camp Packages** you are looking for
    *   Boot Camp drivers are downloaded to a folder of your choosing (default: `~/Downloads/Bombardier`)
*   [x] Launching Bombardier will automatically update:
    *   The list of Mac Models
    *   The Apple Software Update Catalog (**SUCatalog**), used to determine Boot Camp drivers

        **Note:** The catalog can be overridden / reset via **Preferences**:

        ![Preferences](Readme%20Resources/Preferences.png)

## Build Requirements

*   Swift **5.3**.
*   Xcode **12.0**.
*   Runs on macOS Big Sur **11.0**.

## Download

Grab the latest version of **Bombardier** from the [releases page](https://github.com/ninxsoft/Bombardier/releases).

**Note:** Version **3.0** requires **macOS Big Sur** or later.

If you need to run **Bombardier** on an older operating system, you can still use version **2.x**.

## Credits / Thank You

*   Project created and maintained by Nindi Gill ([ninxsoft](https://github.com/ninxsoft)).
*   Tim Sutton ([timsutton](https://github.com/timsutton)) for his amazing work on [brigadier](https://github.com/timsutton/brigadier).
*   Adrien Le Mière ([@Moutok](https://macadmins.slack.com)) for the awesome app name.

## Version History

*   3.0
    *   Complete app rewrite - visual design overhaul and modern SwiftUI App Life-Cycle
    *   Boot Camp Packages now display versions
    *   Added filter and sort options in addition to search
    *   The Software Update Catalog can now be reset to the Apple default
    *   You can now specify a downloads directory (default: `~/Downloads/Bombardier`)
    *   Menubar items have been cleaned up
    *   Shiny new app icon!
*   2.0.1
    *   Fixed a bug where a package would attempt to download when a Mac row was double clicked
*   2.0
    *   Specify a custom Software Update Catalog URL via the Preferences!
    *   Results can be filtered either via **Mac Models** or **Boot Camp Packages**
    *   Search will now also detect dates and file sizes
    *   General UI improvements
    *   General code cleanup
    *   Shiny new app icon!
*   1.0
    *   Initial release

## License

>    Copyright © 2021 Nindi Gill
>
>    Permission is hereby granted, free of charge, to any person obtaining a copy
>    of this software and associated documentation files (the "Software"), to deal
>    in the Software without restriction, including without limitation the rights
>    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
>    copies of the Software, and to permit persons to whom the Software is
>    furnished to do so, subject to the following conditions:
>
>    The above copyright notice and this permission notice shall be included in all
>    copies or substantial portions of the Software.
>
>    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
>    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
>    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
>    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
>    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
>    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
>    SOFTWARE.
