project('zlib', 'c')

zlib_sources = [
    'adler32.c',
    'compress.c',
    'crc32.c',
    'deflate.c',
    'gzclose.c',
    'gzlib.c',
    'gzread.c',
    'gzwrite.c',
    'inflate.c',
    'infback.c',
    'inftrees.c',
    'inffast.c',
    'trees.c',
    'uncompr.c',
    'zutil.c'
]

libzlib = static_library('zlib', zlib_sources, include_directories: include_directories('.'), install : false)

libzlib_dep = declare_dependency(include_directories: include_directories('.'), link_with: libzlib)
