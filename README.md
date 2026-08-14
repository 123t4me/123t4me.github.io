# 123t4me.github.io

GitHub Pages site serving **https://123t4me.com** — the public home for
Affiniti Group's legal and privacy documents.

This repository is PUBLIC by design. It exists so that certification
reviewers, Store customers, and preview testers can read these documents
without a GitHub login. Do not put anything here that is not meant to be read
by anyone.

## Layout

| Path | URL |
|---|---|
| `legal/privacy-policy/index.md` | https://123t4me.com/legal/privacy-policy/ |
| `legal/eula/index.md` | https://123t4me.com/legal/eula/ |
| `legal/preview-terms/index.md` | https://123t4me.com/legal/preview-terms/ |

`CNAME` holds the custom domain. **Deleting it unsets the domain** and the
site reverts to `123t4me.github.io`, breaking every published URL — including
the one in the Microsoft Store listing.

## These documents are canonical HERE

The privacy policy previously lived at `docs/privacy-policy/index.md` in the
private `speakeasy` repo. Keeping a second copy there would let the published
policy and the internal one drift apart — and a privacy policy that does not
match the shipped behavior is not a bug, it is a misrepresentation. The copy
in `speakeasy` should be replaced with a link to the published URL.

## Version history

Git history is the archive. If it is ever necessary to show what the policy
said on a given date, that is what these commits are for. Do not rewrite
history in this repository.
