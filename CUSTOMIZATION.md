# Customizing Landing Pages

This project uses plain HTML/CSS. You can tailor text, layout, and media by editing files directly.

## Editing text and content
- Open the HTML file for the page (e.g. `index.html`, `essencial.html`).
- Replace the text between tags such as `<h1>`, `<p>` or list items with your own copy.

## Adjusting dimensions
- Common sizes are controlled by CSS variables in `css/styles.css`:
  - `--container-max-width` – maximum width of page content.
  - `--section-padding` – top and bottom padding for sections.
- Change these values to increase or decrease the overall width or spacing.

## Adding images
1. Place image files in the `assets/` folder.
2. Reference them in HTML: `<!-- example -->\n<img src="assets/my-photo.jpg" alt="descricao">`.

## Adding videos
1. Upload video files to the `assets/` folder (e.g. `intro.mp4`).
2. Embed them in HTML using the `<video>` tag:
   ```html
   <video controls width="320">
     <source src="assets/intro.mp4" type="video/mp4" />
     Seu navegador não suporta vídeo.
   </video>
   ```

After saving changes, reload the page in your browser to see the updates.
