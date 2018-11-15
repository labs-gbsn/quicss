# Quicss
Quicss is a compact CSS framework made to quicken one's front-end development.

## Installation
Link the minified file [quicss.min.css](#) before your custom styles.

```html
<link rel="stylesheet" type="text/css" href="quicss.min.css">
```

## Available classes
| Class name          | Element | Observations                                                                                   |
|---------------------|---------|------------------------------------------------------------------------------------------------|
| .no-style           | a       | Removes the color and underline of any hyperlink tag.                                          |
| .no-style.underline | a       | Removes the color but keeps the underline of any hyperlink tag.                                |
| .light              | *       | Makes font-weight lighter.                                                                     |
| .boldest            | *       | Makes font-weight boldest.                                                                     |
| .hidden             | *       | Sets display: none;                                                                            |
| .text-white         | *       | Sets text color to white.                                                                      |
| .text-inherit       | *       | Sets text color to inherit.                                                                    |
| .small-text         | *       | Sets font size to a smaller size.                                                              |
| .normal-text        | *       | Sets font size to the default size.                                                            |
| .big-text           | *       | Sets font size to a bigger size.                                                               |
| .no-margin          | *       | Removes margins.                                                                               |
| .no-overflow        | *       | Hides overflows.                                                                               |
| .no-overflow-x      | *       | Hide horizontal overflow.                                                                      |
| .no-overflow-y      | *       | Hide vertical overflow.                                                                        |
| .overflow           | *       | Sets overflows to auto.                                                                        |
| .overflow-x         | *       | Sets horizontal overflow to auto.                                                              |
| .overflow-y         | *       | Sets vertical overflow to auto.                                                                |
| .no-shrink          | *       | Sets flex-shrink property to 0.                                                                |
| .transit-1          | *       | Adds a transition to all properties with a duration of 100 milliseconds and easing in and out. |
| .transit-2          | *       | Adds a transition to all properties with a duration of 200 milliseconds and easing in and out. |
| .op-0               | *       | Sets opacity to 0.                                                                             |
| .op-50              | *       | Sets opacity to 0.5.                                                                           |
| .op-67              | *       | Sets opacity to 0.67.                                                                          |
| .op-100             | *       | Sets opacity to 1.                                                                             |
| .ellipsis           | *       | Makes element overflow with ellipsis.                                                          |
| .cursor-default     | *       | Sets the cursor type to default.                                                               |
| .cursor-pointer     | *       | Sets the cursor type to pointer.                                                               |
| .no-resize          | *       | Disables resize.                                                                               |

## CSS Resetting
Quicss provides minimal CSS normalization and resetting.
Quicss incorporates the most important features of [normalize.css](https://github.com/necolas/normalize.css/).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
(The MIT License)

Copyright (c) 2018 Labs by GBSN Research <labs@gbsnresearch.com>