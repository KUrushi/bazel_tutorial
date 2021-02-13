load("@rules_cc//cc:defs.bzl", "cc_library")

# //main直下のすべてのtargetがhello-targetを指定できる
cc_library(
    name = "hello-time",
    srcs = ["hello-time.cc"],
    hdrs = ["hello-time.h"],
    visibility = ["//main:__pkg__"]  # ここで指定したtargetからの依存を許可する
)