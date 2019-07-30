# Changelog

## 0.9.3

* Change how public URLs are set. Now must either pass nothing for automatic public URL generation, or pass an explicity URL including the subpath to the public folder.
* Do not lowercase all filenames
* Fix bad argument names that break with the admin GUI setup of asset manager storage providers

## 0.9.2

* Fix fieldnames for form validation


## 0.9.1

* Remove dependency on S3SDK (not feature complete enough). Use jets3t that comes with Lucee instead.

## 0.9.0

* First draft working storage provider