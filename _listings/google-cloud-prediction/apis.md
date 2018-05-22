---
name: Google Cloud Prediction
x-slug: google-cloud-prediction
description: Google Cloud Prediction API provides a RESTful API to build Machine Learning
  models. Predictions cloud-based machine learning tools can help analyze your data
  to add various features to your applications, such as customer sentiment analysis,
  spam detection, recommendation systems, and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Google Cloud Prediction
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Prediction API Predict Model
  x-api-slug: google-cloud-prediction-api
  description: Submit input and request an output against a hosted model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/hostedmodels/{hostedModelName}/predict
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecthostedmodelshostedmodelnamepredict-post-openapi.md
- name: Google Cloud Prediction API Train Model
  x-api-slug: google-cloud-prediction-api
  description: Train a Prediction API model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodels-post-openapi.md
- name: Google Cloud Prediction API List Models
  x-api-slug: google-cloud-prediction-api
  description: List available models.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/list
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelslist-get-openapi.md
- name: Google Cloud Prediction API Delete Model
  x-api-slug: google-cloud-prediction-api
  description: Delete a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsid-delete-openapi.md
- name: Google Cloud Prediction API Model Status
  x-api-slug: google-cloud-prediction-api
  description: Check training status of your model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsid-get-openapi.md
- name: Google Cloud Prediction API Add New Data
  x-api-slug: google-cloud-prediction-api
  description: Add new data to a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsid-put-openapi.md
- name: Google Cloud Prediction API Analyze
  x-api-slug: google-cloud-prediction-api
  description: Get analysis of the model and the data the model was trained on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}/analyze
  tags: Model,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-openapi.md
- name: Google Cloud Prediction API Predict
  x-api-slug: google-cloud-prediction-api
  description: Submit model id and request a prediction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}/predict
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/projecttrainedmodelsidpredict-post-openapi.md
- name: Google Cloud Prediction API
  x-api-slug: google-cloud-prediction-api
  description: Google Cloud Prediction API provides a RESTful API to build Machine
    Learning models. Predictions cloud-based machine learning tools can help analyze
    your data to add various features to your applications, such as customer sentiment
    analysis, spam detection, recommendation systems, and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Google Cloud Prediction
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-prediction/master/_listings/google-cloud-prediction/openapi.md
x-common:
- type: x-bugs
  url: https://cloud.google.com/prediction/docs/feedback_and_discuss
- type: x-change-log
  url: https://cloud.google.com/prediction/docs/release-notes
- type: x-code
  url: https://cloud.google.com/prediction/docs/libraries
- type: x-website
  url: https://cloud.google.com/prediction/docs/developer-guide
- type: x-documentation
  url: https://cloud.google.com/prediction/docs/
- type: x-faq
  url: https://cloud.google.com/prediction/docs/faq
- type: x-forum
  url: https://cloud.google.com/prediction/docs/general_discussion_forum
- type: x-getting-started
  url: https://cloud.google.com/prediction/docs/quickstart
- type: x-glossary
  url: https://cloud.google.com/prediction/docs/glossary
- type: x-pricing
  url: https://cloud.google.com/prediction/pricing
- type: x-sla
  url: https://cloud.google.com/prediction/sla
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---