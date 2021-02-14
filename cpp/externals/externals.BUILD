load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "hello-time",
    srcs = glob(["hello-time/*.cc"]),
    hdrs = glob(["hello-time/*.h"]),
    inlucde_prefix = "lib",  # includeする名前空間を定義
    strip_include_prefix = "hello-time",  # module name?
    visibility = ["//visibility:public"],
)
