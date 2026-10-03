# Mitsuba as a godot-sandbox guest (parked)

Partial work toward `mitsuba.elf`: `scalar_rgb` only, plugins linked statically (`MI_STATIC_PLUGINS`), image I/O without JPEG and OpenEXR (`MI_GUEST`), and `generated/` holding the `configure.py` output for that variant. No guest CMake, link or gate yet.
