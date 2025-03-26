TypeScript type definitions for InnerTube (YouTube Internal API)

## Installation

```sh
npm install youtubei-dts
```

## Usage

```typescript
import type youtubei from 'youtubei-dts';
import { Innertube } from 'youtubei.js';

const innertube = await Innertube.create();
const playerResponse = await innertube.actions.execute('/player', { videoId: 'CsyYVkf6oC0' });
const responseData = playerResponse.data as youtubei.IYoutubeApiInnertubePlayerResponse;
console.log(responseData);
```

## License
Distributed under the [MIT](./LICENSE) License.

<p align="right">
(<a href="#top">back to top</a>)
</p>