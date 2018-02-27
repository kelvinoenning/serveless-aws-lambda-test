## Introduction

Tests of Amazon Lambda using the Serverless Framework.

## Install

### Required for any test
1. npm install serverless -g
2. sls config credentials -p \<provider> -k \<awsKey> -s \<awsSecretKey>

### Required for "Go" testing.
1. cd go
2. make
3. sls deploy

### Required for "Nodejs" testing.
1. cd nodejs
2. sls deploy