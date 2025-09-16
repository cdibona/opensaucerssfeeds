# Available RSS Feeds

This directory contains RSS feeds for various YouTube channels, organized by category. Each feed is generated using the [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker) project.

## How to Use These Feeds

Simply copy the raw GitHub URL of any XML file and add it to your RSS reader:

Base URL: `https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/`

Example: `https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/tech/sample_tech_channel.xml`

## Available Feeds by Category

### Tech Channels
- [Sample Tech Channel](tech/sample_tech_channel.xml) - General technology tutorials and programming content

### Maker/DIY Channels  
- [DIY Workshop](maker/diy_workshop.xml) - Woodworking and workshop projects

### Science Channels
- [Science Explained](science/science_explained.xml) - Educational science content and explanations

### Educational Channels
(Coming soon...)

### Entertainment Channels
(Coming soon...)

## Feed Update Schedule

Feeds are updated periodically, but there's no guaranteed schedule. If you need the most up-to-date content, consider using the [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker) tool directly with your own YouTube API key.

## Contributing

If you have YouTube channels you'd like to see added as RSS feeds, feel free to submit a pull request with:
1. The generated RSS file in the appropriate category directory
2. An update to this index file

## Notes

- All feeds include video metadata like duration, views, and likes
- Thumbnails are included via Media RSS extensions
- Feeds are standard RSS 2.0 format compatible with most feed readers