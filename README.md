# joaodavil4.github.io

Public pages for apps whose source is private: privacy policies and support.

- Morf: `/Morf/privacy/` (Play Console and App Store privacy policy URL), `/Morf/support/` (support URL).
- Zibao: `/Zibao/privacy/` (linked from the app's `LegalLinks.swift` and App Store Connect), `/Zibao/support/` (App Store support URL).
- Nhoco: `/Nhoco/privacy/` (Google Play privacy policy URL; en/pt/es on one page).

Keep these paths stable: shipped builds link to them.

## Adding an app

1. Add it to `_data/apps.yml` (name, tagline, platforms, accent colours).
2. Add `_includes/icon-<Slug>.svg`.
3. Add `<Slug>/index.md` (`layout: app`), `<Slug>/privacy/index.md` and `<Slug>/support/index.md` (`layout: doc`), each with `app: <Slug>`.

Design lives in `_layouts/` and `assets/site.css`; dark mode follows the system.
