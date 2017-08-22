# ci-vars-keys

A template Concourse `--load-vars-from` file.

Do not commit secrets here; only use this for sharing the names of keys.

Using a hydrated version of this file makes it easier when someone has to do a `fly set-pipeline` on _all the things_.