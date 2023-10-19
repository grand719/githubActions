# githubActions
| name                     | description                                                                | required | type                   | default |
| ------------------------ | -------------------------------------------------------------------------- | -------- | ---------------------- | ------- |
| `children`               | Any component that you'd like to apply infinite scrolling / marquee effect | YES      | `React.ReactNode`      | 1       |
| `speed`                  | Animation speed                                                            | NO       | `number`               | 1       |
| `spacing`                | Spacing between repeting elements                                          | NO       | `number`               | 0       |
| `style`                  | View style to be applied to Marquee container.                             | NO       | `StyleProp<ViewStyle>` |         |
| `animate`                | Turns animation on and off .                                               | NO       | `boolean`              | true    |
| `animateWhenContentFits` | Defines wether Marquee should animate when content fits.                   | NO       | `boolean`              | true    |
