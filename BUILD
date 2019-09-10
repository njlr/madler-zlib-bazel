alias(
  name = "zlib",
  actual = "@buckaroo_madler_zlib//:zlib",
  visibility = [
    "//visibility:public",
  ],
)

zlib = ":zlib"

cc_binary(
  name = "enough",
  srcs = [
    "enough.c",
  ],
  deps = [
    zlib,
  ],
)

cc_binary(
  name = "gun",
  srcs = [
    "gun.c",
  ],
  deps = [
    zlib,
  ],
)

cc_binary(
  name = "zran",
  srcs = [
    "zran.c",
  ],
  deps = [
    zlib,
  ],
)
