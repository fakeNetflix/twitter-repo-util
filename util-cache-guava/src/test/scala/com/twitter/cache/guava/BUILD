junit_tests(
    sources = rglobs("*.scala"),
    compiler_option_sets = {"fatal_warnings"},
    dependencies = [
        "3rdparty/jvm/com/google/code/findbugs:jsr305",
        "3rdparty/jvm/com/google/guava",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/org/scalatest",
        "util/util-cache-guava/src/main/scala/com/twitter/cache/guava",
        "util/util-cache/src/main/scala/com/twitter/cache",
        "util/util-cache/src/test/scala/com/twitter/cache:abstract_tests",
        "util/util-core/src/main/scala/com/twitter/util",
    ],
)
