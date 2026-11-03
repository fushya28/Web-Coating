# Industrial Coatings Supplier Website

A responsive, single-page product catalogue website with WhatsApp enquiries. No framework or build tools are required.

## Preview locally
1. Extract the ZIP file.
2. Open `index.html` in a web browser.

## Easy customization
Open `index.html` in a text editor (VS Code, Notepad++, etc.). Near the bottom, find:

```js
const STORE_SETTINGS = {
  STORE_NAME: "Industrial Coatings Supplier",
  TAGLINE: "Industrial & Marine Coating Solutions",
  WHATSAPP_NUMBER: "62811973067",
  DISPLAY_WHATSAPP: "+62 811-973-067",
  EMAIL: "",
  LOCATION: ""
};
```

Change `STORE_NAME`, `TAGLINE`, `EMAIL`, or `LOCATION` as needed. Keep `WHATSAPP_NUMBER` as digits only, including the country code, with no `+`, spaces, or hyphens. The display version can include spaces and symbols.

Product names and descriptions are in the `PRODUCTS` array immediately below `STORE_SETTINGS`. Edit each product there to update the catalogue.

## WhatsApp
All contact and product enquiry links use the WhatsApp number supplied by the site owner. Product buttons automatically include the relevant product name in the message.

## Notes
- Product illustrations are CSS placeholders, not official product packaging images. Replace them with authorized product photos when available.
- Product descriptions are summaries of the supplied technical data sheets. Some supplied documents are dated 2013–2014. Verify the latest technical documents, specifications, product availability and suitability before publishing or using them for a project.
- The website supports manual ordering through WhatsApp; it does not accept online payments.
- The temporary store name and copy should be updated to match the actual business before public launch.
