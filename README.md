# _Twilio_ OMG Microservice (GOLANG)

[![Open Microservice Guide](https://img.shields.io/badge/OMG%20Enabled-👍-green.svg?)](https://microservice.guide)
[![Build Status](https://travis-ci.com/omg-services/microservice-twilio.svg?branch=master)](https://travis-ci.com/omg-services/microservice-twilio)
[![codecov](https://codecov.io/gh/omg-services/microservice-twilio/branch/master/graph/badge.svg)](https://codecov.io/gh/omg-services/microservice-twilio)

An OMG service for Twilio, it allows to send SMS.

## Usage in [Storyscript](https://storyscript.io/)

##### Send SMS
```coffee
>>> twilio send from:'phoneNumber' to:'phoneNumber' message:'messageText' 
{
  "sid": "sid",
  "account_sid": "account_sid",
  "to": "+914408012345",
  "from": "+17042456341",
  "body": "hello, text message from twilio omg",
  "status": "queued"
}
```

Curious to [learn more](https://docs.storyscript.io/)?

✨🍰✨

## Usage with [OMG CLI](https://www.npmjs.com/package/omg)
##### Send SMS
```shell
$ omg run send -a from=<PHONE_NUMBER> -a to=<PHONE_NUMBER> -a message=<MESSAGE_TEXT_BODY> -e ACCOUNT_SID=<ACCOUNT_SID> -e AUTH_TOKEN=<AUTH_TOKEN>
```
**Note**: the OMG CLI requires [Docker](https://docs.docker.com/install/) to be installed.

## License
[MIT License](https://github.com/omg-services/microservice-twilio/blob/master/LICENSE).
