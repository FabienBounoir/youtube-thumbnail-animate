# youtube-thumbnail-animate
---

Get the animated thumbnail url with the youtube video Id 

### Module

```js
const fetchAnimatedThumbnail = require("youtube-thumbnail-animate");
(async () => {
  const url = await fetchAnimatedThumbnail("ujKpJc7dSpI");
  console.log(url);
  // https://i.ytimg.com/an_webp/ujKpJc7dSpI/mqdefault_6s.webp?du=3000&sqp=CMCmuqEG&rs=AOn4CLCaxae77RVTtZxQ9sJ2QRcrN83QCQ
})();
```