all:
	kubectl create configmap -n mtg-fsdatasets --dry-run=client nginx --from-file=freesound_datasets.conf=freesound_datasets.conf -o yaml > nginx.yaml
	kubectl create configmap -n mtg-fsdatasets --dry-run=client local-settings --from-file=local_settings.py=local_settings.py -o yaml > local-settings.yaml
