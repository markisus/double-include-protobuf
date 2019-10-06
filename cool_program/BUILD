package(default_visibility = ["//visibility:public"])

cc_binary(
    name = "cool_program",
    srcs = [
        "cool_program.cc",
    ],
    deps = [
        ":cool_proto_cc_proto",
        "//third_party/libtorch",
    ],
)

proto_library(
    name = "cool_proto",
    srcs = ["cool_proto.proto"],
)

cc_proto_library(
    name = "cool_proto_cc_proto",
    deps = [":cool_proto"])
