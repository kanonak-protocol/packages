# Kanonak Protocol Packages

Source of the Kanonak Protocol packages.

## Publishing a version

Add it as `{package}/{version}.kan.yml`, then run `kanonak release-lock` and commit the `{version}.kanonak.lock` it
writes beside it: the closure the version resolves to now, recorded once and never changed. kanonak.org serves it at
`https://kanonak.org/{package}/{version}/kanonak.lock`, and this repository's check refuses a version without one.
