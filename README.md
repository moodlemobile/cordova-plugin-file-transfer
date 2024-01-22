# cordova-plugin-file-transfer (fork)

This is a fork of `cordova-plugin-file-transfer` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [apache/cordova-plugin-file-transfer](https://github.com/apache/cordova-plugin-file-transfer).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| - | Return headers along with the file entry when downloading a file |

You can see all the changes here: [1.7.1...moodlemobile:v1.7.1-moodle.8](https://github.com/apache/cordova-plugin-file-transfer/compare/1.7.1...moodlemobile:v1.7.1-moodle.8)

## Installation

You can install this package using the [original installation instructions](https://github.com/apache/cordova-plugin-file-transfer#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-file-transfer@1.7.1-moodle.8
```
