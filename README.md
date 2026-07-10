<h3 align="center">
	<img src="https://raw.githubusercontent.com/h4lodev/h4webv2/refs/heads/master/src/assets/logo.svg" width="100" alt="Logo"/><br/>
	H4RING <a href="https://en.wikipedia.org/wiki/Webring">Webring</a>

</h3>

<p align="center">
	<a href="https://github.com/isabelroses/catppuccin-webring/contributors"><img src="https://img.shields.io/github/contributors/h4lodev/h4ring?colorA=99a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

## How to join

- You may be asking yourself: "How can I join this super cool webring???"\
  The answer to that amazing question is to open a pull request with your website added to the `websites.json` file!

  - Full **title** of your site
  - A brief **description** of your site
  - Some form of **contact info** (can be basically anything)
  - If you have one, your **RSS** link

  An entry might look like:

  ```json
  {
    "name": "Example Name",
    "slug": "example",
    "about": "Boring example",
    "url": "https://example.com/",
    "rss": "https://example.com/index.xml",
    "owner": "person@example.com"
  }
  ```

  After you've filled out that PR, you can add the buttons of the webring to your site! Make sure to place your SLUG in the urls!

  ```html
  <a href="https://webring.h4lo.ca/YOUR_SLUG/previous">&larr;</a
  ><a href="https://webring.h4lo.ca/">H4RING</a
  ><a href="https://webring.h4lo.ca/YOUR_SLUG/next">&rarr;</a>
  ```

## Special Thanks:

- [Isabel Roses](https://github.com/isabelroses) For the amazing workflow code
