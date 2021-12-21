# Plugins

## else

Miscellaneous plugins

  * [accum](opcodes/accum.md): Simple accumulator of scalar values
  * [atstop](opcodes/atstop.md): Schedule an instrument at the end of the current instrument
  * [bisect](opcodes/bisect.md): Returns the fractional index of a value within a sorted array / tab
  * [crackle](opcodes/crackle.md): generates noise based on a chaotic equation
  * [deref](opcodes/deref.md): Dereference a previously created reference to a variable
  * [detectsilence](opcodes/detectsilence.md): Detect when input falls below an amplitude threshold
  * [diode_ringmod](opcodes/diode_ringmod.md): A ring modulator with optional non-linearities
  * [extendarray](opcodes/extendarray.md): Extend one array with the contents of a second array, in place
  * [fileexists](opcodes/fileexists.md): Returns 1 if a file exists and can be read
  * [findarray](opcodes/findarray.md): Find an element in an array
  * [frac2int](opcodes/frac2int.md): Convert the fractional part of a number into an integer
  * [ftfill](opcodes/ftfill.md): create a table and fill it with values (like fillarray but for f-tables)
  * [ftfind](opcodes/ftfind.md): Find an element in a table
  * [ftnew](opcodes/ftnew.md): creates a new table of a given size
  * [ftsetparams](opcodes/ftsetparams.md): Set metadata parameters of a table, as if it was loaded via GEN1
  * [initerror](opcodes/initerror.md): Throws an error message at init
  * [interp1d](opcodes/interp1d.md): Interpolate between elements of an array/table
  * [lfnoise](opcodes/lfnoise.md): low frequency, band-limited noise
  * [linenv](opcodes/linenv.md): A triggerable linear envelope with sustain segment
  * [loadnpy](opcodes/loadnpy.md): Load an array (of any number of dimensions) saved as a .npy file
  * [memview](opcodes/memview.md): Create a view into a table or another array
  * [panstereo](opcodes/panstereo.md): Stereo signal balancer
  * [perlin3](opcodes/perlin3.md): gradient noise sound generator
  * [pread](opcodes/pread.md): Read pfield values from any active instrument instance
  * [pwrite](opcodes/pwrite.md): Modify pfield values of an active instrument instance
  * [ramptrig](opcodes/ramptrig.md): A triggerable ramp between 0 and 1
  * [ref](opcodes/ref.md): Get a reference to a variable
  * [refvalid](opcodes/refvalid.md): Queries if a reference is valid
  * [schmitt](opcodes/schmitt.md): A schmitt trigger (a comparator with hysteresis).
  * [setslice](opcodes/setslice.md): Set a slice of an array to a given value
  * [sigmdrive](opcodes/sigmdrive.md): Analog "soft clipping" distortion by applying non-linear transfer functions.
  * [standardchaos](opcodes/standardchaos.md): Standard map chaotic generator
  * [throwerror](opcodes/throwerror.md): Throws an error message at performance or init
  * [uniqinstance](opcodes/uniqinstance.md): Return an fractional instrument number which is not in use
  * [zeroarray](opcodes/zeroarray.md): Zero all elements in an array

## pathtools

Cross-platform path handling and string opcodes

  * [findFileInPath](opcodes/findFileInPath.md): Find a file inside the search paths of the csound environment
  * [getEnvVar](opcodes/getEnvVar.md): Get the value of an environment variable
  * [pathAbsolute](opcodes/pathAbsolute.md): Returns the absolute path of a file
  * [pathIsAbsolute](opcodes/pathIsAbsolute.md): Returns 1 if the path of a file is absolute
  * [pathJoin](opcodes/pathJoin.md): Join two parts of a path according to the current platform
  * [pathNative](opcodes/pathNative.md): Convert a path to its native version
  * [pathSplit](opcodes/pathSplit.md): Split a path into directory and basename
  * [pathSplitExt](opcodes/pathSplitExt.md): Split a path into prefix and extension
  * [pathSplitExtk](opcodes/pathSplitExtk.md): Split a path into prefix and extension at performance time
  * [pathSplitk](opcodes/pathSplitk.md): Split a path into directory and basename at perf-time
  * [scriptDir](opcodes/scriptDir.md): Get the directory of the loaded orc/csd file
  * [strjoin](opcodes/strjoin.md): Concatenate any number of strings
  * [strsplit](opcodes/strsplit.md): Split a string at a given separator
  * [sysPlatform](opcodes/sysPlatform.md): Get a string description of the current system platform
