# Flock API Client
REST API Client for [Flock](https://flock.com/). 
Based on [Sendgrid Python HTTP client](https://github.com/sendgrid/python-http-client)

Example of usage:
-------------
```python
api = FlockAPIClient(token=my_api_token)
raw_data = api.client.roster.listContacts.post()
users = raw_data.to_dict
```
