think_out_sources = [
  'main.c',
  'think-out-application.c',
  'think-out-window.c',
]

think_out_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1'),
]

think_out_sources += gnome.compile_resources('think-out-resources',
  'think-out.gresource.xml',
  c_name: 'think_out'
)

executable('think-out', think_out_sources,
  dependencies: think_out_deps,
       install: true,
)
