# claude-3d-animation-web-designer-7m4ow

A collection of packaged Claude skills (`.skill` = gzipped tarball of a skill directory containing `SKILL.md` + `references/`).

## Skills

### `3d-animation-web-designer.skill`
Build cinematic, dark-luxury 3D animated websites — particle systems, scroll
animations, glassmorphism, preloaders, CSS skylines, and premium motion design.

### `consistent-video-prompt-designer.skill`
Turn reference images (character model sheets, location plates, style frames)
into highly detailed, structured prompts for AI video generation that stay
**consistent across every shot, cut, and scene**. Extracts a locked
"fingerprint" (character / world / look) from the image and re-injects it into
every shot prompt to kill drift. Works with Seedance, Kling, Runway, Veo, Sora,
Hailuo, Pika, Luma, and Wan. Contains:
- `SKILL.md` — the 5-step workflow + anti-drift techniques + consistency checklist
- `references/character-bible-template.md` — forensic image-read checklist and
  character / world / look fingerprint templates
- `references/shot-prompt-templates.md` — the universal shot skeleton, camera
  vocabulary, per-platform dialects, frame-chaining, and a worked 5-cut storyboard

## Installing a skill locally

```bash
# unpack into your Claude skills directory
tar -xzf consistent-video-prompt-designer.skill -C ~/.claude/skills/
```
