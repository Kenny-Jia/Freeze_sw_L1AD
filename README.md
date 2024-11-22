# Freeze_sw_L1AD
## hls4ml edelweiss 0.8.1 with modification for QDenseBatchnorm
https://github.com/fastmachinelearning/hls4ml/pull/718
	1. hls4ml/backends/vivado/passes/core_templates.py: line 3, 32, 48
	2. hls4ml/converters/keras/core.py: line 87
	3. hls4ml/converters/keras/qkeras.py: line 179-189
	4. hls4ml/model/layers.py: line 407-451, 1382
## qkeras 0.9.0 with QDenseBatchnorm
https://github.com/google/qkeras/pull/74
	1. qkeras/__init__.py: line 36
	2. qkeras/qdense_batchnorm.py: whole file
	3. qkeras/utils.py: line 41, 98, 138, 198, 856
test file modification is optional

