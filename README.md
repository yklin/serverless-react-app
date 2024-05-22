# To deploy

Before you can deploy, you need to setup AWS credentials before deploying. You can do this by running `aws configure` and following the prompts.

Or, you can use the `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables.

``` bash
$ export AWS_ACCESS_KEY_ID=your_access_key
$ export AWS_SECRET_ACCESS_KEY=your_secret_key
```


``` bash
$ npm install
$ npm run build
$ npx serverless deploy
```
