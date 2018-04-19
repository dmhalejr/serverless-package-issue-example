## Reproducible Example

```
npm install # first time
npm run package
```

Although I understand that the documentation states that running `sls package` is going to package the `service while using the default stage (dev) and default region (us-east-1).`

I was hoping that if I gave the serverless.yml `stage` an environmental variable on package it'd create a deployable that would work stage/environment agnostic. 

LINK:
https://serverless.com/framework/docs/providers/aws/cli-reference/package#packaging-without-stage-and-region-options