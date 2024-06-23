# symlink-to-con - Example repo with a symlink to `CON`

This is a simple example repo with a symbolic link whose target is `CON`, for
testing Git-related tools on Windows, where this is a valid but reserved
filename because it is a legacy DOS device name except when present in a `\\?\`
path, but where it is permitted to create a symlink to it regardless (much as
it is permitted to create a symlink to an invalid name like `???`).
