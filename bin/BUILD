package(
    default_visibility = ["//visibility:public"],
)

load("@io_bazel_rules_go//go:def.bzl", "go_binary")

go_binary(
    name = "bin",
    srcs = ["bin.go"],
    deps = [
        "//libtwo:go_default_library",
    ],
)
