load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "standing_still_trajectory1d",
    srcs = [
        "standing_still_trajectory1d.cc",
    ],
    hdrs = [
        "standing_still_trajectory1d.h",
    ],
    deps = [
        "//modules/planning/math/curve1d",
    ],
)

cc_library(
    name = "piecewise_acceleration_trajectory1d",
    srcs = [
        "piecewise_acceleration_trajectory1d.cc",
    ],
    hdrs = [
        "piecewise_acceleration_trajectory1d.h",
    ],
    deps = [
        "//modules/common",
        "//modules/common/math:linear_interpolation",
        "//modules/planning/common:planning_gflags",
        "//modules/planning/math/curve1d",
    ],
)

cc_library(
    name = "constant_deceleration_trajectory1d",
    srcs = [
        "constant_deceleration_trajectory1d.cc",
    ],
    hdrs = [
        "constant_deceleration_trajectory1d.h",
    ],
    deps = [
        "//modules/common",
        "//modules/planning/common:planning_gflags",
        "//modules/planning/math/curve1d",
    ],
)

cc_library(
    name = "piecewise_trajectory1d",
    srcs = [
        "piecewise_trajectory1d.cc",
    ],
    hdrs = [
        "piecewise_trajectory1d.h",
    ],
    deps = [
        "//modules/common",
        "//modules/common/math:linear_interpolation",
        "//modules/planning/math/curve1d",
    ],
)

cc_library(
    name = "lattice_trajectory1d",
    srcs = [
        "lattice_trajectory1d.cc",
    ],
    hdrs = [
        "lattice_trajectory1d.h",
    ],
    deps = [
        "//modules/planning/math/curve1d",
    ],
)

cc_library(
    name = "constant_jerk_trajectory1d",
    srcs = [
        "constant_jerk_trajectory1d.cc",
    ],
    hdrs = [
        "constant_jerk_trajectory1d.h",
    ],
    deps = [
        "//modules/planning/math/curve1d",
        "//modules/planning/common:planning_gflags",
    ],
)

cc_library(
    name = "piecewise_jerk_trajectory1d",
    srcs = [
        "piecewise_jerk_trajectory1d.cc",
    ],
    hdrs = [
        "piecewise_jerk_trajectory1d.h",
    ],
    deps = [
        "//modules/planning/math/curve1d",
        "//modules/planning/common:planning_gflags",
        ":constant_jerk_trajectory1d",
    ],
)

cpplint()
