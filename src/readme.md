
# gdrive-downloader

Download Google Drive folder and files.

## google-drive-folder-downloader

Repository basead on [google-drive-folder-downloader](https://github.com/segnolin/google-drive-folder-downloader)


## Getting Started

You need to enable the Drive API to use the script.
The enabling instructions can be found on [Python Quickstart](https://developers.google.com/drive/api/v3/quickstart/python).<br/>
The `credentials.json` file will be needed in the working directory.



## Open sourcecode directory
```
$ cd src/
```

### Using virtualenv

```
# Create virtual env to project on src folder
$ python -m venv gdrive_downloader_env

# Activate virtualenv
$ source gdrive_downloader_env/bin/activate

# Deactivate virtualenv
```

### Install dependencies
```
$ pip install -r requirements.txt --upgrade
```

## Basic Usage

Just run the script with **gdrive target folder name** and the **output path** (optional, default value is `./`) where you want to save to.

### Python 3.x

```
$ python3 gdrive_downloader.py gdrive_folder_name [output_path]
```