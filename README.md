# chrome-hack
Customize Chrome behaviours with css and javascript

### Usage
- Checkout this repo and load as an "unpacked" extension. This lets you import and run your own css and javascript
- add/update entries to the "content_scripts" section of `manifest.json` to include your new script, i.e.:
  ```json
  "content_scripts": [
    {
      "matches": ["https://some-site.com"],
      "css": ["scripts/my-new-styling.css"]
    }
  ]
  ```
