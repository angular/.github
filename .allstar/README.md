# Allstar configuration for Angular

[Allstar](https://github.com/ossf/allstar) is a security-policy GitHub app. It is
installed for all repositories in the Angular organization. This repository contains the root
configuration for the app.

## Enabled Repos

Currently Allstar is enabled on only the following repositories:

- [angular/angular](https://github.com/angular/angular)
- [angular/angular-cli](https://github.com/angular/angular-cli)
- [angular/components](https://github.com/angular/components)
- [angular/dev-infra](https://github.com/angular/dev-infra)


## Policy Configuration

### [Branch Protection](branch_protection.yaml)

We do not currently require branch protection as we enforce our restrictions via rulesets.

### [Outside Collaborators](outside.yaml)

- Push access not allowed.
- Admin access not allowed.

### [SECURITY.md](security.yaml)

- SECURITY.md required.

### [Binary Artifacts](binary_artifacts.yaml)

- No binary artifacts are allowed to be commited to the repository.
