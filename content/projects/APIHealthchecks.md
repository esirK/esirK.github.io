---
date: '2020-08-01'
title: 'API Health checks'
github: 'https://github.com/esirK/APIHealthchecks'
external: ''
android: ''
tech:
  - Python
company: ''
showInProjects: true
---

AWS Lambda function that checks the status of APIs defined in `apis.json` and if the API can be monitored(pinged) from this app, then the app sends a ping to Healthchecks(Opensource project) leting it know that the app is online. If the app can't ping an API, it doesn't ping healthchecks and thus healthchecks notifies us that the app is down.
