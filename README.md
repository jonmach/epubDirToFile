# epubDirToFile
Convert an iTunes/Books epub directory to a single file

When you import an epub into Books (on the Mac), it takes the single epub file and extacts it to a directory.  If you need to take this content and move it to a different e-reader, or re-import it into another environment, you need to repackage the epub directory into a single file.

This is a Jupyter Notebook.

This routine simply descends into each epub directory, compressing it into zip format and then copying the contents to a file with the original name that is portable.
