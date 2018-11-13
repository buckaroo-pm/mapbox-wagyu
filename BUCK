prebuilt_cxx_library(
  name = 'wagyu', 
  header_namespace = '', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.mapbox-geometry.hpp//:geometry', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
