load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "ipnet.go",
        "net.go",
        "port.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/utils/net",
    importpath = "k8s.io/utils/net",
    visibility = ["//visibility:public"],
)
