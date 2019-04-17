# GitVersion Bug

Demonstrating [GitVersion issue 1578](https://github.com/GitTools/GitVersion/issues/1578).

## Results

GitVersion assumes the root commit to be the fallback `0.1.0` rather than using the `v0.0.0` tag.

See [the result file](Results.md) for details. GitVersion does not support detached HEADs so `git reset --hard` is necessary to recreate the results.

|  Sha    | GitVersion Calculated | Expected |
| ------- | --------------------- | -------- |
| e8caf03 | v0.0.0                | v0.0.0   |
| f97f396 | v0.2.0                | v0.1.0   |
| 2426637 | v0.2.1                | v0.1.1   |
| 03a4836 | v1.0.0                | v1.0.0   |
