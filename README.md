# dchousing

Project to consider best housing options given a work location.  Should generate a heatmap based upon the following variables for most if not all of DC.  There's a little weirdness where highways travel over city streets because I didn't specify which it was starting from, but otherwise interesting results.

Create a file with your config options in `config.json`
```json
{
          "gmap_key": "<insert_gmap_key>",
          "forwork": [7, 0, 0],
          "forhome": [15, 0, 0],
          "work_address": "<Work address>"
}
```
 * `gmap_key`: your google map api key
 * `forwork`: what time you leave for work
 * `forhome`: what time you return for home
 * `work_address`: where you work

