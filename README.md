# irisexample

gcloud ml-engine local train --module-name trainer.iris --package-path trainer
gcloud ml-engine jobs submit training iris1 --module-name trainer.iris --package-path trainer --staging-bucket bucketname --region regionname --runtime-version 1.8
