cc_library(
    name = "greet_lib",
    srcs = ["gree.cc"],
    hdrs = ["greet.hh"],
)

cc_binary(
    name = "hello",
    srcs = ["hello.cc"],
    deps = [":greet_lib"],
)
