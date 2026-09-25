# Licensing

This repository is a fork of
[mtu-most/most-scad-libraries](https://github.com/mtu-most/most-scad-libraries),
the OpenSCAD libraries of Michigan Technological University's Open Sustainability
Technology (MOST) lab. [What applies where](#what-applies-where) is the operative
section — it is how these files are made available. The commentary around it is
for convenience; the binding terms are the full texts in [`LICENSES/`](LICENSES/).

Michigan Technological University, which holds the copyright in the MOST lab's own
files here, has licensed them under the terms below, following the
[FAST licensing policy](https://github.com/uwo-fast/.github/blob/main/LICENSING.md).
Upstream states no licence for most of them. Files by other authors keep their own
licences and are listed under [Third-party components](#third-party-components).

The root [`LICENSE`](LICENSE) is a copy of the GPL text. GitHub reports only one
licence per repository and reads that file, so this document is where the full
picture lives.

## What applies where

| Path | Licence | Copyright |
| --- | --- | --- |
| Every `.scad` file not listed under [Third-party components](#third-party-components), and `scadfont/` | `GPL-3.0-or-later` **and** `CERN-OHL-S-2.0` | 2013–2015 Michigan Technological University (authors Jerry Anzalone and Bas Wijnen); changes since, FAST research group and contributors |
| `readme.md`, `LICENSING.md`, `.gitattributes` | `GPL-3.0-or-later` **and** `CERN-OHL-S-2.0`, at your option | Michigan Technological University; FAST research group and contributors |

These are parametric CAD source, granted under both licences so that a licensee
who Makes a Product from geometry rendered with them can satisfy CERN-OHL-S-2.0 §4.
[`LICENSES/`](LICENSES/) holds both texts.

A design that includes one of the third-party files below also takes on that
file's terms.

## Third-party components

These keep their own licences, unaffected by this document. Each is described as
its own header states.

| Path | Author | Licence as stated |
| --- | --- | --- |
| `parametric_involute_gear_v5.0.scad` | Greg Frost, 2010 ([Thingiverse 3575](https://www.thingiverse.com/thing:3575)) | "Creative Commons - GNU GPL", no version given |
| `airtripper-extruder-gca.scad` | Airtripper, 2012, rewritten "by GCA" | "Creative Commons - GNU GPL", no version given |
| `gear_calculator.scad` | combines Greg Frost's gears with Cliff L. Biffle's `spur_generator` (2011) | `CC-BY-SA-3.0`, as the file states — [`LICENSES/CC-BY-SA-3.0.txt`](LICENSES/CC-BY-SA-3.0.txt) |
| `OpenScadFont.scad` | Steve Miller ([Thingiverse 6820](https://www.thingiverse.com/thing:6820)) | `CC-BY-SA-3.0` — [`LICENSES/CC-BY-SA-3.0.txt`](LICENSES/CC-BY-SA-3.0.txt) |
| `fnt-LeagueGothic/` | glyph outlines named for League Gothic, by The League of Moveable Type | `OFL-1.1`, the typeface's licence — [`LICENSES/OFL-1.1.txt`](LICENSES/OFL-1.1.txt) |

`PlanetaryGearboxModules.scad` and `planetary_extruder.scad` include
`gear_calculator.scad`, and `planetary_extruder.scad` also includes
`airtripper-extruder-gca.scad`, so a design using them combines these terms.

## Contributions

"Contribution" means any work of authorship intentionally submitted for inclusion
in this project — a pull request, patch, commit, issue, or other communication —
excluding anything conspicuously marked "Not a Contribution".

Unless you state otherwise, contributions you submit are licensed under whichever
of the licences above covers the files they touch, with no additional terms. By
submitting a contribution you represent that you have the right to license it on
those terms.

## Patents

GPL-3.0 (section 11) and CERN-OHL-S-2.0 (section 7) contain express patent
provisions. Review them before using, modifying, or distributing this project.

## Disclaimer of warranty and liability

A summary of terms in the licences themselves — GPL-3.0 sections 15–17 and
CERN-OHL-S-2.0 section 6.

THIS PROJECT, INCLUDING ALL SOFTWARE AND HARDWARE DESIGNS, IS PROVIDED "AS IS"
WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND
NON-INFRINGEMENT.

TO THE EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL THE AUTHORS,
CONTRIBUTORS, OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY ARISING FROM, OUT OF, OR IN CONNECTION WITH THIS PROJECT.

## Trademarks

No licence here grants trademark rights. This project does not grant permission to
use the names, trademarks, or logos of Michigan Technological University, the MOST
lab, the FAST research group, or the project's contributors, except as needed to
describe the project's origin.

## Precedence

Where the commentary in this document and the full licence texts conflict, the full
texts prevail. The table under [What applies where](#what-applies-where) is not
commentary — it is the statement of which files are made available under which
terms.
