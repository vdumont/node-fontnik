# 0.4.3

- Handle `ft_face->style_name` null value in `RangeAsync`.

# 0.4.2

- Handle `ft_face->style_name` null value in `LoadAsync`.

# 0.4.1

- Publish Node.js v5.x binaries.
- Autopublish binaries on git tags.

# 0.4.0

- Fixes bounds for short ranges.
- Fixes Travis binary publishing.
- Adds Node.js v4.x support.

# 0.2.6

- Truncate at Unicode point 65535 (0xFFFF) instead of 65533.

# 0.2.3

- Calling .codepoints() on an invalid font will throw a JavaScript
  error rather than running into an abort trap.
