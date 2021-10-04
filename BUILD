cc_library(
    name = "greet_lib",
    srcs = ["greet.cc"],
    hdrs = ["greet.hh"],
)

cc_binary(
    name = "hello",
    srcs = ["hello.cc"],
    deps = [":greet_lib"],
)
