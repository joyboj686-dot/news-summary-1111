# World news summary, 11 November 2026

A make.fun entry: a small Node program that writes a single English summary of world news from Wednesday 11 November 2026 (under 2000 characters) to `/output/entry.txt`.

## Run

    node main.ts

Needs Node 22+ and only the standard library. The text lives in `summary.txt` and is copied to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

## Sources

AP, Al Jazeera, UN News, Reuters, NDTV, BLS (via Reuters), Washington Institute, CBS, ABC, Just Security, Yonhap.
