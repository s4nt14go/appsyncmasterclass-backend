# appsyncmasterclass-backend

## Notes

If when deploying, it shows `Resource handler returned message: "Uploaded file must be a non-empty zip (Service: Lambda...`, use node v14. It can be set by `nvm`:
```shell
nvm install 14
nvm use 14
npm run sls -- deploy
```
[Source](https://stackoverflow.com/questions/65916681/uploaded-file-must-be-a-non-empty-zip-service-awslambdainternal-status-code#answer-66069210)