
# Example of how to make CapsLock key (scancode 58) produce ESCAPE keycode:
# map key 58  ESCAPE

# Default scancode to keycode mapping can be found at
# https://android.googlesource.com/platform/frameworks/base/+/master/data/keyboards/Generic.kl
# Some scancode to keycode mapping from Generic.kl:
# key 29  CTRL_LEFT
# key 56  ALT_LEFT
# key 58  CAPS_LOCK
# key 97  CTRL_RIGHT
# key 99  SYSRQ
# key 100 ALT_RIGHT
# key 125 META_LEFT
# key 126 META_RIGHT
# This is KCM (not KL) file, so 'map' directive must be added before the statements above to make them work here.


# Example of how to add a ctrl+shift+3 shortcut for screenshot:
# key 3 {
#     label:                              '3'
#     base:                               '3'
#     shift:                              '#'
#     ctrl+shift:                         fallback SYSRQ
# }

# Keycodes can be found at
# https://android.googlesource.com/platform/frameworks/native/+/master/include/android/keycodes.h
