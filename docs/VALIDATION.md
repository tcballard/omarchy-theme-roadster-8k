# Validation — Roadster

Target: omacom/omarchy Quattro 51bfd1dbaa1b5f790e19623faf2745945d40c796. Date: 2026-10-16.

PASS: Real upstream headless theme application in an isolated account directory; local installation and Git-provenance staging; template generation (24 configuration files); parsed TOML/JSON; no unresolved template placeholders; red shell controls/bar/menu/countdown/image-picker tokens; default wall-ride selection; second application cycles; switch away and back restores remembered wallpaper; installer refuses existing destination; all eight previously decoded/verified 8K PNGs match their hashes.

Contrast: foreground/background 13.89:1; foreground/selection 10.48:1; accent/background 5.27:1; muted/background 5.40:1.

NOT RUN: bundled Rust helper (cargo unavailable), registry validator, live desktop rendering and input. This offline check does not certify rendering, GTK application appearance or marketplace approval.

Remaining live checks on the XPS: theme switch and switch back; launcher, menus, notification, lock and authentication screens; focused/selected/disabled states; bar at each used orientation; 100% and mixed display scales; terminal, editor and GTK app reloads; shell restart/login; wallpaper crop on the installed monitor. Record Omarchy version and scale. Preserve the prior theme and wallpaper before testing.

No preview.png is included because no live desktop screenshot was captured. Public submission also requires wallpaper source/licence confirmation.

Repository packaging: 03-hover-8k.webp uses lossless WebP because the GitHub blob API rejected the original 54 MiB PNG. Full decoded RGB byte hashes match the original PNG exactly. The other seven PNGs are unchanged. Repository SHA256SUMS reflects these packaged bytes.

Poster addition: ninth wallpaper, lossless sRGB PNG at 8192 × 4608. Fully decoded and visually reviewed at full-frame and 100% detail. Existing eight wallpaper bytes and default selection preserved.
PASS for the ninth-image update: portable repository checks and five Node tests; all nine image checksums; real upstream headless Git-installed staging, nine-image cycle, default, wraparound and remembered selection. Live desktop interaction is not implied by this check.

Starlight addition: tenth wallpaper, lossless RGB8 sRGB PNG at 8192 × 8192, copied byte-for-byte from the reviewed and fully decoded export. Original received two contextual passes; Tokyo Night is a separate 1254 × 1254 colour edit enlarged to 8K. Existing nine wallpapers and wall-ride default are unchanged. No new live desktop acceptance is claimed.
