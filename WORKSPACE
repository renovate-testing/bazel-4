load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:utils.bzl", "maybe")

http_archive(
    name = "GBDeviceInfo",
    url = "https://github.com/lmirosevic/GBDeviceInfo/archive/6.8.0.tar.gz",
    sha256 = "15790f98e47e8d6b66611e66e59a6ad83817958416d3336478b0ac57f0aef6c2",
    strip_prefix = "GBDeviceInfo-6.8.0/GBDeviceInfo"
)

http_archive(
    name = "com_github_nelhage_rules_boost",
    url = "https://github.com/nelhage/rules_boost/archive/135d46b4c9423ee7d494c78a21ff621bc73c12f3.tar.gz",
    sha256 = "3651f5dda0f7296e4cecafacc7f9d1f274be0fd64e30bebd74e28ffba28fe77f",
    strip_prefix = "rules_boost-135d46b4c9423ee7d494c78a21ff621bc73c12f3",
)
load("@com_github_nelhage_rules_boost//:boost/boost.bzl", "boost_deps")
boost_deps()

http_archive(
    name = "GBDeviceInfo-zip",
    url = "https://github.com/lmirosevic/GBDeviceInfo/archive/6.3.0.zip",
    sha256 = "4ef4320c4880fd64cfb7f42132f4b02fa626bccf1ba3e1a71dfbfcb50735f141",
    strip_prefix = "GBDeviceInfo-6.3.0/GBDeviceInfo"
)

http_archive(
    name = "com_github_nelhage_rules_boost-zip",
    url = "https://github.com/nelhage/rules_boost/archive/135d46b4c9423ee7d494c78a21ff621bc73c12f3.zip",
    sha256 = "de8aac034cabe4a9ba5f7a33b9523862bf76c245a6c554c0e737f591bb7c7aeb",
    strip_prefix = "rules_boost-135d46b4c9423ee7d494c78a21ff621bc73c12f3",
)

maybe(
  http_archive,
  name = "io_bazel_rules_go",
  sha256 = "2b1641428dff9018f9e85c0384f03ec6c10660d935b750e3fa1492a281a53b0f",
  url = "https://github.com/bazelbuild/rules_go/releases/download/v0.29.0/rules_go-v0.29.0.zip",
)
