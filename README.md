# spring-cloud-config-server

Get all repo/modules from - https://github.com/khabib97/spring-boot-cloud-service

This repository serves as centralized configuration server for the above project

- Clone this repo
- Import as maven project
- Then run as java application
- Go to http://localhost:8888/limits-service/default
Expected output, maybe:
```
{
  name: "limits-service",
  profiles: [
    "default"
  ],
  label: null,
  version: "9540d048cb261ca54def0ae76630df2afa09f191",
  state: null,
  propertySources: [
    {
      name: "https://github.com/khabib97/config-repo-spring-cloud-service.git/file:C:\Users\User\AppData\Local\Temp\config-repo-9055180827079894343\limits-service.properties",
      source: {
        limits-service.minimum: "4",
        limits-service.maximum: "444"
      }
    }
  ]
}
```
