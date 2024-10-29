# mentions-characterizations

This repo aims at collecting corrections to improve [Grobid](https://github.com/kermitt2/grobid) modules called [DataStet](https://github.com/kermitt2/datastet) and [SoftCite](https://github.com/softcite).
These corrections are usually submitted through the dedicated tool [Works magnet](https://github.com/dataesr/works-magnet/).

Each correction is recorded as an issue of this Github repository. This correction can be about the mention type (software, dataset or nothing) or about the characterization (used, created and / or shared).

A correction of the mention type set the corrected type in field `type` and the previous type in field `previousType`.

A correction of the characterization has its context in field `texts[0].text`. Then each characterization has its own entry in field `texts[0].class_attributes.classification`. And each of theses entries has it corrected value in field `value` and the previous value in field `previousValue`. As it is a human correction, it is supposed to be 100% sure, so score will always be 1.

A `user` field is always provided but is encrypted to preserve user anonimity.
