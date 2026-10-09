# Applist Exporter — Actions

This repository contains the manual Actions runner. The implementation and saved
results are maintained in a separate private repository.

Run **Actions → Run export → Run workflow** on `main`. Leave the internal
continuation fields at their defaults. Empty filters select all items; a nonzero
`max_apps` limits the total across workers and disables automatic continuation.

The workflow publishes only basic progress. Saved results, execution state
and detailed diagnostics are stored in the private repository. Runtime
configuration is documented in the private repository.
