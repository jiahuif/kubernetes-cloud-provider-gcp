load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "dump.go",
        "errors.go",
        "garbagecollector.go",
        "graph.go",
        "graph_builder.go",
        "operations.go",
        "patch.go",
        "uid_cache.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/controller/garbagecollector",
    importpath = "k8s.io/kubernetes/pkg/controller/garbagecollector",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/groupcache/lru:go_default_library",
        "//vendor/gonum.org/v1/gonum/graph:go_default_library",
        "//vendor/gonum.org/v1/gonum/graph/encoding:go_default_library",
        "//vendor/gonum.org/v1/gonum/graph/encoding/dot:go_default_library",
        "//vendor/gonum.org/v1/gonum/graph/simple:go_default_library",
        "//vendor/k8s.io/api/core/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/meta:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/sets:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/client-go/discovery:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/core/v1:go_default_library",
        "//vendor/k8s.io/client-go/metadata:go_default_library",
        "//vendor/k8s.io/client-go/tools/cache:go_default_library",
        "//vendor/k8s.io/client-go/tools/record:go_default_library",
        "//vendor/k8s.io/client-go/util/retry:go_default_library",
        "//vendor/k8s.io/client-go/util/workqueue:go_default_library",
        "//vendor/k8s.io/controller-manager/pkg/informerfactory:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/controller/apis/config/scheme:go_default_library",
        "//vendor/k8s.io/kubernetes/pkg/controller/garbagecollector/metaonly:go_default_library",
    ],
)
