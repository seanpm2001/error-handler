# Yii Error Handler Change Log

## 3.1.0 under development

- New #87: Add `CompositeException` to be able to render multiple exceptions (@xepozz)
- Bug #87: Fix a bug with try/finally from #75 (@xepozz)
- Chg #75: Dispatch `ApplicationError` in `ErrorCatcher` (@xepozz)
- Enh #82: Add `HeadersProvider` (@xepozz)
- Enh #86: Add color scheme definition based on system settings (@dood-)

## 3.0.0 February 14, 2023

- Chg #64: Raise PHP version to `^8.0` (@vjik, @xepozz)
- Chg #72: Adapt configuration group names to Yii conventions (@vjik)
- Enh #65: Explicitly add transitive dependencies `ext-mbstring`, `psr/http-factory` and
  `psr/http-server-handler` (@vjik)

## 2.1.1 January 26, 2023

- Bug #70: Prevent duplication of throwable rendering (@vjik)

## 2.1.0 June 15, 2022

- Enh #54: Add shutdown event, fix cwd (@rustamwin)
- Enh #55: Defer exit on terminate (@rustamwin)
- Enh #57: Add markdown support for friendly exception solutions (@vjik)
- Enh #58: Add support for `2.0`, `3.0` versions of `psr/log` (@rustamwin)

## 2.0.2 February 04, 2022

- Bug #50: Fix JSON rendering on JSON recursion exception (@thenotsoft)

## 2.0.1 January 26, 2022

- Bug #49: Fix JSON rendering of non-UTF-8 encoded string (@devanych)

## 2.0.0 November 09, 2021

- Chg #48: Transfer `HeaderHelper` to `yiisoft/http` package (@devanych)
- Enh #45: Improve appearance of solution from friendly exceptions (@vjik)

## 1.0.0 May 13, 2021

Initial release.
