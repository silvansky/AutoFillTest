# `UITextField` AutoFill bug demo

## Storyboard setup

Each textfield is placed in its own `UIViewController`. These controllers are embedded in the main one via segues.

`textContentType` of fields is set to `.username` and `.password`.

![Storyboard][storyboard]

## Result

When I invoke AutoFill feature only first textfield is filled.

![Screen 1][screen1]
![Screen 2][screen2]
![Screen 3][screen3]

## Simple layout

The second screen in example is simplified and works correctly.

![Simplified layout][simplified]

![Screen 4][screen4]
![Screen 5][screen5]


[storyboard]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/storyboard.png
[simplified]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/simplified.png
[screen1]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/screen1.png
[screen2]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/screen2.png
[screen3]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/screen3.png
[screen4]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/screen4.png
[screen5]: https://raw.githubusercontent.com/silvansky/AutoFillTest/main/Images/screen5.png
