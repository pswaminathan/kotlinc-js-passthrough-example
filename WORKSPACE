load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_kotlin",
    sha256 = "01293740a16e474669aba5b5a1fe3d368de5832442f164e4fbfc566815a8bc3a",
    urls = ["https://github.com/bazelbuild/rules_kotlin/releases/download/v1.8/rules_kotlin_release.tgz"],
)

load("@io_bazel_rules_kotlin//kotlin:repositories.bzl", "kotlin_repositories", "kotlinc_version")

kotlin_repositories()

register_toolchains("//:kotlin_toolchain")
