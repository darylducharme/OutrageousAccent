load("@rules_pkg//:pkg.bzl", "pkg_zip")

SOUND_ASSETS = glob(["wrapper/assets/**/*.ogg"]);
BEDROCK_META_ASSETS = glob(
    ["wrapper/assets/**/*.json", "wrapper/assets/**/pack_icon.png"],
    exclude = ["wrapper/assets/sound.json"],
);
JAVA_META_ASSETS = ["wrapper/pack.mcmeta", "wrapper/pack.png"];

pkg_zip (
    name = "outrageous_accents",
    extension = "mcpack",
    srcs = SOUND_ASSETS + BEDROCK_META_ASSETS,
    strip_prefix = "/wrapper/assets/minecraft",
)

pkg_zip (
    name = "outrageous_accents_java",
    srcs = SOUND_ASSETS + JAVA_META_ASSETS,
    strip_prefix = "/wrapper",
)
