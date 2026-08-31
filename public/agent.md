# Agent Notes

## GomiHub municipality page URLs

- Individual GomiHub municipality pages under `gomihub/municipality/` use the format `{5-digit-municipality-code}-{short-romaji-slug}.html`.
- The municipality code is the primary stable identifier. The romaji slug is only for readability.
- Do not use sequential numbers or Japanese filenames for new municipality pages, because future additions can make sequential URLs unstable and Japanese filenames are less convenient operationally.
- For municipality code matching, use the Ministry of Internal Affairs and Communications nationwide local government code source page, and the public JSON conversion of that data:
  - https://www.soumu.go.jp/denshijiti/code.html
  - https://github.com/nojimage/local-gov-code-jp
- When adding or regenerating pages, update all of the following together:
  - `gomihub/index.html`
  - files under `gomihub/municipality/`
  - `sitemap.xml`
  - canonical and Open Graph URLs inside each municipality page
