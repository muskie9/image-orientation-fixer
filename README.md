# Image Orientation Fixer
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/salted-herring/image-orientation-fixer/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/salted-herring/image-orientation-fixer/?branch=master)

## Description
Have you ever come across the moments like below:

## What does this module do?
Automactially rotate the image that you upload to SilverStripe CMS, based on its orientation value stored in the exif data.

## Install
The module can be installed via composer:
```bash
composer require salted-herring/silverstripe-standard-permissions
```
After composer has downloaded the directory, go to your SilverStripe website, and in browser's addres bar, attache "?flush=all" to the existing URL, and then hit "Enter"

## Usage
Usage? What usage? Once you have done the installation, it's ready to go -- upload an image with orientation (simply, any portrait orientation photo taken by iPhone), and check if the thumbnail is resampled in the right orientation.

So, have fun coding :)