load("@rules_python//python:defs.bzl", "py_library")
load("@graknlabs_kglib_pip//:requirements.bzl",
       graknlabs_kglib_requirement = "requirement")


py_library(
    name = "synthetic",
    deps = [
        '//kglib/utils/grakn/synthetic/statistics',
        '//kglib/utils/grakn/synthetic/examples',
    ],
    visibility=['//visibility:public']
)