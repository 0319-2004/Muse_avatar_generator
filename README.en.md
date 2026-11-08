**English** | [日本語](./README.md)

# Avatar Prompt Generator

A tool for building image-generation prompts to create avatar images with GPT Image and similar models.
Pick a style and character traits as chips, and a GPT Image–ready prompt is assembled on the spot.

## How to use

1. Open `index.html` in your browser (no server required — a single file)
2. Choose a style (3D figure, Pixar-like, clay model, pixel art, and more — 6 styles in total) along with character traits, hairstyle, outfit, expression, accessories, and color tone
3. Copy the generated prompt, paste it into GPT Image (or similar), and create the image
4. Hand the finished image to Muse to turn it into an avatar candidate (you can use the request text built into the tool as-is)

Includes a 日本語 / English language toggle. Prompts automatically append "front view, face close-up, simple background."

## Live demo

The tool is published with GitHub Pages:

**https://0319-2004.github.io/Muse_avatar_generator/**

To publish your own copy:

1. Create a new repository
2. Upload the HTML file as `index.html`
3. Go to Settings → Pages → choose "Deploy from a branch" (branch `main`, folder `/root`) and it will be available at a URL

## Notes

- This tool does not generate images itself. Its role is prompt generation.
- If you create images that blend in a real person's face, be mindful of portrait rights and similar concerns before publishing or sharing.
