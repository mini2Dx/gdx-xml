# gdx-xml
LibGDX XML classes extracted into a standalone library (i.e. no OpenGL, LWJGL, etc. required)

Mechanism
----------------------

The gradle build will checkout a specific version of libgdx, copy the compression source files into src/main/java, package renamed from _com.badlogic.gdx.utils_ to _org.mini2Dx.gdx.xml_ and compile the standalone jar.

Usage
----------------------

```gradle
compile "org.mini2Dx:gdx-xml:1.9.11"
```

This project's only dependency is [gdx-collections](https://github.com/mini2Dx/gdx-collections).

Included Classes
----------------------

 * BufferUtils.java
 * SerializationException.java
 * StreamUtils
 * XmlReader
 * XmlWriter
