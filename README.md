# Chameleon-Cloud-Anomaly-Detection

This Repo contains the inststructions to use Chameleon Outage data for ML based anomaly detection.

Please doenload the data from this bucket: https://chi.uc.chameleoncloud.org:7480/swift/v1/AUTH_4140e5f9f65545dbb9f0bdc90ef68d23/chameleon_usage_metrics_public_share/

The training data is overall 16GB and is split into 4 tar.gz files, which need to be combined:
``` cat training_data.tar.gz.part_* > training_data.tar.gz ``` can be used to combine all 4 files into one.

