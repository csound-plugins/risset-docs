# Plugins

## beosc

Band-enhanced oscillators implementing the sine+noise synthesis model

  * [beadsynt](opcodes/beadsynt.md): Band-Enhanced Oscillator-Bank
  * [beosc](opcodes/beosc.md): Band-Enhanced Oscillator
  * [getrowlin](opcodes/getrowlin.md): opy a row from a 2D array or table, with interpolation between rows
  * [tabrowlin](opcodes/tabrowlin.md): Copy a row from an f-table to another, interpolating between rows

## chua

Implementation of a Chua oscillator

  * [chuap](opcodes/chuap.md): Simulates Chua's oscillator

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
  * [mtro](opcodes/mtro.md): an accurate version of metro
  * [nametoinstrnum](opcodes/nametoinstrnum.md): Returns the number of a named instrument
  * [panstereo](opcodes/panstereo.md): Stereo signal balancer
  * [perlin3](opcodes/perlin3.md): gradient noise sound generator
  * [pread](opcodes/pread.md): Read pfield values from any active instrument instance
  * [presetinterp](opcodes/presetinterp.md): Interpolates between presets placed in a 2D plane
  * [pwrite](opcodes/pwrite.md): Modify pfield values of an active instrument instance
  * [pwriten](opcodes/pwriten.md): Modify pfield values of an active instrument instance created via nstance
  * [ramptrig](opcodes/ramptrig.md): A triggerable ramp between 0 and 1
  * [ref](opcodes/ref.md): Get a reference to a variable
  * [refvalid](opcodes/refvalid.md): Queries if a reference is valid
  * [schmitt](opcodes/schmitt.md): A schmitt trigger (a comparator with hysteresis).
  * [setslice](opcodes/setslice.md): Set a slice of an array to a given value
  * [sigmdrive](opcodes/sigmdrive.md): Analog "soft clipping" distortion by applying non-linear transfer functions.
  * [standardchaos](opcodes/standardchaos.md): Standard map chaotic generator
  * [throwerror](opcodes/throwerror.md): Throws an error message at performance or init
  * [uniqinstance](opcodes/uniqinstance.md): Return an fractional instrument number which is not in use
  * [vowelsdb](opcodes/vowelsdb.md): A database of vowel sounds
  * [weightedsum](opcodes/weightedsum.md): Weighted sum of multiple 1D arrays, or the rows of a 2D array
  * [zeroarray](opcodes/zeroarray.md): Zero all elements in an array
  * [zerocrossing](opcodes/zerocrossing.md): Outputs a frequency based on the number of zero-crossings per second.

## hdf5

Read/Write signals and arrays to/from an hdf5 file

  * [hdf5read](opcodes/hdf5read.md): Read signals and arrays from an hdf5 file.
  * [hdf5write](opcodes/hdf5write.md): Write signals and arrays to an hdf5 file.

## jsfx

jsfx support for csound

  * [jsfx](opcodes/jsfx.md): Instantiates and runs a jsfx script
  * [jsfx_getslider](opcodes/jsfx_getslider.md): Gets a slider value of a jsfx instance
  * [jsfx_new](opcodes/jsfx_new.md): Instantiates a jsfx script
  * [jsfx_play](opcodes/jsfx_play.md): Processes audio through a jsfx script
  * [jsfx_setslider](opcodes/jsfx_setslider.md): Sets the slider values of a jsfx script
  * [tubeharmonics](opcodes/tubeharmonics.md): A distortion with control for odd/even harmonics

## klib

A hashtable for csound

  * [dict_del](opcodes/dict_del.md): Remove a key:value pair from a hashtable
  * [dict_dump](opcodes/dict_dump.md): Dumps the contents of this dict as a string
  * [dict_exists](opcodes/dict_exists.md): Returns 1 if the dict exists, 0 otherwise
  * [dict_free](opcodes/dict_free.md): Free a hashtable
  * [dict_get](opcodes/dict_get.md): Get a value from a hashtable
  * [dict_geti](opcodes/dict_geti.md): Get a string value from a hashtable at init time
  * [dict_iter](opcodes/dict_iter.md): Iterate over the key-value pairs of a dict
  * [dict_loadstr](opcodes/dict_loadstr.md): Creates and fills a new dict from a string definition
  * [dict_new](opcodes/dict_new.md): Create a hashtable
  * [dict_print](opcodes/dict_print.md): Prints the contents of a dict
  * [dict_query](opcodes/dict_query.md): Query different properties of a dict
  * [dict_set](opcodes/dict_set.md): Set a value from a hashtable
  * [dict_size](opcodes/dict_size.md): Returns the number of key:value pairs in a dict
  * [pool_at](opcodes/pool_at.md): Returns the item of a pool at a given index
  * [pool_capacity](opcodes/pool_capacity.md): Returns the capacity of a pool
  * [pool_gen](opcodes/pool_gen.md): Create a pool and fill it with values
  * [pool_isfull](opcodes/pool_isfull.md): Returns 1 if the pool is full
  * [pool_new](opcodes/pool_new.md): Create an empty  pool
  * [pool_pop](opcodes/pool_pop.md): Pop (get) an item from a pool
  * [pool_push](opcodes/pool_push.md): Push an item into a pool
  * [pool_size](opcodes/pool_size.md): Returns the size of a pool
  * [sderef](opcodes/sderef.md): Retrieves a read-only string from the cache
  * [sref](opcodes/sref.md): Insert a string into a global registry and return a reference to it

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

## poly

Multiple (parallel or sequential) instances of an opcode

  * [defer](opcodes/defer.md): Run an opcode at the end of current event
  * [poly](opcodes/poly.md): `poly` creates and controls multiple parallel version of an opcode
  * [poly0](opcodes/poly0.md): `poly0` creates and controls multiple parallel version of an opcode with no outputs
  * [polyseq](opcodes/polyseq.md): `polyseq` creates and controls multiple **sequential** version of an opcode

## python

Opcodes to interact with an embedded python interpreter

  * [pyrun](opcodes/pyrun.md): Run a Python statement or block of statements

## risset

Opcodes to access risset package metadata

  * [risset](opcodes/risset.md): Get information from risset's package manager

## sndmeta

opcodes using libsndfile

  * [filereadmeta](opcodes/filereadmeta.md): Read metadata from a soundfile

## vst3

Host vst3 plugins in csound

  * [vst3audio](opcodes/vst3audio.md): Sends audio to, and/or receives audio from, a VST3 plugin.
  * [vst3info](opcodes/vst3info.md): Prints information about the plugin
  * [vst3init](opcodes/vst3init.md): loads a VST3 plugin for use with the other vst3-opcodes
  * [vst3midi](opcodes/vst3midi.md): Sends raw MIDI messages to a VST3 plugin.
  * [vst3note](opcodes/vst3note.md): Sends a single note with a specified duration to a VST3 plugin
  * [vst3paramget](opcodes/vst3paramget.md): Gets the current value of a single parameter from a VST3
  * [vst3paramset](opcodes/vst3paramset.md): Sets the current value of a single parameter in a VST3 plugin.
  * [vst3presetload](opcodes/vst3presetload.md): Loads a preset from a file
  * [vst3presetsave](opcodes/vst3presetsave.md): Saves a plugin preset to a file.
  * [vst3tempo](opcodes/vst3tempo.md): Changes the tempo in a VST3 plugin.
