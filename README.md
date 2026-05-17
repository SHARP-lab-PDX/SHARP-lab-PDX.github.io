# SHARP Lab Website

Last dev update: Oct 5, 2025

Domain: www.sharplabpdx.com \
Site generator: Jekyll 4.3 \
CMS: Decap 3.0 \
Deployed with: Netlify [![Netlify Status](https://api.netlify.com/api/v1/badges/79e14001-2650-411a-8caa-f11d86680cda/deploy-status)](https://app.netlify.com/projects/sharplabpdx/deploys)\
Package list: Gemfile 

## Installing the project

`bundle install`

## Running the dev server

`jekyll serve` \
Local server: http://127.0.0.1:4000/

### To serve to local network
Run the following command to get your mac's IP address: `ipconfig getifaddr en0`

Then run `jekyll s -H <device IP address> -P 8080` to set the jekyll server to that IP (port setting optional here.)

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
Fjalla (regular) 
