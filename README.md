# Doing some route planning with OSMNX for running

Don't know what I am doing FYI.

## Results

### Low High Route

![Hills around pirates](./site/hills-pirates.html)

## Resources

For OSMNX docs and good examples https://osmnx.readthedocs.io/en/stable/index.html

## Setup

### Docker for jupiter notebook

This is the easiest way to get the jupiter notebook up and running. Don't need to install anything on your local machine. Assuming you have docker installed.

I had trouble with some of the dependencies on my mac so the osmnx jupiter container is great. 

```bash
docker-compose up
```
http://localhost:8888/lab

<!-- ### Local setup
I need to clean up the dependancies and requirements.txt file before this will work.
```bash
python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt
``` -->