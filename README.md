# pippin_dependency_data
A repo for testing purposes - contains various python dependency files.

In order to test `pippin` we need publicly accessible HTTP URLs that contain `tar.gz` archives of user code that contain:

* `requirements.txt`
* `poetry.lock` & `pyproject.toml`
* combinations thereof

We use this repo to generate the tarballs and we use tags to version them.

e.g.

`https://github.com/tensorleap/pippin_dependency_data/tarball/requirements_only` points to a version of this repo that contains only a `requirements.txt` file.

