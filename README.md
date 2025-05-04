/ README.md
# RSS Feed Parser

A PHP package to parse RSS feeds and fetch full content from each article using Guzzle.

## Installation

```bash
composer require mohitrawat/rss-feed-parser
```

## Usage

```php
use MohitRawat\RssFeedParser\RssFeedParser;

$parser = new RssFeedParser('https://example.com/rss');
$articles = $parser->fetch();
print_r($articles);
```
## License
MIT
