android_sdk_repository(
    name = "androidsdk",
    path = "C:/Users/llkey/AppData/Local/Android/Sdk",
)

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "rules_java",
    sha256 = "220b87d8cfabd22d1c6d8e3cdb4249abd4c93dcc152e0667db061fb1b957ee68",
    url = "https://github.com/bazelbuild/rules_java/releases/download/0.1.1/rules_java-0.1.1.tar.gz",
)
load("@rules_java//java:repositories.bzl", "rules_java_dependencies", "rules_java_toolchains")
rules_java_dependencies()
rules_java_toolchains()