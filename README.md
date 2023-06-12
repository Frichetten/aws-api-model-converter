# aws-api-model-converter
Take undocumented APIs in the AWS Console and convert them to usable models for the AWS CLI.

Inspired by the Amazing talk from [Ben Bridts](https://twitter.com/benbridts), "[From ‘huh?’ to privilege escalation: finding vulnerabilities from a bug in the AWS console](https://pretalx.com/fwd-cloudsec-2023/talk/7BXVWM/)", this tool is designed to convert [undocumented APIs](https://github.com/Frichetten/aws-api-models/) to a format that can be used by [botocore](https://botocore.amazonaws.com/v1/documentation/api/latest/reference/loaders.html), and as a result, the AWS CLI. 
