project(
	'ogl-learning',
	['cpp', 'c'],
	version: '0.1',
	license: 'MIT',
	meson_version: '>=0.60.0',
	default_options: [
		'warning_level=0',
		'werror=false',
	],
)

glfw = dependency('glfw3')
cc = meson.get_compiler('cpp')

ogl_inc = include_directories('include')
subdir('src')
