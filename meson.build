project('meson-detached-head', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

exe = executable('meson_detached_head', 'meson_detached_head.c',
  install : true, dependencies: [dependency('catch2')])

test('basic', exe)
