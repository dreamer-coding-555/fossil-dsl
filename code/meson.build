deps = [
    dependency('fossil-sdk')
]

dir = include_directories('.')
code = files('app.c')

executable('fossil-dsl',
    sources: ['main.c', code],
    include_directories: dir,
    dependencies: deps,
    install: true)
