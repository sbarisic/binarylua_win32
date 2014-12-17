binarylua_win32
===============

Garry's Mod module that adds a function to load precompiled glua chunks


It registers function binaryload(s), s can either be lua source code or precompiled chunk.
Returns function (loads bytecode or compiles and loads source)
when input s is valid or nil when it's invalid.