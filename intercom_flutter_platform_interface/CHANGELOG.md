# Changelog

# 1.1.0

- Added method `loginIdentifiedUser` with `IntercomStatusCallback` support.
- Deprecated `registerIdentifiedUser` in favor of `loginIdentifiedUser`.
- Added method `loginUnidentifiedUser` with `IntercomStatusCallback` support.
- Deprecated `registerUnidentifiedUser` in favor of `loginUnidentifiedUser`.
- Added parameter `statusCallback` in `updateUser` to support `IntercomStatusCallback`.
- Renamed the following methods in the MethodChannel:
    - `registerIdentifiedUserWithUserId` to `loginIdentifiedUserWithUserId`.
    - `regsiterIdentifiedUserWithEmail` to `loginIdentifiedUserWithEmail`.
    - `registerUnidentifiedUser` to `loginUnidentifiedUser`.

# 1.0.1

- Added API documentation.

# 1.0.0

- displayCarousel
- displayArticle

# 0.0.1

- Initial open source release