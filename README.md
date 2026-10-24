# fecdash

Data releases for the FEC candidate dashboard at https://jessebrandt.com/fec/ (forthcoming).

Each release holds per-candidate aggregates of FEC individual-contribution bulk data, built by the maintainer's private pipeline.

## Assets

- `fecdash-site.tar.gz`: the dashboard page (`index.html`, `app.js`, ...) at the archive root and the data tree under `data/`.
- `fecdash-data.tar.gz`: the data tree alone, with `manifest.json` and one folder per cycle (`2026/...`) at the archive root.

## manifest.json

The manifest is also the release notes.

- `data_as_of`: the date of the latest FEC bulk data the release covers.
- `fetched_at`: when the pipeline downloaded those files from the FEC.

## FEC notice

Information about individual contributors taken from FEC reports cannot be sold or used for soliciting contributions or for commercial purposes.
