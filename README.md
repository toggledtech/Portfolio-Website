# Getting Started With Carbon

### Fork this Template
Start off by forking this template.

![How to fork](https://orionideteam.nimbusweb.me/box/attachment/9239909/lyei9z1e23e316aezdac/x1EYvP0pdTsPfNQ9/screenshot-github.com-2023.09.10-11_07_53.png)

### Carbon.json
All control of your web app can be found in `carbon.json`

Here is what the default `carbon.json` looks like:
```json
{
  "pages": [{
    "name": "Home",
    "doc": "index"
  },
  {
    "name": "About",
    "doc": "about"
  }],
  "logo": "carbon.png",
  "action": {
    "URL": "//carbon.toggled.tech",
    "text": "Try Carbon"
  },
  "title": "Carbon Starter"
}
```

### Adding, Removing, and Customizing Pages
To create a new page, you can need to add a JSON object to the array 'pages'.

```json
{
  "pages": [
    {
      "name": "Display Name (Also shown in URL)",
      "doc": "The file path of the Markdown code in your GitHub repo"
    }
  ]
}
```

Deleting a page can simply be done by removing the object from the `pages` array.

### Customizing your Web App
If you would like to edit the title, favicon, logo, or action button, then this can all be done via the `carbon.json` file.

```json
{
  "logo": "The file path of your logo. 80px x 80px (Cannot use external URL the photo must be in your GitHub Repo)",
  "action": {
    "URL": "The URL of your action button",
    "text": "The display text of your action button"
  },
  "title": "The title in the address bar for your site",
  "favicon": "The file path of your favicon. (Cannot use external URL the photo must be in your GitHub Repo)",
}
```
