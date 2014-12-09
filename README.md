python-training-gov-au
======================

A python wrapper for the training.gov.au SOAP api

### Basic Usage

```
from TrainingGov import TrainingGovAPI, Organisations, TrainingComponents

api = TrainingGovAPI("api-username", "api-password")     

orgs = Organisations()
# Passing RTO Code
results = orgs.getCourseList("4 digit RTO Code")
```
