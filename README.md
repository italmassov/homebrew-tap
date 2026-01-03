# Homebrew Tap (Template)

This folder contains a ready-to-publish Homebrew tap layout.

## How to publish
1) Create a new repo, for example: `italmassov/homebrew-tap`.
2) Copy this folder's contents into the new repo root.
3) Edit `Casks/blockableplayer.rb` and replace:
   - `__URL__` with your GitHub Release zip URL
   - `__SHA256__` with the zip SHA256
   - `__HOMEPAGE__` with your project page
4) Commit and push.

## Install (for users)
```
brew tap italmassov/tap
brew install --cask blockableplayer
```
