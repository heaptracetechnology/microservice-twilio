# Twilio as a microservice (GOLANG)
An OMG service for Twilio, it allows to send SMS.

[![Open Microservice Guide](https://img.shields.io/badge/OMG-enabled-brightgreen.svg?style=for-the-badge)](https://microservice.guide)
<!-- [![Build Status](https://travis-ci.com/heaptracetechnology/microservice-mail.svg?branch=master)](https://travis-ci.com/heaptracetechnology/microservice-mail) -->


## [OMG](hhttps://microservice.guide) CLI

### OMG

* omg validate
```
omg validate
```
* omg build
```
omg build
```
### Test Service

* Test the service by following OMG commands

### CLI

##### Send SMS
```sh
$ omg run send -a from=<PHONE_NUMBER> -a to=<PHONE_NUMBER> -a message=<MESSAGE_TEXT_BODY> -e ACCOUNT_SID=<ACCOUNT_SID> -e AUTH_TOKEN=<AUTH_TOKEN>
```

## License
### [MIT](https://choosealicense.com/licenses/mit/)

## Docker
### Build
```
docker build -t microservice-twilio .
```
### RUN
```
docker run -p 3000:3000 microservice-twilio
```
