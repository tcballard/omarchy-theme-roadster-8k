# Develop and test Roadster

Run `./tests/run` and `sha256sum -c SHA256SUMS`. Do not edit generated current-theme files.

Install with `omarchy theme install https://github.com/tcballard/omarchy-theme-roadster-8k`. This applies the theme and replaces an existing theme-roadster-8k installation. Preserve local changes and record the previous theme/background first.

The checked target is Quattro revision 51bfd1dbaa1b5f790e19623faf2745945d40c796. See VALIDATION.md for offline evidence. On the XPS, verify shell menus, launcher, notifications, lock screen, focus/selection/disabled states, display scaling, terminals, editor and GTK app. Switch away and back, cycle wallpaper, then restart the shell or log in again. Record real results in ACCEPTANCE.json and capture a desktop preview.

Roll back with the theme picker. Remove only this theme's directory after preserving local edits. Registry submission needs a live preview and resolved media attribution/permissions. All packaged images are below the observed registry 50 MiB per-image limit.
