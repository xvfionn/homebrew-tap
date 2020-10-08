To downgrade `gnupg` with homebrew to version 2.2.21, run the following.

    brew tap xvfionn/tap
    brew install gnupg@2.2.21
    # This may produce some errors, that's ok
    brew link --overwrite gnupg@2.2.21

Test it by checking the output of `gpg --version`.

To reinstall the latest version from homebrew, run the below commands.

    brew unlink gnupg
    brew unlink gnupg@2.2.21
    brew link gnupg
