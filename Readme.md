
### 원본 깃허브
https://github.com/SimeonGriggs/tints.dev

### Usage
```scss

// Optional palette options
$paletteOption: (
    step: (50, 100, 200, 300, 400, 500, 600, 700, 800, 900), // default
    std: 500,            // reference step
    sat-tweak: 0.12,     // saturation adjustment
    light-min: 5,        // minimum lightness
    light-max: 98,       // maximum lightness
    use-light: true      // use lightness for distribution
);

// Generate palette
$colors: palette(#eb150d, $paletteOption);

// Result example (HSL Map)
$colors: (
    50:  hsl(0, 86%, 95%),
    100: hsl(0, 88%, 88%),
    200: hsl(0, 90%, 78%),
    300: hsl(0, 92%, 68%),
    400: hsl(0, 94%, 58%),
    500: hsl(0, 96%, 50%), // base color
    600: hsl(0, 94%, 44%),
    700: hsl(0, 92%, 36%),
    800: hsl(0, 90%, 28%),
    900: hsl(0, 88%, 20%)
);

```
