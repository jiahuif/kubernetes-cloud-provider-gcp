load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["sync.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/controller/nodeipam/ipam/sync",
    importpath = "k8s.io/kubernetes/pkg/controller/nodeipam/ipam/sync",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/controller/nodeipam/ipam/cidrset:go_default_library",
    ],
)
