# Stocks

Demo app for the material design widgets and other features provided by Flutter.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer/)

Clicking the button above will open this repository in Gitpod, a fully-featured dev environment running in your browser.

### Building and installing the stocks demo app

* `cd $FLUTTER_ROOT/examples/stocks`
* `flutter pub get`
* `flutter run --release`

The `flutter run --release` command both builds and installs the Flutter app.

## Internationalization

This app has been internationalized (just enough to show how it's
done). It's an example of how one can do so with the
[Dart intl package](https://pub.dev/packages/intl).

The [Flutter Internationalization Tutorial](https://flutter.dev/tutorials/internationalization/)
covers Flutter app internationalization in general.

See [regenerate.md](lib/i18n/regenerate.md) for an explanation
of how the Dart internationalization tools, like
`intl_translation:generate_from_arb`, were used to generate
localizations for this app.

## Icon

Icon was created using Android Asset Studio:
https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=image&foreground.space.trim=0&foreground.space.pad=0&foreColor=607d8b%2C0&crop=0&backgroundShape=square&backColor=fff%2C100&effects=none

From this clipart:
https://openclipart.org/detail/30403/tango-go-up
Which is public domain.
