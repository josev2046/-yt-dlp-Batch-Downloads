# yt-dlp Batch Downloads

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15249279.svg)](https://doi.org/10.5281/zenodo.15249279)

This repository illustrates how to download multiple URLs using the `yt-dlp` command-line tool with a batch file. **Please ensure you have the necessary rights or permissions from the copyright owner before downloading any content.**

![image](https://github.com/user-attachments/assets/a426350e-8a5c-4974-8076-6f9d2a76f3c9)


## Usage

1.  **Prepare a text file** (e.g., `urls.txt`) containing a list of URLs to download, one URL per line. For example:

    ```text
    [https://example.com/video1](https://example.com/video1)
    [https://example.com/video2](https://example.com/video2)
    [https://example.com/another/video](https://example.com/another/video)
    ```

2.  **Execute `yt-dlp`** with the `-a` or `--batch-file` option, pointing to your text file:

    ```bash
    yt-dlp -a urls.txt
    ```

    or

    ```bash
    yt-dlp --batch-file urls.txt
    ```

`yt-dlp` will then process each URL in the `urls.txt` file sequentially.


## Further Information

Refer to the [yt-dlp documentation](https://github.com/yt-dlp/yt-dlp) for more advanced options and configurations.
