project('gumbo', 'c')

gumbo_lib = library(
  'gumbo',
  sources: files(
    'src/attribute.c',
 'src/char_ref.c',
 'src/error.c',
 'src/parser.c',
 'src/string_buffer.c',
 'src/string_piece.c',
 'src/tag.c',
 'src/tokenizer.c',
 'src/utf8.c',
 'src/util.c',
 'src/vector.c',
  ),
  include_directories: [
    include_directories('src')
  ],
)
gumbo_dep = declare_dependency(
  link_with: gumbo_lib,
  include_directories: include_directories('src'),
)
