# [Docs.rs](https://docs.rs/gl_constants)

# gl_constants

Declares OpenGL and OpenGL ES enumerated constant values.

The one constant that's missing from this crate is `GL_ACTIVE_PROGRAM_EXT`,
which is part of the `GL_EXT_separate_shader_objects` extension. It's the only
constant which has a *different* value in OpenGL compared to OpenGL ES. All
other constants are the same value in both APIs.
