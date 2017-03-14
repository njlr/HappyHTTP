cxx_library(
  name = 'happyhttp',
  header_namespace = '',
  exported_headers = [
    'happyhttp.h',
  ],
  srcs = [
    'happyhttp.cpp',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'test.cpp',
  ],
  deps = [
    ':happyhttp',
  ],
)
