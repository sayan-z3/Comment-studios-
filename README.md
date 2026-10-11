# Comment Studio

Create realistic, editable social-media-style comments for video edits—without logging in, paying, or adding a watermark.

**Live app:** [commentstudio.pages.dev](https://commentstudio.pages.dev)

> Comment Studio is an editor-friendly mockup generator. It creates fictional comment graphics for creative work, prototypes, presentations, and video overlays. It is not affiliated with YouTube, Instagram, or Facebook.

## What it does

Comment Studio helps video editors build believable comment overlays in a few seconds:

- **Three familiar layouts:** YouTube, Instagram, and Facebook
- **Live preview:** See every change instantly before exporting
- **Editor-focused controls:** Name, handle, avatar, verification badge, text, timestamp, likes, reactions, pinned comments, creator hearts, and replies
- **Fast identity generation:** Roll a realistic profile with regional identity presets
- **Comment templates:** Start with curated viral, tutorial, humor, appreciation, and debate comments
- **Flexible backgrounds:** Transparent checkerboard, green screen, dark, or light
- **Export-ready output:** Transparent PNG, JPG, green-screen PNG, and clipboard copy
- **High-resolution rendering:** 2× and 3× export scale for crisp video overlays
- **No account required:** Open the hosted app and start creating

## Quick start

1. Open [commentstudio.pages.dev](https://commentstudio.pages.dev).
2. Choose **YouTube**, **Instagram**, or **Facebook**.
3. Customize the profile and comment content.
4. Select **Alpha** for a transparent overlay or **Green** for chroma-key workflows.
5. Export the PNG/JPG or copy the rendered comment to your clipboard.

## Typical editing workflows

### Transparent overlay

Choose **Alpha** and download a transparent PNG. Import it above your footage in Premiere Pro, DaVinci Resolve, CapCut, Final Cut Pro, or another editor.

### Green-screen overlay

Choose **Green Screen** when your editor workflow is built around chroma keying. The output uses the standard bright green `#00FF00` backdrop.

### Quick social proof mockup

Use the template picker to create a natural-sounding reaction, then adjust the username, likes, timestamp, and platform details to match the scene.

## Project status

The public hosted experience is available at [commentstudio.pages.dev](https://commentstudio.pages.dev). This repository is the project home for public documentation, product direction, and future source releases.

The initial repository snapshot contained only a generated placeholder README; the application build is currently deployed separately. Keeping that distinction explicit makes the repository easier to trust and maintain.

## Roadmap

- [ ] Publish the complete application source in this repository
- [ ] Add a reproducible local development setup
- [ ] Add automated build and type-check workflows
- [ ] Add saved presets and custom preset collections
- [ ] Add more platform-specific comment layouts
- [ ] Add export size presets for common video formats
- [ ] Add a small visual regression test suite

## Contributing

Ideas, bug reports, and improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the preferred workflow and standards.

## Responsible use

Generated comments should be clearly fictional and used as creative assets. Do not use Comment Studio to impersonate real people, fabricate endorsements, mislead viewers, or create deceptive evidence.

## License

This project is released under the [MIT License](LICENSE).
