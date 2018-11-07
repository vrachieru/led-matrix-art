<p align="center">
    <img src="https://user-images.githubusercontent.com/5860071/48146455-b1885b80-e2bd-11e8-87c0-0185c7bf8431.png" width="200px" />
</p> 

## Gallery

Please use the [gallery](https://vrachieru.github.io/pixel-art/) to browse through the items in this repository.

## Format

```
{
    "name": "string",        // item name
    "category": "string",    // category name
    "size": "int x int",     // item size (rows x columns)
    "is_bw": boolean,        // has bw definition
    "is_rgb": boolean,       // has rgb definition
    "is_animation": boolean, // is animation (frames > 1)
    "frames": {
        "bw": [
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1],
                [0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1, 0|1]
        ],
        "rgb": [
            [
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]],
                [[r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b], [r, g, b]]
            ]
        ]
    },
    "delays": [frame1_ms, frame2_ms, ...] // time in ms to display each frame
}
```

## License

MIT