# matryoshka
A repository of common, opinionated CloudFormation templates, designed to be used as nested stacks.

# TODO
- sync on githook--when templates are pushed to git, they should automatically end up in an s3 bucket, ready for use
- mirror git history to s3 as well, so as to avoid changes breaking attempts to update existing stacks?
  - some versioning system required, in any case.
