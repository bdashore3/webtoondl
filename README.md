# webtoondl

This is for EDUCATIONAL purposes ONLY! Please respect the creators of these comics and DO NOT
repost them on any other website. I am not responsible for any legal trouble that you go through.

`npm i -g webtoondl`

```
Replace webtoondl script from npm to the one from this repository
$ webtoondl --comic=1022 --out=lumine/ --pdf
Comic Selected: LUMINE (Drama) by Emma Krogell
Indexing Episodes [========================================] 100% | ETA: 0s | Episode 35/35
Downloading to /home/snek/documents/comics/lumine
Downloading Episode 1 [========================================] 100% | ETA: 0s | Panel 42/42
Downloading Episode 2 [========================================] 100% | ETA: 1s | Panel 36/36
Downloading Episode 3 [========================================] 100% | ETA: 1s | Panel 48/48
Downloading Episode 4 [==============================----------] 75% | ETA: 0s | Panel 33/45
```

### Options

- `--comic` comic id from webtoons
  - in `http://www.webtoons.com/en/challenge/lumine/list?title_no=1022` the comic id is `1022`
- `--out`: defaults to cwd
- `--pdf`: output pdfs of the episodes instead of folders with images (may come out weird depending on the comic)
