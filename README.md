# join-screenshots

Static mirror of [Join Screenshots](https://join-screenshots.zhanghai.me/) — join multiple movie-subtitle screenshots into one image, entirely in the browser.

- Original author: [zhanghai](https://github.com/zhanghai/JoinScreenshots)
- This mirror only rewrites asset paths to relative URLs (so it works on a GitHub Pages project subpath) and drops the original analytics scripts. The application code is unchanged.

## Local preview

```bash
python -m http.server 8000
```

Then open http://localhost:8000/

## Notes

- The tool runs fully client-side (canvas); no backend is required.
- Assets keep their original content-hashed filenames.
