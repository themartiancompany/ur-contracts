[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (----------------------------------------------------)
[comment]: <> (Copyright © 2021, 2022, 2023,)
[comment]: <> (            2024, 2025, 2026)
[comment]: <> (            Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (----------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the)
[comment]: <> (GNU Affero General Public License as published)
[comment]: <> (by the Free Software Foundation, either version)
[comment]: <> (3 of the License.)

[comment]: <> (This program is distributed in the hope that it)
[comment]: <> (will be useful, but WITHOUT ANY WARRANTY;)
[comment]: <> (without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.)
[comment]: <> (See the GNU Affero General Public License)
[comment]: <> (for more details.)

[comment]: <> (You should have received a copy of the)
[comment]: <> (GNU Affero General Public License)
[comment]: <> (with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Ur contracts

This repository contains
[Ur](
  https://github.com/themartiancompany/ur)
Solidity contracts and the configuration
for their deployments.

In particular it contains a
Javascript module which contains a load function
for Ur contracts data, such as the
source, its ABI and bytecode.

The data is generated at package build time
using
[EVM Make](
  https://github.com/themartiancompany/evm-make).


## Build

To build the module one can use GNU Make

```bash
make \
  all
```

or npm

```bash
npm \
  install
```

## Installation

After build you can run
using GNU Make

```bash
make \
  install-npm
```

On the Ur itself this package
is called `ur-contracts` and it is
part of the
[`ur`](
  https://github.com/themartiancompany/ur-ur)
package, here linked at its Github
mirror.

The package has also been published on the
[NPM Registry](
  https://npmjs.com/package/ur-contracts)

# License

This originally MIT licensed file is distributed
under the GNU Affero General Public License version 3
by Pellegrino Prevete.
