# Berberim İrfan — Mobile logo assets

The mobile-ready logo package was prepared from the exact image supplied by the owner.
It preserves the original gold **iK** monogram, diagonal stroke, broken circular outline,
dark textured background, and proportions. The artwork was cropped from the original
photo and gently sharpened/upscaled; it was not redrawn with substitute lettering.

## Package contents

See the downloadable `berberim_irfan_mobile_assets.zip` package supplied with this task.

- Master: 2048×2048 PNG and 1024×1024 PNG
- Android: 48, 72, 96, 144, 192 px launcher variants and 432 px adaptive foreground
- iOS: 20, 29, 40, 58, 60, 76, 80, 87, 120, 152, 167, 180, 1024 px variants
- iOS starter `Contents.json`

## Integration recommendation

Use the 1024×1024 PNG as the single source image for the Flutter launcher icon
generator, then build and inspect Android adaptive masks and the iOS AppIcon catalog.
The current repository did not contain an application source tree, so the image assets
have not yet been wired into a Flutter project.
