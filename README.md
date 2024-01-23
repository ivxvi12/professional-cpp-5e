# professional-cpp-5e

It's the example of code in windows.

I built things on windows command line.

To compile and build things with c++20, we need several things.

https://learn.microsoft.com/ko-kr/cpp/cpp/tutorial-import-stl-named-module?view=msvc-170

1. cl /std:c++latest /EHsc /nologo /W4 /MTd /c "%VCToolsInstallDir%\modules\std.ixx"
2. import std instead of import '''<iostream>'''
3. cl /std:c++latest /EHsc /nologo /W4 /MTd importExample.cpp std.obj
