# astro-mastodon-embed

## About

An Astro component for embedding Mastodon posts in your website.

This is very much a work in progress, and not at all ready for production.

## Install

In your Astro project, run the following command:

`npm install git+https://github.com/ghall89/astro-mastodon-embed.git`

## Importing & Usage

### Import

In your Astro or MDX file:

`import MastodonEmbed from 'astro-mastodon-embed'`

### Use Component

The MastodonEmbed component just needs a URL for the post you want to embed.

`<MastodonEmbed url={yourUrl} />`

By default, the component is in light mode. You can enable dark mode by passing the prop `variant="dark"`:

`<MastodonEmbed url={yourUrl} variant="dark" />`

## Dependencies

- [astro-remote](https://github.com/natemoo-re/astro-remote)

## Acknowledgments

- [Roboto](https://fonts.google.com/specimen/Roboto) - Used under the [Apache 2.0 license](./src/fonts/LICENSE.txt)
