# rss-to-json
> The GitHub Action for parsing multiple RSS feeds into a local JSON file.

## Usage

```yaml
- uses: i-valchev/rss-to-json@v1
```

All options:

```yaml
- uses: i-valchev/rss-to-json@v1
  with:
    source: data/feeds.yaml # An optional parameter to specify the source. Defaults to feeds.yaml
    target: output/feeds.json # An optional parameter to specify the target. Defaults to feeds.json
```

### `feeds.yaml` format

Specify as many URLs to RSS feeds to be included as you like.

```yaml
feeds:
 - https://example.org/rss.xml
 - https://another-example.org/feed
```
