maven_layout()

jar_library(name='zipkin-scrooge',
  dependencies=[
    pants('oss/zipkin-scrooge/src/main/scala'),
    pants('oss/zipkin-scrooge/src/main/thrift')
  ]
)

jar_library(name='tests',
  dependencies=[
    pants('oss/zipkin-scrooge/src/test/scala')
  ]
)
