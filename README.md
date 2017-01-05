# terraform-skeleton
A skeleton structure for quick-starting a new terraform project


## Usage
```
$ terraform plan
$ terraform apply
```

## Structure
* Split into "environments" - rename directories as needed for targets
* top level tf file for each env called "base" add tf files as necessary for customisations and layering up config
* vars.tf intended to parameterise configs for DRY approach


