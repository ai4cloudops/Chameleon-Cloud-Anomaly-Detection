# Chameleon-Cloud-Anomaly-Detection

This repository contains instructions for using Chameleon Cloud outage data for machine learning–based anomaly detection.

Please download the dataset from the following public bucket:
https://chi.uc.chameleoncloud.org:7480/swift/v1/AUTH_4140e5f9f65545dbb9f0bdc90ef68d23/chameleon_usage_metrics_public_share/

The training dataset is approximately 16 GB and has been split into four .tar.gz parts for easier distribution. To reassemble the full archive, run the following command:

```cat training_data.tar.gz.part_* > training_data.tar.gz```

Once combined, you can extract the contents using:

```tar -xvzf training_data.tar.gz```
