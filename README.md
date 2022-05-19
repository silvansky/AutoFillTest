# `UITextField` AutoFill bug demo

## Storyboard setup

Each textfield is placed in its own `UIViewController`. These controllers are embedded in the main one via segues.

`textContentType` of fields is set to `.username` and `.password`.

## Result

When I invoke AutoFill feature only first textfield is filled.

## Simple layout

The second screen in example is simplified and works correctly.
