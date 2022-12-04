# Subscribe-O-Mast

A tool to export, import and subscribe to Mastodon Filters and Tags.

Includes a publicly maintained list of Mastodon filters and tags for easy synchronisation.

## Usage

### Setup

```shell
./subscribe-o-mast
```

- Subscribe-O-Mast will create a config file in `config.json` if it doesn't exist.
- Update the config file with your Mastodon API key.
- Optionally add a filter/tag URL you want to subscribe to.

### Export

To create a backup of your filters and tags, run:

```shell
./subscribe-o-mast export
```

### Import

To import a backup of your filters and tags, run:

```shell
./subscribe-o-mast import <file> #TODO: support command line args rather than a menu
```

Example:

```shell
./subscribe-o-mast import #TODO: link to example file
```

### Sync

To sync your filters and tags with a publicly maintained list, run:

```shell
./subscribe-o-mast sync <url>
```

## Filter and Tag Subscription URLs

## Contributing

Please consider contributing to this repository to add more filters and tags you think people might find useful.

Simply raise a PR with your additional to the `filters/<filter-name>.json` and/or `tags/<tag-name>.json` files which can be exported as above.

## License

MIT
