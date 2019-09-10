load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
  name = "buckaroo_madler_zlib",
  urls = [
    "https://github.com/madler/zlib/archive/v1.2.11.tar.gz"
  ],
  sha256 = "629380c90a77b964d896ed37163f5c3a34f6e6d897311f1df2a7016355c45eff",
  strip_prefix = "zlib-1.2.11",
  build_file = "//:zlib.BUILD",
  workspace_file = "//:zlib.WORKSPACE",
)
