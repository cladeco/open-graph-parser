# open-graph-parser [![CircleCI](https://circleci.com/gh/cladeco/open-graph-parser.svg?style=shield&circle-token=b37ac9febd540869e72c485d864605dcbaf2b820)](https://circleci.com/gh/cladeco/open-graph-parser)

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
