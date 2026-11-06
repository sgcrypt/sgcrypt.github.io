# SG Crypt

Website for **SG Crypt — Cryptography Workshops in Singapore**.

Published at <https://sgcrypt.github.io/> using GitHub Pages and Jekyll.

## Apply this update

Copy the contents of this ZIP into the root of the existing
`sgcrypt/sgcrypt.github.io` repository, keeping the folder structure.
Overwrite files with the same paths. Leave all other files untouched.

The ZIP contains only the changed and new files, **not** a complete repository.
It preserves the existing workshop posts, talk abstracts, and PDFs.

## What changed

- Renames the website to SG Crypt, with a more descriptive subtitle.
- Shows 'SG Crypt 2027' as the homepage heading and removes the blog date/author.
- Lists previous posts by title instead of by publication date, excluding the
  current (newest) post.
- Preserves the former directions on a historical 2026 page and keeps the
  upcoming workshop venue unconfirmed.
- Adds small typography, table, and mobile-layout improvements.
- Replaces the old HTTP MathJax URL with an HTTPS link to MathJax 2.7.9.

## Maintenance notes

The homepage currently labels the upcoming edition **SG Crypt 2027**.
When announcing the next workshop, change that heading in `index.html`.
The 'Previous Editions' list assumes the newest `_posts` entry is the current
workshop. Keep the latest edition as the most recent dated post.

The title displayed for each previous edition comes from the corresponding
post's YAML `title:` field. To rename the old workshop in the archive to
'SG Crypt 2026', edit that post's front matter without changing its URL.

Existing talk abstracts were intentionally not rewritten; only the existing
program table's presentation is lightly improved.

## Preview

Run `bundle exec jekyll serve` if your local Jekyll setup is installed,
then open <http://localhost:4000/>.
