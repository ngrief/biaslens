# BiasLens

**Analyze media articles for bias, emotion, and loaded language**

BiasLens is a client-side web tool that helps you understand how articles are framed through language analysis. It doesn't determine what's "true" or "false" — instead, it shows you the linguistic patterns, emotional content, and framing techniques used in the text.

## Features

- **Sentiment Analysis** - Detects positive, negative, and neutral language
- **Emotional Intensity** - Identifies emotionally charged words
- **Loaded Language Detection** - Highlights biased framing (positive/negative)
- **Fact vs Opinion Analysis** - Estimates the ratio of factual to opinion-based statements
- **Interactive Highlighting** - Visual color-coding of bias indicators
- **8 Example Articles** - Test the tool with diverse pre-loaded examples

## How It Works

BiasLens uses:
- **compromise.js** for natural language processing
- **AFINN-based sentiment lexicon** for sentiment scoring
- **Pattern matching** for loaded language detection
- **Heuristic analysis** for fact vs opinion classification

Everything runs client-side in your browser — no data is sent to any server.

## Usage

1. Visit the [live demo](#) (GitHub Pages link)
2. Paste an article or news text into the input area
3. Click "Analyze Article"
4. Review the sentiment breakdown, metrics, and highlighted text

## Technologies

- Pure HTML/CSS/JavaScript
- compromise.js NLP library
- GitHub Pages hosting

## License

MIT
