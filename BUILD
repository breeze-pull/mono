load("@io_bazel_rules_go//go:def.bzl", "go_binary")

package(
    default_visibility = ["//visibility:public"],
)

go_binary(
    name = "hello",
        srcs = ["main.go"],
    deps = [
        "//auth",
    ],
)