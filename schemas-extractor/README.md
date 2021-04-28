Simple utility to get schemas of all official Terraform Providers

How to Use
-----

1. Ensure you have `GOPATH` env variable set up

2. Run `make`

3. You'll see `schemas` directory with schemas and 'failure.txt' file with list of failed providers

4. Run: ./copy-json-files.sh

5. Copy providers.list to `/REPO_ROOT/terraform/model/`


