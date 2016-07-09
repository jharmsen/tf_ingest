load("@protobuf//:protobuf.bzl", "cc_proto_library")

cc_proto_library(
    name = "tf_ingest_proto",
    srcs = ["tf_ingest.proto"],
    cc_libs = ["@protobuf//:protobuf"],
    default_runtime = "@protobuf//:protobuf",
    protoc = "@protobuf//:protoc",
)
