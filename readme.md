# Traffic anomaly detection
In this project, we took a stab at building various models on a large (8GB) dataset that records traffic events across the US from August 2016 to Jan 2021. In addition to preprocessing, I worked on building an isolation forest to identify anomalous traffic events.

The notebook in the repo was used to test code with a subsample of data (~1M records). The code was later applied to the entire dataset on an AWS EMR cluster, with buffed up specs (so we don't dry up waiting).

The original dataset can be downloaded here: https://smoosavi.org/datasets/lstw