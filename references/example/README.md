# Bundled fictional example

Three exports from an invented workshop contact workflow:

- `01-address-book.csv`: an earlier contact book, comma separated, UTF-8 BOM.
- `02-workshop-signups.csv`: a later signup list, semicolon separated.
- `03-follow-up.csv`: follow-up entries, tab separated.

Names, organisations, notes and dates are invented. Emails use reserved example
domains; all phones use North American fictional 555-01XX numbers. The files include
cross-export duplicate entries, missing details, changed email addresses, initials,
Chinese/pinyin names, organisation contacts, pasted headers and blank/placeholder
rows. Identical phone suffixes are intentionally possible across different people.

Run `--demo` to process these exact files. The three output artifacts are generated
at runtime rather than bundled. The README screenshot is a headless browser capture
of that real report, with its first merge already open.
