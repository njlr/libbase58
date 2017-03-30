cxx_library(
  name = 'libbase58',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 'libbase58'),
  ]),
  srcs = [
    'base58.c',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'base58',
  srcs = [
    'clitool.c',
  ],
  deps = [
    ':libbase58',
  ],
)
