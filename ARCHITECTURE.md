# Architecture

colors.toml owns the semantic palette. Omarchy generates supported application configuration from it.

shell.bar.toml, shell.controls.toml, shell.menu.toml and shell.launcher.toml replace complete upstream sections. They carry defaults from Quattro revision 51bfd1dbaa1b5f790e19623faf2745945d40c796 and change colours and focus/selection borders. Reconcile these sections when upgrading. Other shell sections remain generated; there is no full shell.toml override or install hook.

The nine backgrounds/ image files are the verified 8K exports. Alphabetical order makes 01-wall-ride-8k.png the first wallpaper. SHA256SUMS records exact bytes. User wallpaper history can override the initial selection after first use.

Portable validation covers metadata, palette syntax, contrast, links and workflow policy. Offline upstream checks and remaining live gates are recorded in docs/VALIDATION.md.
