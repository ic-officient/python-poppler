project(
    'python-poppler', 
    'cpp', 
    version: '0.4.2', 
    license: 'GNU General Public License v2 (GPLv2)', 
    license_files: 'LICENSE.txt',
    meson_version: '>=1.1.0',
    default_options : ['cpp_std=c++11']
)

poppler_dep = dependency('poppler-cpp', version: '>=25.03.0')

python_mod = import('python')
python3 = python_mod.find_installation('python3', pure: false)

pybind11_dep = dependency('pybind11', version: '==3.0.1', required: true)

subdir('src')
