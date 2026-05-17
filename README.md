# SHARP Lab Website

Last dev update: Oct 5, 2025

Domain: www.sharplabpdx.com \
Site generator: Jekyll 4.3 \
CMS: Decap 3.0 \
Deployed with: Netlify \
Package list: Gemfile \

## Installing the project

`bundle install`

## Running the dev server

`jekyll serve` \
Local server: http://127.0.0.1:4000/

### To serve to local network
Run the following command to get your mac's IP address: `ipconfig getifaddr en0`

Then run `jekyll s -H <device IP address> -P 8080` to set the jekyll server to that IP (port setting optional here.)

Then run `jekyll serve` as usual and go to `http://<ip address>:8080`.

**Note:** Decap local server did not work with this configuration when I tested it.

## Build testing

`jekyll build`

## Dependencies:

- jekyll-timeago
- Bootstrap 5.3
- Academic Icons CDN

## Fonts

Source Sans 3 (variable) \
Sintony (regular) \
Fjalla (regular) \
