# Agbamami Restaurant Menu Template

This is a mobile-first custom HTML menu based on the interface shown in your screen recording.

## Quick edits

Open `index.html` in a text editor.

At the top of the JavaScript section, change:

- `PHONE` to the restaurant phone number, e.g. `+233241234567`
- `WHATSAPP` if you want to add a WhatsApp button later
- `LOCATION` to the restaurant's Google Maps URL

Then edit the `MENU` array.

For a category photo:
1. Put the image in the `images` folder.
2. Set the category's `image` value, e.g. `image:"images/soups.jpg"`.

For items:
```js
{name:"Fufu with Goat Soup", price:"GH₵ 120", desc:"Optional description"}
```

## Hosting

This folder can be uploaded to a free static host such as GitHub Pages.

Once published, the public URL can be:
- used directly as the QR code destination, or
- embedded into Google Sites as an external page.

## Phone button

The call button uses a `tel:` link. On a customer's phone, tapping it opens the phone's calling interface with the restaurant number.

## Important

The sample prices and items are placeholders. Replace them with your real menu.
