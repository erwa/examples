# Description:
#   Avro Library

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE.txt"])

cc_library(
    name = "avro_c",
    srcs = glob(
        [
            "*.c",
            "*.h"
        ],
        exclude = [
            "schema_specific.c",
        ],
    ),
    hdrs = glob(["avro.h", "avro/*.h"]),
    linkstatic = True,
    visibility = ["//visibility:public"],
)
