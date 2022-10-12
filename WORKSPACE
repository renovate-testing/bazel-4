load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:utils.bzl", "maybe")

http_archive(
    name = "GBDeviceInfo",
    url = "https://github.com/lmirosevic/GBDeviceInfo/archive/6.3.0.tar.gz",
    sha256 = "d7666275dff039407ea467c3083b83e24934101777c8b55b6b1b3b7e9a9e220b",
    strip_prefix = "GBDeviceInfo-6.3.0/GBDeviceInfo"
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
    url = "https://github.com/nelhage/rules_boost/archive/630cf5dbad418ee8cfa637b1e33125b11807721d.zip",
    sha256 = "65670fec5210cccd45ff6d4ef69762feda49ac1bbd15eae344d79a8f5076c051",
    strip_prefix = "rules_boost-630cf5dbad418ee8cfa637b1e33125b11807721d",
)

maybe(
  http_archive,
  name = "io_bazel_rules_go",
  sha256 = "2b1641428dff9018f9e85c0384f03ec6c10660d935b750e3fa1492a281a53b0f",
  url = "https://github.com/bazelbuild/rules_go/releases/download/v0.29.0/rules_go-v0.29.0.zip",
)
