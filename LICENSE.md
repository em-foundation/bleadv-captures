# License

<!-- SPDX-License-Identifier: CC-BY-4.0 AND MIT -->

This repository contains several different kinds of material, and they are licensed differently.
Where any section of this file conflicts with a third-party license covering material in this
repository, the third-party license governs.

> **Note on the previous license.** Until this file, this repository carried an MIT-only `LICENSE`.
> MIT is the right license for the tooling here, but it is not the right license for measurement
> data, which is what most of this repository is. This file keeps MIT for the code and moves the
> benchmark definition, documentation and capture data to CC BY 4.0. Material already released under
> the previous license remains available under it to anyone who received it.

## Benchmark definition, documentation, and measurement data

Everything in this repository that is neither source code nor third-party material is licensed under
the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0). This includes the benchmark definition, the README and other documentation, platform and
power-source declarations, capture metadata, and the measurement data itself.

Copyright (c) 2025-2026 The EM Foundation and the individual contributors identified in this
repository's commit history. Each contributor holds copyright in the material that contributor
authored.

You are free to share and adapt this material for any purpose, including commercially, provided you
give appropriate credit, link to the license, and indicate if changes were made.

Full license text: <https://creativecommons.org/licenses/by/4.0/legalcode>

CC BY 4.0 is used here rather than an earlier version because it explicitly covers *sui generis*
database rights, which apply to the capture data.

### What this license covers, and what it does not

CC BY 4.0 licenses the *expression* of this benchmark, not the underlying method. Implementing this
benchmark, measuring against it, and publishing your own results require no permission from anyone.
The license governs reuse of this repository's text, declarations, and measurement data.

Consistent with Section 2(b)(2) of CC BY 4.0, no trademark or patent rights are licensed by this
file.

The advertising payload prescribed by this benchmark includes the Bluetooth SIG Company Identifier
`0x08D3`, which is assigned to Novel Bits, LLC. That identifier is not licensed by this file. Novel
Bits, LLC permits its use in the advertising payload of implementations measured against this
benchmark, and for no other purpose.

## Source code

Any source code in this repository that was authored by the EM Foundation or by contributors to this
repository is licensed under the MIT License. This applies to whatever such code the repository
contains at any given time, and to none of the vendor SDK sources, vendor project files, or compiled
firmware images covered by the "Third-party material" section below.

```
MIT License

Copyright (c) 2025-2026 The EM Foundation

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
```

Creative Commons recommends against using CC licenses for software, which is why code is covered by
MIT rather than by the CC BY 4.0 grant above.

## Third-party material

Some material in this repository originates with third parties: vendor SDK sources, generated
configuration, build products, compiled firmware images, and vendor project files, retained as build
provenance.

**That material remains under its own license, whether or not a copy of that license accompanies it
here. Nothing in this file grants any right in it, and the sections above do not apply to it.** Where
a third-party license is more restrictive than the terms above, the third-party license governs for
that material. Copyright notices must be retained.

Measurement data is not third-party material. Capture archives containing only recorded samples are
covered by the CC BY 4.0 grant above.

## Attribution

When citing or reusing this work, please credit:

> BlueJoule benchmark, The EM Foundation. Methodology by Bob Frankel (The EM Foundation) and
> Mohammad Afaneh (Novel Bits).

For a specific measurement result, also cite the capture path and the commit it was taken from, since
results are revised as methodology improves.

## Contributions

Contributions are welcome. By submitting a contribution you license it to the public under the terms
above, matching the material type: CC BY 4.0 for documentation, declarations, and data, and MIT for
code.

**Each contributor retains copyright in that contributor's own contributions.** No copyright
assignment is made, required, or implied by this file or by the act of contributing, and the
copyright lines in the sections above are not a claim to any contributor's work. No contributor
grants any license to any other work, whether or not that work is related to this repository or
referenced by it.
