# eagle2tvm802
an Eagle Layout to TVM802 Pick and Place converter

this program loads eagle mnt and mnb files (which are exported with the standard ULP: mountsmd)
assignes a stack/tray list to the components
and generates a TVM802 compatible pick&place file.

It allows easy editing and automatic processing
of Stacks, Nozzle, Vision... and all other settings.

The software is written in C# with visual studio 2015,
the compiled and ready-to-use program can be found in the bin/release
folder, name: eagle2tvm.exe

The program is translated into English and German,
the user instructions are shown in the windows.

changes V1.10:
automatic Fiducial coordinate import from eagle board.
See Fiducial Window for details.

changes V1.12:
Nozzles may be set to 1, 2 or 1/2.

=======================================================
we support EAGLE V7.

we DO NOT support EAGLE V8 until autodesk changes the unacceptable licensing conditions.
=======================================================

