# spark-event-corpus-data

Pure data: Spark event logs generated or fetched by
[spark-event-corpus](https://github.com/shuffle-works/spark-event-corpus).
Every commit is tagged per generation run (`vYYYY-MM-DD`). Consumed by
sparkforensics as a pinned git submodule tag, and by spark-event-corpus's own
`index.json` catalog, which is the source of truth for which tag a given
log lives at.
