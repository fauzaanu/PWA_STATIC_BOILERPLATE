# BOILERPLATE FOR MAKING PWAS FROM STATIC SITES

## Resources:
- HTTPS server is needed - Github pages would work
- https://maskable.app/editor - to make icons
- https://favicon.io/ - for favicons
- https://www.pwabuilder.com - to export the application for all platforms

## Snippets
```
"screenshots": [
        {
            "src":"The src to your screenshot",
            "sizes":"The size of your screenshot, such as 2880x1800",
            "type":"The type of your image, such as image/png",
            "description":"The type of your image, such as image/png"
        }
    ]
```

## WHY THIS:
`<body oncontextmenu="return false">`
- to make sure that the context menu does not pop up when a user hold clicks a link

```
*{
    user-select: none;
    -webkit-user-select: none;
}
```
- to make sure that the context menu does not pop up when a user selects a text


# ANDROID
- If github pages:
    - Maker a  _config.yaml
    - `include: [".well-known"]`
    - Create .well-known folder and place assetlinks.json






