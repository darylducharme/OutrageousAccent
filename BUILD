load("@rules_pkg//:pkg.bzl", "pkg_zip")

SOUND_ASSETS = glob(["assets/**/*.ogg"]);
JSON_ASSETS = glob(["assets/**/*.json"]);

pkg_zip (
    name = "outrageous_accents",
    extension = "mcpack",
    srcs = SOUND_ASSETS + JSON_ASSETS,
    strip_prefix = "/assets",
)
