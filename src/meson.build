sources = [
  'window.vala',
  'application.vala',
  'utils.vala',
  'widgets/colour-switcher.vala',
  'widgets/game-board.vala',
  'widgets/difficulty-selector.vala',
  'models/colours.vala',
  'models/difficulty.vala',
  'objects/signals.vala',
  'dialogs/victory-dialog.vala',
  'dialogs/defeat-dialog.vala'
]

deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.0'),
  dependency('gee-0.8'),
]

gnome = import('gnome')

executable(
  'window_painter',
  sources,
  asresources,
  vala_args: '--target-glib=2.50',
  dependencies: deps,
  install: true,
)
