# Google Analytics 4 (GA4) Data API with Python

Important links:
1. Google Quickstart guide: https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries
2. API dimensions and metrics: https://developers.google.com/analytics/devguides/reporting/data/v1/api-schema
3. Google developer's guides: https://developers.google.com/analytics/devguides/reporting/data/v1/rest/v1beta/properties
https://googleapis.dev/python/analyticsdata/latest/data_v1beta/beta_analytics_data.html

The overview of the process:
1. Get API keys: create a GCP project, authorize Google Analytics Data API, create a service account, create JSON keys for the account.
2. Add service account as a viewer to your GA4 propert(Admin->User Management) 
3. Install google-analytics-data package.
4. Set os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = 'your_api_key.json'
5. Send request, get output. Done!
