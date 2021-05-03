# dictybase footer specification

There are two footer JSON files. `footer.json` contains the data for the old
sitemap-style footer. `footer-condensed.json` is for the more recent condensed
version of the DCR footer.

The default is to use JSON, but the YAML output can also beused for ease of editing.

## json -> yaml

- Install python
- Install pyaml `pip install pyaml`
- Run `$_> cat footer.json | python -m pyaml > footer.yaml`

## yaml -> json

Just the opposite of `json -> yaml`, like directions in Google Maps.
