# Description:
#   Avro Library

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE.txt"])

cc_library(
    name = "avro_c",
    srcs = glob(["*.c", "*.h"]),
    hdrs = glob(["avro.h", "avro/*.h"]),
    visibility = ["//visibility:public"],
)
