# [Concatenate Video Files in Python]
To run this:
- `pip3 install -r requirements.txt`
```
    $ python merge_video.py --help
```
**Output**:
```
    usage: merge_video.py [-h] [-c CLIPS [CLIPS ...]] [-r REDUCE] [-o OUTPUT]
    Simple Video Concatenation script in Python with MoviePy Library
    optional arguments:
    -h, --help            show this help message and exit
    -c CLIPS [CLIPS ...], --clips CLIPS [CLIPS ...]
                            List of audio or video clip paths
    -r REDUCE, --reduce REDUCE
                            Whether to use the `reduce` method to reduce to the lowest quality on the resulting clip
    -o OUTPUT, --output OUTPUT
                            Output file name
```
- Sample command to merge multiple files `file1.mp4` and `file2.mp4` to produce `output.mp4`:
```
    $ python merge_video.py -c file1.mp4 file2.mp4 -o output.mp4
```
