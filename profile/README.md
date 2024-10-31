# Lingua-Franca Community Package Repository

## What is lf-pkgs?

This GitHub organization hosts a selection of [lingo](https://github.com/lf-lang/lingo) packages, which contain Lingua Franca libraries that might be useful to the LF community.

## Guidelines for projects hosted within the lf-pkgs organization

- The name of the repository name should follow the `<name>-<target>` scheme (all lowercase, hyphenated).
- You need a `Lingo.toml` file in the root directory of the repository.
- The `Lingo.toml` file must contain a `[lib]` section that specifies the include directory, target, and name of the library.
- The repository description should name the current maintainer.
- Please set up a good `README.md` that descibes how to use the package.
- Set up a GitHub Actions workflow for continuous testing.
- Specify a license in a `LICENSE` file.
