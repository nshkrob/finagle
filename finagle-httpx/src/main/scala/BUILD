scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'finagle.httpx',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/twitter/bijection:core',
    '3rdparty/jvm/commons-lang',
    '3rdparty:guava',
    '3rdparty:netty',
    'finagle/finagle-core',
    'util/util-codec',
    'util/util-core',
    'util/util-logging',
  ],
  sources=rglobs('*.scala'),
)
