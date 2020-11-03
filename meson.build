project('pugixml', 'cpp')

pugixml_includes = include_directories('src')

pugixml_sources = [
'src/pugiconfig.hpp',
'src/pugixml.cpp',
'src/pugixml.hpp',
]

pugixml_library = library('pugixml', sources : pugixml_sources, include_directories : pugixml_includes)

pugixml_dependency = declare_dependency(include_directories : pugixml_includes, link_with : pugixml_library)
