# Wercker for test-kitchen with Docker backend.

Wercker currently does not support `inherits: wercker-labs/docker` in
the `wercker-box.yml`, you have to put the `script:` part into the `wercker.yml`. See
the `wercker.yml` in the [Pure-FTPd](https://github.com/Aigeruth/pure-ftpd) repository.
