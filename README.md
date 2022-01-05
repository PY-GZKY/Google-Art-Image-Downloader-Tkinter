
# Google-Art-Image-Downloader-Tkinter

由 [google-art-downloader](https://github.com/mewforest/google-art-downloader)
整改的批量 Google 艺术展平台高清图片下载

---

![screenshot](https://user-images.githubusercontent.com/15357833/144015262-a51e5260-7d81-40eb-b106-9faa9fc5ae1b.png)

⭐ It works perfectly from 2018 year till today, thanks for stars!

---

## Usage

1. Just download a zip archive with binaries from [releases](https://github.com/mewforest/google-art-downloader/releases), unzip it to any
folder and run **google-art-downloader.exe**.
2. Use button **"Paste url"** or `CTRL+V` to paste your url and click **"Download"** to start the image processing.

See [Running with Python](#running-with-python) section, if are running on Linux or macOS.

## Requirements

Compiled release requires just connection to the Internet and Chrome installed (should be added in PATH).

## Running from the source

### <a name="running-with-python"></a> Running with Python

> This method is also suit for you if you don't use Windows.

If you want co compile your own version or use it without downloading compiled files:

1. Install Python 3.8+ and add interpreter to PATH
2. Install Google Chrome or Chromium and add executable to PATH
3. Install all project dependencies:
   ```shell
   python -m pip install -r requirements.txt
   ```
4. **Only for Linux and MacOS**: be sure you make webdrivers from `bin` executables.
   - Linux:
    ```shell
    chmod +x bin/chromedriver_linux64/chromedriver
    ```
    - MacOS:
    ```shell
    chmod +x bin/chromedriver_mac64/chromedriver
    ```
5. Done! You have to just run a script:
    ```shell
    python GoogleArtDownloader.py
