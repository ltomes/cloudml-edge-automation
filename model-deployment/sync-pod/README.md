This is to build a container for using gcloud commands on an arm architecture
device.

From this directory:

	gcloud builds submit . --config=cloudbuild-x86_64.yaml
	gcloud builds submit . --config=cloudbuild-armv7l.yaml


