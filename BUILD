sh_binary(
    name = "timer",
    srcs = ["timer.sh"]
)

sh_binary(
    name = "printer",
    srcs = ["printer.sh"],
    deps = ["@bazel_tools//tools/bash/runfiles"],
    data = ["data.txt"]
)
