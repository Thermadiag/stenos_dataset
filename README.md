Test/benchmark dataset for the <a href="https://github.com/Thermadiag/stenos">stenos</a> library
------------------------------------------------------------------------------------------------

This repository contains several data files used to test and/or benchmark binary compression libraries like <a href="https://github.com/Thermadiag/stenos">stenos</a> or <a href="https://github.com/Blosc/c-blosc2/tree/main">blosc</a>.

All data files are in the *dataset* folder. Filenames start with a number which is the number of bytes par sample, followed by an underscore.
All files are in raw binary format, except the ones with the *.txt* suffix (ascii format).

Current content:
-	**1_javascript.js**: Plain JavaScript file (1 byte per element)
-	**1_tree_r.txt**: Red component of an image (1 byte per element)
-	**2_DIV.txt**: Infrared image (degree Celsius) of the WEST tokamak (2 bytes per element)
-	**2_LH1.txt**: Infrared image (degree Celsius) of the WEST tokamak (2 bytes per element)
-	**2_WA.txt**: Infrared image (degree Celsius) of the WEST tokamak (2 bytes per element)
-	**2_PI240_15s.wav**: Raw audio file(2 bytes per element)
-	**12_953134_float3.bin**: <a href="https://github.com/aras-p/float_compr_tester/tree/main/data">Water/snow simulation</a> (12 bytes per element)
-	**16_1024_sq_float4.bin**: <a href="https://github.com/aras-p/float_compr_tester/tree/main/data">Water/snow simulation</a> (16 bytes per element)
-	**16_2048_sq_float4.bin**: <a href="https://github.com/aras-p/float_compr_tester/tree/main/data">Water/snow simulation</a> (16 bytes per element)
-	**16_232630_float4.bin**: <a href="https://github.com/aras-p/float_compr_tester/tree/main/data">Water/snow simulation</a> (16 bytes per element)
-	**8_SHYBPTOT.txt**: sensor data from the WEST tokamak (1d + time) (8 bytes per element)
-	**8_UTOR.txt**: sensor data from the WEST tokamak (1d + time) (8 bytes per element)
