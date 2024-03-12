Working !!!! :
cl.exe /EHsc /DGLEW_STATIC /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


cl.exe /Zi /EHsc /nologo /FeC:\code\signal\HelloWorld.exe C:\code\signal\HelloWorld.cpp
cl.exe /Zi /EHsc /FeC:\code\signal\HelloWorld.exe C:\code\signal\HelloWorld.cpp
.\HelloWorld.exe


cl.exe /Zi /EHsc /FeC:\code\signal\HelloWorld.exe C:\code\signal\HelloWorld.cpp glfw3.lib


cl example.cpp /I"path_to_glfw_include_directory" /link "path_to_glfw_library\glfw3.lib" /SUBSYSTEM:CONSOLE


cl.exe C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link  "C:\code\signal\glfw\lib-vc2019\glfw3.lib"


cl.exe C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link /LIBPATH:"C:\code\signal\glfw\lib-vc2019\glfw3.dll" "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" 

cl.exe C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" 

cl.exe C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link /LIBPATH:"C:\code\signal\glfw\lib-vc2019\glfw3.dll" "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" 


Working:
cl.exe C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link  "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib"



cl.exe /EHsc C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" "C:\code\signal\glew\include\" /link  "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\code\signal\glew\lib\Release\Win32\glew32.lib"

cl.exe /EHsc C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glew\include\GL" /I "C:\code\signal\glfw\include" /link  "C:\code\signal\glfw\lib-vc2019\glfw3dll.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\code\signal\glew\lib\Release\Win32\glew32.lib"

cl.exe /EHsc C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glew\include\GL" /I "C:\code\signal\glfw\include" /link "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

cl.exe /EHsc C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


cl.exe /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

cl.exe /EHsc /MT /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib" C:\code\signal\HelloWorld.cpp

cl.exe /EHsc /MT C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

cl.exe /EHsc /MT C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2017\glfw3.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


Working:
cl.exe /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /LIBPATH:C:\code\signal\glfw\lib-vc2019 /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

cl.exe /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


cl.exe /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

Working:
cl.exe /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


cl.exe /GLEW_STATIC /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"

Working !!" :
cl.exe /DGLEW_STATIC /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"


Working !!!! :
cl.exe /EHsc /DGLEW_STATIC /DEFAULTLIB:Yes C:\code\signal\HelloWorld.cpp /I "C:\code\signal\glfw\include" /I "C:\code\signal\glew\include" /link /NODEFAULTLIB:MSVCRT "C:\code\signal\glew\lib\Release\Win32\glew32s.lib" "C:\code\signal\glfw\lib-vc2019\glfw3_mt.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\opengl32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\User32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Gdi32.lib" "C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x86\Shell32.lib"
