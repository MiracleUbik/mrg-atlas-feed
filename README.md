# Encrypted update feed

This repository stores authenticated encrypted update packages and a small
version manifest. It contains no viewing key and no unencrypted application.
The encrypted packages can be opened only with the separately distributed
viewer and its key.

Earlier encrypted packages are retained so cached manifests can finish
downloading. Repository history and previously downloaded copies may persist.
Changing a viewing key controls future packages; it does not revoke copies
that a recipient has already downloaded and decrypted.
