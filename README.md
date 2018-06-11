# ColorMotion dataset

The dataset is built from videos with permissive licences (mostly open source movies).

In the dataset, each video is identified by a hash. The hash is computed over the first 32KiB of the video ([source code](https://github.com/ColorMotion/ColorMotion/blob/150a4be41009ce8661026d157f238b28ff896dc8/colormotion/dataset.py#L13-L16)). It should be used to verify if the downloaded file is the same used when building the dataset.

| Video | Download page | Hash | Metadata |
|-------|---------------|------|----------|
| Tears of Steel | [New version (4k rendered) - HD](https://mango.blender.org/download/) | 3da6f3053e50b704bca44da452f01643535259a7 | [tears-of-steel.json](metadata/tears-of-steel.json) |
| Valkaama | [Valkaama HD - 720p](http://www.valkaama.com/index.php?page=valkaama&l=en) | d048ba7479562dc188c85a72c92ca57e18a4c3b0 | [valkaama.json](metadata/valkaama.json) |
