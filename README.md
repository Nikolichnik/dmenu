# dmenu

Heavily inspired by the Luke Smiths's build. Check his work [here](https://github.com/LukeSmithxyz).

Extra stuff added to vanilla dmenu:

- Reads Xresources (ergo pywal compatible).
- Alpha patch, which importantly allows this build to be embedded in transparent st.
- Can view color characters like emoji (libxft-bgra is required for this reason).
- `-P` for password mode: hide user imput.
- `-r` to reject non-matching input.
- dmenu options are mouse clickable.

## Installation

You must have `libxft-bgra` installed until the libxft upstream is fixed.

After making any config changes that you want, but `make`, `sudo make install` it.
