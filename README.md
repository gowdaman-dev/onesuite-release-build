# OneSuite Release Build

Private build repository for OneSuite Windows EXE release assets.

This repository does not store the organization source tree. Its GitHub Actions workflow receives a repository dispatch event containing the source repository name and commit SHA, checks out that exact commit with a read-only source token, builds the project, and attaches the generated ZIP outputs to a release in this private repository.
