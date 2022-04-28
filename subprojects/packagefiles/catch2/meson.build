project('catch2', 'cpp', default_options : ['cpp_std=c++11'])

libcatch2_dep = declare_dependency(
    include_directories: include_directories('single_include')
)

meson.override_dependency('catch2', libcatch2_dep)
