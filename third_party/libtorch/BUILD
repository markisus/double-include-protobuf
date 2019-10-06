package(default_visibility = ["//visibility:public"])

cc_library(
    name = "libtorch",
    hdrs = glob(["include/**/*"]),
    srcs = glob(["lib/*.lib"]),
    deps = [":dlls",], # this copies dlls first
    strip_include_prefix = "/third_party/libtorch/include",
)

cc_library(
    name = "dlls",
    srcs = glob(["lib/*.dll"]),
)
