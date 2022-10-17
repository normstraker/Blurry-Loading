# Blurry Loading

https://normstraker.github.io/Blurry-Loading/

- Blurred background clears while percent counter counts to 100

## CSS

- background: url() no-repeat center top/cover
- position: absolute;
- width: calc(100vw + 60px);
- height: calc(100vh + 60px);
- filter: blur();

## Javascript

- querySelector()
- setInterval()
- clearInterval()
- .innerHTML
- .style.opacity
- .style.filter
- Stackoverflow result;
  const scale = (num, in_min, in_max, out_min, out_max) => {
  return ((num - in_min) \* (out_max - out_min)) / (in_max - in_min) + out_min;
  };
