package(default_visibility = ["//visibility:public"])

load("@org_tensorflow_tensorboard//tensorboard/defs:web.bzl", "ts_web_library")

licenses(["notice"])  # Apache 2.0

ts_web_library(
    name = "facets_overview_row_stats",
    srcs = [
        "facets-overview-row-stats.html",
        "facets-overview-row-stats.ts"
    ],
    clutz_entry_points = [
        "proto.featureStatistics.DatasetFeatureStatistics",
        "proto.featureStatistics.DatasetFeatureStatisticsList",
        "proto.featureStatistics.FeatureNameStatistics",
        "proto.featureStatistics.NumericStatistics",
        "proto.featureStatistics.StringStatistics",
        "proto.featureStatistics.CommonStatistics",
        "proto.featureStatistics.Histogram",
        "proto.featureStatistics.RankHistogram"
    ],
    path = "/facets-overview/components/facets-overview-row-stats",
    deps = [
        "//facets_overview/proto",
        "//facets_overview/common",
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:d3",
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
    ],
)
