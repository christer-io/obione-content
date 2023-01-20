## Can I write proprietary code that links to a shared library that's open source?

### Answer:

Sometimes you can; it depends on the Open Source license. Authors often want you to be able to do this, so most shared libraries are licensed under a permissive license or one that allows linking under certain circumstances (e.g., the LGPL). 

A very small number of libraries use the GPL, which only allows linking with proprietary works if the licensor grants an explicit exception. Thus, you are wise to check the licenses that your program links to. The community expects that all code linked to GPL code will be licensed under the GPL, even if the link is made at runtime using a shared library.
