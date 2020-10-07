# TODOs

- Make build work on Windows again
- Consider whether to follow OMS in its install/platform pattern or not.
  Needs changes in CMakeLists.txt
- Improve finding OMS dependencies (FindOMSimulatorLibrary.cmake)
  particularly, make cmake fail if it doesn't find it
- Understand -static-libgcc issue in OMS, see
  `set(STATIC_LIBGCC "-static-libgcc")` in OMS's CMakeLists.txt
- Understand differences in how OMS loads python lib

## Issues

- Check GetGitRevisionDescription handling and compare against OMS, particular
  check documentation build problem with current revision handling
