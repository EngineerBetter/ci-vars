# ci-vars-keys

A template Concourse `--load-vars-from` file.

Do not commit secrets here; only use this for sharing the names of keys.

Using a hydrated version of this file makes it easier when someone has to do a `fly set-pipeline` on _all the things_.

## Usage

```
$ cp secrets.yml private/secret.yml
# Fill in values
$ cd workspace/some-project
$ fly [...] --load-vars-from ~/workspace/ci-vars-keys/private/secrets.yml
```