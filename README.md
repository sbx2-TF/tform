# Terraform Utils

This repository contains reusable [Terraform](https://www.terraform.io/) utility modules, which are liberally licensed, and can be shared between projects.

## Resources

In addition to the modules here, there's a lot of useful ones in the wild. For example:

- https://registry.terraform.io/ - lots of solutions to common problems, some verified by Hashicorp themselves
- https://github.com/cloudposse - look for repos starting with `terraform-` for lots of good building blocks

## Releasing

Please use the included release script. For example:

```
$ ./release.sh
Checking dependencies... OK
Running terraform fmt... OK
Checking for clean working copy... OK
Parsing git remote... OK
Verifying GitHub API access... OK
Fetching previous tags from GitHub... OK

Previous release was: v9.1
This release will be: v9.2

Tagging new release... OK
Pushing release to GitHub... OK
Creating release on GitHub... OK
Updating example code with new release... OK
Updating Terraform module docs... OK
Creating commit from docs updates... OK
Pushing updated docs to GitHub... OK
Cleaning up... OK

New release is: https://github.com/futurice/terraform-utils/releases/tag/v9.2

```

## License

MIT
