genrule(
    name = "version",
    srcs = glob([".git/**"]),
    outs = ["version.txt"],
    cmd_bash = "git --git-dir=$(location :.git) describe --always --dirty |tee $@",
)
