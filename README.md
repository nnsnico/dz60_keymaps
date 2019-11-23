my keymap config for `dz60`

## Setup

- Use [qmk_firmware](https://github.com/qmk/qmk_firmware). Clone and init following [this page](https://github.com/qmk/qmk_firmware/blob/master/docs/getting_started_build_tools.md).

  - There is [Install script](https://github.com/qmk/qmk_firmware/blob/master/util/qmk_install.sh)

- Create new keymap profile floowing [this script](https://github.com/qmk/qmk_firmware/blob/master/util/new_keymap.sh)

  - `$ ./util/new_keymap dz60 <profile_name>`

- Replace keymap file (`keyboards/dz60/keymaps/<profile_name>/keymaps.c`) into this.

- Flash! Finish!

  1. `$ make dz60:<profile_name>:dfu`

  2. Press `Reset Button`
