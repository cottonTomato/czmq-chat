project('czmqhttp', 'c', version: '0.1', default_options: 'default_library=static')

project_name = meson.project_name()
czmq_dep = dependency('libczmq', version: '>=4.2.1')

client = executable('client', 'client.c', dependencies: czmq_dep)
server = executable('server', 'server.c', dependencies: czmq_dep)
