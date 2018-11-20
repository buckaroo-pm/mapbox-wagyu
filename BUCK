load('//:buckaroo_macros.bzl', 'buckaroo_deps')

prebuilt_cxx_library(
  name = 'wagyu', 
  header_namespace = '', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'), 
  ]), 
  deps = buckaroo_deps(), 
  visibility = [
    'PUBLIC', 
  ], 
)
