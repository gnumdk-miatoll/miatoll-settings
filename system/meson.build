mobile_settings_sources = [
  'bus.c',
  'main.c',
  '../common/utils.c'
]

mobile_settings_deps = [
  dependency('glib-2.0'),
  dependency('gio-2.0'),
  dependency('gio-unix-2.0'),
  dependency('libgbinder')
]

executable('mobile-settings', mobile_settings_sources,
  dependencies: mobile_settings_deps,
  install_dir: sbin_dir,
  install: true,
)
