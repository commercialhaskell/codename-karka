# Changelog for rio

## Unreleased

* Expose `Data.Text.replace` and `Data.Text.Lazy.replace`

## 0.1.4.0

* Add `Const` and `Identity`
* Add `Reader` and `runReader`

## 0.1.3.0

* Add `newLogFunc` function to create `LogFunc` records outside of a callback scope
* Allow dynamic reloading of `logMinLevel` and `logVerboseFormat` for the `LogOptions` record
* Add `foldMapM`
* Add `headMaybe`, `lastMaybe`, `tailMaybe`, `initMaybe`, `maximumMaybe`, `minimumMaybe`,
  `maximumByMaybe`, `minimumByMaybe` functions to `RIO.List` module (issue #82)
* Move non partial functions `scanr1` and `scanl1` from `RIO.List.Partial` to `RIO.List` (issue #82)
* Add `SimpleApp` and `runSimpleApp`
* Add `asIO`

## 0.1.2.0

* Allow setting usage of code location in the log output

## 0.1.1.0

* Move some accidentally included partial functions

## 0.1.0.0

* Initial stable release

## 0.0

__NOTE__ All releases beginning with 0.0 are considered
experimental. Caveat emptor!
