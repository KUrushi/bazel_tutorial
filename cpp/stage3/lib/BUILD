load("@rules_cc//cc:defs.bzl", "cc_library")

# //main直下のすべてのtargetがhello-targetを指定できる
cc_library(
    name = "hello-time",
    srcs = ["hello-time.cc"],
    hdrs = ["hello-time.h"],
    visibility = ["//visibility:public"]  # publicにして外部からでもhello-timeを参照できるようにする
)