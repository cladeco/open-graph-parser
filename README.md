# open-graph-parser [![CircleCI](https://circleci.com/gh/cladeco/open-graph-parser.svg?style=shield&circle-token=0109c22092b2aae080e849d7d80c831d143640c9)](https://circleci.com/gh/cladeco/open-graph-parser)

A utility to extract Open Graph data from a URL.

## Installation

```shell
$ npm install --save @cladeco/open-graph-parser
```

## Usage

```javascript
import OpenGraphParser from '@cladeco/open-graph-parser'
const openGraphData = await OpenGraphParser.extractMeta(url)
```

## Credits

Uses code from [Osedea/react-native-opengraph-kit](https://github.com/Osedea/react-native-opengraph-kit)