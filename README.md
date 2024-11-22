# Freeze_sw_L1AD
## hls4ml edelweiss 0.8.1 with modification for QDenseBatchnorm
https://github.com/fastmachinelearning/hls4ml/pull/718
- hls4ml/backends/vivado/passes/core_templates.py: line 3, 32, 48
- hls4ml/converters/keras/core.py: line 87
- hls4ml/converters/keras/qkeras.py: line 179-189
- hls4ml/model/layers.py: line 407-451, 1382
## qkeras 0.9.0 with QDenseBatchnorm
https://github.com/google/qkeras/pull/74
- qkeras/__init__.py: line 36
- qkeras/qdense_batchnorm.py: whole file
- qkeras/utils.py: line 41, 98, 138, 198, 856
test file modification is optional

