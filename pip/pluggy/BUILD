package(default_visibility = ["//visibility:public"])

load("//build_tools/py:py.bzl", "dbx_py_pypi_piplib")

dbx_py_pypi_piplib(
    name = "pluggy",
    pip_version = "0.13.1",
    python2_compatible = True,
    python3_compatible = True,
    setup_requires = ["//pip/setuptools_scm"],
    deps = ["//pip/importlib-metadata"],
)
