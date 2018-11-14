prebuilt_cxx_library(
  name = 'concept-check', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-core//:core', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
    'buckaroo.github.buckaroo-pm.boost-mpl//:mpl', 
    'buckaroo.github.buckaroo-pm.boost-preprocessor//:preprocessor', 
    'buckaroo.github.buckaroo-pm.boost-type_traits//:type-traits', 
    'buckaroo.github.buckaroo-pm.boost-utility//:utility'
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
