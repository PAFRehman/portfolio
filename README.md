# 0xPAF — Personal Portfolio

Personal portfolio site for **Abdul Rehman** ([@0xpaf](https://x.com/0xpaf)) — Web3 community lead, builder, and writer based in Pakistan.

## Pages

| Route | Description |
|---|---|
| `/` | Home — intro, photo, recent writing, tools built |
| `/about` | Bio, photo, projects list |
| `/writing` | Published threads and articles |
| `/captures` | Photography with fullscreen lightbox |
| `/contact` | X, email, and GitHub links |

## Adding Images (Captures)

Place images in the root `/` directory named sequentially:

```
image1.jpg
image2.jpg
image3.jpg
image4.jpg
image5.jpg
image6.jpg
```

The captures page automatically loads these. Clicking any photo opens a fullscreen lightbox with left/right arrow navigation. Keyboard shortcuts: `←` `→` to navigate, `Esc` to close.

Your profile photo is `/image.jpg`.

## Tech Stack

- Pure HTML + CSS — no frameworks, no dependencies
- Google Fonts: EB Garamond + DM Sans
- Deployed on Vercel

## Deployment

Deployed via Vercel. The `vercel.json` handles routing so all `/about`, `/writing`, `/captures`, `/contact` routes serve their respective `index.html` files correctly.

## Links

- X: [https://x.com/0xpaf](https://x.com/0xpaf)
- GitHub: [https://github.com/PAFRehman](https://github.com/PAFRehman)
- Mail: abdulrehmansian786@gmail.com

## Tools Built

| Tool | Link |
|---|---|
| BulkTrade Validator Stats | [bulkvalidator.netlify.app](https://bulkvalidator.netlify.app/) |
| BulkCards | [bulkcards.vercel.app](https://bulkcards.vercel.app/) |
| BulkAcademy | [bulkacademy.netlify.app](https://bulkacademy.netlify.app/) |
