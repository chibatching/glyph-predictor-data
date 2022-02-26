# glyph-predictor-data

Glyph sequence and shape data for [Glyph predictor](https://play.google.com/store/apps/details?id=com.chibatching.glyphpredictor)

Sometime one glyph has multiple name, but in these data file only one name should be used.

## Glyph lines data

`glyph_line.csv` is data of glyph shape.
Data format is below.
```csv
name,shape(using 0..9 and a)
```

<img src="https://user-images.githubusercontent.com/7804631/155848043-ace3f806-b16d-4bba-8348-808f8aa3253d.png" width=400 />

## Glyph sequence data

`glyph.csv` is sequence data.
We have to use only the name in `glyph_line.csv`

## Contributing

If you want to report or add new sequence or shape, please make issue or pull request.

**Important** Be sure to attach a screenshot to ensure the accuracy of the information.
