add_header_library(
  errno_setter_matcher
  HDRS
    ErrnoSetterMatcher.h
)

add_custom_target(check-libc)
add_custom_target(exhaustive-check-libc)

add_subdirectory(config)
add_subdirectory(loader)
add_subdirectory(src)
add_subdirectory(utils)
