Product Launch Page
===

Build and deploy and single page "Product Launch Page"!

## Resources

Keep it Simple, looking for Teaser more than complete product page:
- [Mailchimp page builder](https://mailchimp.com/features/landing-pages)

### Images

- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)
- [Burst](https://burst.shopify.com/)

### Typography (Fonts)

- [Google Fonts](https://fonts.google.com/)
- [Font Squirrel](https://www.fontsquirrel.com/)

### Color Pallets

From image:
- [Canva generate from image](https://www.canva.com/colors/color-palette-generator/)
- [Generate from image](https://imagecolorpicker.com/)
- [Coolors](https://coolors.co/image-picker)

Designer/Color Palettes
- [Colour lovers](https://www.colourlovers.com/)
- [Adobe Color wheel](https://color.adobe.com/create/color-wheel)
- [Canva Color Wheel](https://www.canva.com/colors/color-wheel/)

### CSS Grid

- [CSS Tricks Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Project

Take a look at the demo pages for how-to's, ideas, inspiration. Feel free to copy,
but use _as you build_. Do not copy and change values!

Build your page in the following files:

File | Purpose
---|---
`index.html` | Main page with html and semantic elements
`global.css` | css for your page
`thank-you.html` | Page your form will "submit" to

## Commit

As you are working and complete small steps, stop and make a commit using the 
build-in VSCode sidebar tool:

- "Stage" the files you want to commit
- Enter a commit message and hit `CMD + ENTER` or `CTRL + ENTER` (mac or windows)

To "push" to GitHub, either hit "Sync" after committing, or hit the recycle wheel button in the lower left corner.

## Steps

1. Come up with a concept and find assets:
    - Image(s)
    - Content (okay to be silly or flippant)
    - Fonts
    - Sketch out general design
    - Decide on whether it will be responsive
1. Create your html
1. Add CSS to create your layout
    - Start with "narrow" mobile-first design
    - Consider separately:
        - layout
        - styling
    - Add additional layout css for wider viewports (laptop)
1. Make sure to add the following attributes to your form and its controls:
    - Use `method="GET"` and `action="thank-you.html"` to direct to the thank you 
    page when the form is submitted
    - Make sure to add an id to your input, and add `for="email"` (or whatever your id is) _to the label_. This makes the label associated with the input

## Deploying

Follow the instructions in the Resources on Canvas to deploy using GitHub pages