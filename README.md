# ICUTKD Website

This is the ICUTKD website, new for 2020. It is built with [Hugo](https://gohugo.io/), which generates the website files. To edit the site, you will need to install Hugo.

## Editing Content

### Pages

Content is written in [markdown](https://www.markdownguide.org/). Website pages can be found in the `content/` directory. To add a new page, simply create a new file in this directory. Use the existing files as a template.

For more advanced functionality, read the Hugo documentation.

### Adding committee members

The committee page is a special page with its own template. It reads data from `data/committee.yml`. To edit the committee members, simply edit the entries in that file.

## Testing Locally

To preview your changes, you can run 

```
hugo serve
```

which will start a local webserver. Navigate to localhost:1313 to view a local version of the website.

## Uploading

Once you are done editing the site, you need to upload a new version of the website to the union webserver. To do this, first run 

```
hugo
```

to build the website. This will generate files in the `public/` directory. Then, all you need to do is upload the _contents_ of the `public/` file to the `/website/acc/taekwondo/` directory.

## Theme

The current theme is [Ananke](https://themes.gohugo.io/gohugo-theme-ananke/). To change this, simply change the `theme =` line in `config.toml`.
