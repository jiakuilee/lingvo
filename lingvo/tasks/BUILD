package(
    default_visibility = ["//visibility:public"],
)

licenses(["notice"])  # Apache 2.0

py_library(
    name = "all_params",
    # LINT.IfChange(task_dirs)
    deps = [
        "//lingvo/tasks/image/params",
        "//lingvo/tasks/lm/params",
        "//lingvo/tasks/mt/params",
    ],
    # LINT.ThenChange(../model_imports.py:task_dirs)
)
