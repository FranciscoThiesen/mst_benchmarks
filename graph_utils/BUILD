load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "graph_utils",
    srcs = ["graph_utils.cpp"],
    hdrs = ["graph_utils.hpp"],
    copts = [
        "-std=c++17",
    ],
    deps = ["//union_find:union_find"],
    visibility = ["//visibility:public"],
)
