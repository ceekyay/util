scala_library(
    sources = rglobs("*.scala"),
    fatal_warnings = True,
    provides = scala_artifact(
        org = "com.twitter",
        name = "util-slf4j-jul-bridge",
        repo = artifactory,
    ),
    dependencies = [
        "3rdparty/jvm/org/slf4j:jul-to-slf4j",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "util/util-core/src/main/scala",
        "util/util-slf4j-api/src/main/scala",
    ],
)
