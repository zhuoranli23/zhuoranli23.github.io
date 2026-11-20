# Zhuoran Li

[Academic homepage](https://zhuoranli23.github.io/). Open `index.html` in a browser for a local preview. The page uses local fonts, figures, and scripts.

## CV

Edit `cv/main.tex` and the files in `cv/sec/`. To rebuild the PDF linked by the homepage, run these commands from the repository root.

```sh
build_dir=$(mktemp -d)
tectonic --outdir "$build_dir" cv/main.tex && cp "$build_dir/main.pdf" "files/Zhuoran Li - CV.pdf"
```

## Credits

The homepage adapts [Haolin Yang’s template](https://github.com/TidalHarley/TidalHarley.github.io). The CV uses [Cunchuan Huang’s Academic-LaTeX, CV/cv1](https://github.com/CunchuanHuang/Academic-LaTeX/tree/main/CV/cv1). Font and icon licenses are included alongside their assets. The PAW image is Figure 3 of the manuscript, “Learning to plan with the abstract world model.”
