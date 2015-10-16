Fall 2015

This folder contains the tool library and post-processing script to allow you to
cut parts designed in SolidWorks on the IDeATe CNT Motion CNC router.  These
files can be used by the HSMWorks CAM system integrated into our SolidWorks
installations to program tool paths and generate G-code files to operate the
machine.

To add the tool library to your HSMWorks installation:

1. Check out this repository to your local disk.
2. From within SolidWorks, select CAM/Tool Library to open the library interface.
3. Right-click on any folder with the upper-left tree view, and select "Add Library Folder."
4. Select the folder containing this file you are reading (physcomp-solidworks/HSMWorks).

If you need to edit the tool library, you may wish to make a duplicate first to avoid
problems with future repository updates.


To use the post-processor for generating your G-code file:

1. Create your job of cutting operations using the appropriate tool library.
2. Right-click on the job name and select Post Process.
3. In the Post Process dialog, find the folder selection field under Configuration Folder.  Click the ellipsis button to open a folder selection dialog.  Select the folder containing this file you are reading (physcomp-solidworks/HSMWorks).
4. You should see the postprocessor script appear in the drop-down under Post Configuration as "HSM_CNTMS950_IDEATE.CPS - IDeATe WinCNC".
