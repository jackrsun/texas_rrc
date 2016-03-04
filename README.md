Files obtained for the texas railroad commission for oil and gas districts 1 and 2 are in the data directory. These are the 'production' files -- one each for oil and gas, I believe. An RRC rep said that pdf100 is oil and pdf101 is gas. 

They are provided as zipped EBCDIC files: the original readme says this:


                           Mainframe Data

                          Data Translation:
                          -----------------
 RRC Mainframe files reside on the mainframe in EBCDIC format.  Some
 data fields are packed or compressed (e.g. COMP or COMP-3 in COBOL).
 In order to maintain the correct contents of the data fields all
 files containing these types of fields are transferred in binary
 format.  Thus the transferred file retains the EBCDIC format.  In
 order to process an EBCDIC file correctly it must be loaded to a
 computer that processes the EBCDIC format or it must be translated to
 a readable format using software that can be found on the internet.
 Files not containing COMP or COMP-3 fields are transferred using an
 ASCII translation.  RRC uses the following file extensions for
 transferred mainframe files:

        Extension    File Format
        ---------    -----------
        .ebc         EBCDIC format
        .ebc.Z       EBCDIC format compressed
        .txt         ASCII format
        .txt.Z       ASCII format compressed



                          File Compression:
                          -----------------
 Files with an uppercase Z extension are compressed using the standard
 UNIX system compression command.  These files may be in EBCDIC or
 ASCII format after compression.  Standard compression or "zipping"
 software can be used to restore the file to it's original size.