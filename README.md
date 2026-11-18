# Gamma Space vs Linear Light: Does Resampling in sRGB Actually Cost Quality?

Measured: resampling a 50/50 checkerboard in sRGB returns 127/255 where linear light returns 187/255 — a 60 code-value error. But on a real photo the same linear pipeline loses 0.98 dB. And the winner flips depending on which colour space you compute PSNR in.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-gamma-vs-linear-light/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
