# All images

This repository hosts a simple script, written in JavaScript for the convenience of viewing, that generates every image possible within the provided resolution and color bit depth constraints.

**View the [live demo](https://nurgak.github.io/all-images/) here.**

[![All images](all-images.png)](https://nurgak.github.io/all-images/)

Depending on the settings and iteration speed, the time to finish generating all the combinations might take more or less than the [heat death of the universe](https://en.wikipedia.org/wiki/Heat_death_of_the_universe).

There is no point to it. Enjoy.

## Usage

Set the resolution, color bit depth, color channels and hit run.

Example of a 2x2, 2-bit, 1-channel (black/white) image combinations (256 possibilities).

![All images, 2x2, 1-bit, 1-channel](all-images_2x2_2b_1c.png)

## Known issues

At this time, because of the way the image is encoded, the script can only deal with a maximum image size where the encoded image is represented by a number using less than 1024-bits (maximum value is 2^1024-1). The maximum value depends on the configuration.

## License

This script is published under [MIT license](LICENSE).
