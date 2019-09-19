# float_stuff
Repository for work on adding float compatibility with exch2 in the MITgcm

In order to run with floats:

1. The MITgcm code tree to use is at https://github.com/cspencerjones/MITgcm/tree/pkg_flt_02. Please do all pull requests to this version of the code and I will do a final PR to the core MITgcm. 
2. Compile using the files in the 'code' directory of this repository. You will obviously need to replace the build-options file with your own.
3. Run forwards using standard ECCOr4v3 input, plus the two files in the 'extra_input' directory.
