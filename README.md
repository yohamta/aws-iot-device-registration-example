# AWS IoT Device Registration using Lambda Example

This is an example of creating AWS IoT Device and generate Certificate using Lambda.

## Use Case
Set up IoT Device automatically and register to AWS IoT when you execute AWS Lambda through API Gateway which should be secure using API Key or Custom Authorization.

## Set Up
- Create ThingType
- Create Policy

## How to run locally
- Run following command
```
$ sls invoke local -f generateCert -d '{"thingName":"thing001","thingType":"test-thing-type","policy":"test-device-policy"}'
```

## How to deploy
- Run following command
```
$ serverless deploy
```
- execute lambda using AWS Console

