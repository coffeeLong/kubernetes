load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "interface.go",
        "testtype.go",
    ],
    importmap = "k8s.io/kubernetes/vendor/k8s.io/code-generator/_examples/apiserver/informers/internalversion/example2/internalversion",
    importpath = "k8s.io/code-generator/_examples/apiserver/informers/internalversion/example2/internalversion",
    visibility = ["//visibility:public"],
    deps = [
        "//staging/src/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//staging/src/k8s.io/apimachinery/pkg/watch:go_default_library",
        "//staging/src/k8s.io/client-go/tools/cache:go_default_library",
        "//staging/src/k8s.io/code-generator/_examples/apiserver/apis/example2:go_default_library",
        "//staging/src/k8s.io/code-generator/_examples/apiserver/clientset/internalversion:go_default_library",
        "//staging/src/k8s.io/code-generator/_examples/apiserver/informers/internalversion/internalinterfaces:go_default_library",
        "//staging/src/k8s.io/code-generator/_examples/apiserver/listers/example2/internalversion:go_default_library",
    ],
)
