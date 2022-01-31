gcloud build submit --tag gcr. io/arboreal-cosmos-338023/continuous-deployment --project=arboreal-cosmos-338023

gcloud run deploy continuous-deployment --image gcr. io/arboreal-cosmos-338023/continuous-deployment --platform managed --project=arboreal-cosmos-338023 --allow-unauthenticated --region us-east1

