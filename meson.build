project('spdlog_setup', 'cpp', version : '0.3.0_aplha.1', license: 'MIT',
		default_options : ['cpp_std=c++11'])

inc = include_directories('include')

spdlog_setup_dep = declare_dependency(include_directories : inc)

src_utest = [
    'src/unit_test/unit_test.cpp',
]

utest_exec = executable('utest', src_utest, include_directories : inc)
test('utest', utest_exec)
