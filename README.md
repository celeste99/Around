# Around

A Cloud and React based Social Network - Backend Implementation

1. Launched a scalable web service in Go to handle posts and deployed to Google Cloud (GAE flex) 
2. Used ElasticSearch (GCE) to provide geo-location-based search functions such that users can search nearby posts within a      distance (e.g. 200km)
3. Utilized Google Dataflow to dump daily posts to a BigQuery table for offline analysis (keyword-based spam detection)
4. Used Google Cloud ML API and Tensorflow to train a face detection model and integrate with the Go service
