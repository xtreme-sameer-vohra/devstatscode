# Testing
1. To execute tests just run `make test`, do not set any environment variables for them, one of tests is to check default environment!
2. To check all sources using multiple go tools (like fmt, lint, imports, vet, goconst, usedexports), run `make check`.
3. To check Travis CI payloads use `PG_PASS=pwd GET=1 ./devel/webhook.sh` and then `./devel/test_webhook.sh`.
4. Continuous deployment instructions are [here](https://github.com/cncf/devstats/blob/master/CONTINUOUS_DEPLOYMENT.md).