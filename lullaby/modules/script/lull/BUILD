licenses(["notice"])  # Apache 2.0


package(
    default_visibility = ["//visibility:public"],
)

cc_library(
    name = "lull",
    srcs = [
        "functions/array.cc",
        "functions/compare.cc",
        "functions/cond.cc",
        "functions/do.cc",
        "functions/event.cc",
        "functions/map.cc",
        "functions/math.cc",
        "functions/mathfu.cc",
        "functions/stringify.cc",
        "functions/time.cc",
        "functions/typeof.cc",
        "functions/types.cc",
        "lull_script_engine.cc",
        "script_arg_list.cc",
        "script_ast_builder.cc",
        "script_compiler.cc",
        "script_env.cc",
        "script_frame.cc",
        "script_parser.cc",
        "script_scoped_symbol_table.cc",
        "script_value.cc",
    ],
    hdrs = [
        "functions/converter.h",
        "functions/functions.h",
        "lull_script_engine.h",
        "script_arg_list.h",
        "script_ast_builder.h",
        "script_compiler.h",
        "script_env.h",
        "script_frame.h",
        "script_parser.h",
        "script_scoped_symbol_table.h",
        "script_types.h",
        "script_value.h",
    ],
    deps = [
        "//lullaby/modules/dispatcher",
        "//lullaby/modules/function",
        "//lullaby/modules/serialize",
        "//lullaby/util:common_types",
        "//lullaby/util:hash",
        "//lullaby/util:optional",
        "//lullaby/util:span",
        "//lullaby/util:string_view",
        "//lullaby/util:time",
        "//lullaby/util:typed_pointer",
        "//lullaby/util:typeid",
        "//lullaby/util:variant",
        "@mathfu//:mathfu",
    ],
    alwayslink = 1,
)

