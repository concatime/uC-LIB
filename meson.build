uclib_deps = []
uclib_inc = include_directories('.')
if get_variable('default_configuration', false)
  uclib_inc = [uclib_inc, include_directories('Cfg/Template')]
endif
uclib_src = files(
  'lib_ascii.c',
  'lib_math.c',
  'lib_mem.c',
  'lib_str.c',
)
