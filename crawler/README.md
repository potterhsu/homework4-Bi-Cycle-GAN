# Flickr Crawler


## Requirements

* yaml

    > pip install yaml

* flickrapi

    > pip install flickrapi


## Setup

* Create file `env.yaml` with following information:

    ```
    FLICKR_PUBLIC_KEY: xxx
    FLICKR_SECRET_KEY: xxx
    ```


## Usage

* Run a crawler, e.g.:

    ```
    $ python flickr_crawler.py suit --json_dir=./json --image_dir=./images
    ```
