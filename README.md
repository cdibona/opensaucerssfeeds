# Open Source RSS Feeds

This repository contains a collection of RSS feeds generated from popular YouTube channels using the [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker) project. The goal is to provide easy access to YouTube content via RSS without requiring users to set up their own YouTube API keys.

## 🎯 Purpose

The [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker) tool is excellent for converting YouTube channels to RSS feeds, but it requires:
- Setting up a YouTube Data API key
- Installing Python dependencies  
- Running the tool for each channel

This repository eliminates that barrier by providing pre-generated RSS feeds that you can use directly in your favorite RSS reader.

## 🚀 Quick Start

1. Browse the available feeds in the [`feeds/`](feeds/) directory
2. Copy the raw GitHub URL of any RSS file
3. Add it to your RSS reader

**Example URL format:**
```
https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/tech/sample_tech_channel.xml
```

**Available feeds:**
- Tech: [Sample Tech Channel](https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/tech/sample_tech_channel.xml)
- Maker: [DIY Workshop](https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/maker/diy_workshop.xml) 
- Science: [Science Explained](https://raw.githubusercontent.com/cdibona/opensaucerssfeeds/main/feeds/science/science_explained.xml)

## 📁 Organization

Feeds are organized by category in the `feeds/` directory:
- `tech/` - Technology, programming, and software development channels
- `maker/` - DIY, woodworking, and maker project channels  
- `science/` - Educational science and research channels
- `educational/` - General educational content
- `entertainment/` - Entertainment and gaming channels

See the [feeds README](feeds/README.md) for a complete catalog of available feeds.

## 🔄 Updates

Feeds are updated periodically, but there's no guaranteed schedule. For the most current content, consider using the [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker) tool directly.

## 🤝 Contributing

Want to add more channels? Contributions are welcome!

1. Fork this repository
2. Generate RSS feeds using [YoutubeRSSMaker](https://github.com/cdibona/YoutubeRSSMaker)
3. Add the XML files to the appropriate category directory
4. Update the feeds README with your new additions
5. Submit a pull request

## 📝 Feed Format

All feeds follow RSS 2.0 standards with Media RSS extensions, including:
- Video titles, descriptions, and links
- Publication dates
- Video duration, view counts, and likes
- Thumbnail images
- Channel metadata

## ⚠️ Disclaimer

These feeds are provided as-is and may not always be up-to-date. Channel availability and content can change at any time. This is an unofficial collection and is not affiliated with YouTube or any of the channel creators.

## 📄 License

This collection of RSS feeds is provided under the MIT License. Individual video content remains the property of the respective channel creators.
