# Training results archive

Analysis reports and their extracted history from
https://github.com/riverside234/brass-birmingham-ai .

This repository is checked out independently at `results/` in the code project;
it is not a Git submodule. The code exporter commits and pushes new bundles here.
Incremental exports require the earlier bundles named in `export-manifest.json`.
Do not remove those dependencies. Checkpoints and replay caches are not reports.
Historical files retain their original Git blob contents. New files use `-text`
attributes so report hashes remain independent of platform line-ending settings.
