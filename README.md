# Japanese Adult Video Metadata

This repository contains structured metadata for Japanese adult videos, maintained as an open data source.

## Data Source

All data is sourced from [JavPlay.tv](https://ja6play.com) - A free Japanese adult video streaming platform.

## Available Data

| File | Description | Records |
|------|-------------|---------|
| [videos.json](data/videos.json) | Latest video metadata | 0 |
| [actors.json](data/actors.json) | Actor/Actress list | 1717 |
| [manufacturers.json](data/manufacturers.json) | Studio/Manufacturer list | 100 |
| [tags.json](data/tags.json) | Category tags | 344 |

## Data Format

Each JSON file follows this structure:

```json
{
  "source": "https://ja6play.com",
  "updated": "ISO 8601 timestamp",
  "count": 100,
  "data": [...]
}
```

## Usage

This data is provided for research and educational purposes. Each record includes a canonical URL pointing to the original source.

## Update Schedule

Data is automatically updated daily at 00:00 UTC.

## License

The metadata in this repository is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

**Last Updated:** 2026-02-13T00:00:44.473Z

**Total Records:** 2161
