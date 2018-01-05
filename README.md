Quora Question Pairs Shiny App
=====================================

Before running you need to download and unzip model and tokenizers
You can do it manually from Google Drive at this [link](https://drive.google.com/open?id=1t8gxe0C8IbN2XXa3qnChyPIYsAm03EmJ).

Or using the `googledrive` package:

```
library(googledrive)
drive_download(as_id("https://drive.google.com/open?id=1t8gxe0C8IbN2XXa3qnChyPIYsAm03EmJ/"))
unzip("model-quora-question-pairs.zip")
```

Tou can then click `Run Document` from ` app.Rmd`.