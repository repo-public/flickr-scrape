# Scrape flickr

## Installation

1. Clone the repo

2. Create a virtualenvironment

```
virtualenv env
source env/bin/activate
```

3. Install requirements

`pip install -r requirements.txt`

## Usage

`python scraper.py --search "SEARCH TERM" --bbox minimum_longitude,minimum_latitude,maximum_longitude,maximum_latitude`

`This searches for images of flowers and will download as many as possible:
python scraper.py --search "flowers"`

`This searches for images of cats, but will only download the first 3 pages of results:
python scraper.py --search "cats" --max-pages 3`

`This searches for images of dogs with a geographic region:
python scraper.py --search "dogs" --bbox 40.851928,-74.3030917,0.5239146,-73.709836`
