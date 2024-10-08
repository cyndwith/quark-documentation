Quark for ONNX
==============

There are several steps to quantize a floating-point model with
``Quark for ONNX``:

1. Load original float model
2. Set quantization configuration
3. Define datareader
4. Use the Quark API to perform in-place replacement of the model's modules with quantized module.

More details:

* `Configuring Quark for ONNX <./user_guide_config_description.html>`__
* `Adding Calibration Datasets <./user_guide_datareader.html>`__
* `Feature Description <./user_guide_feature_description.html>`__
* `Supported Datatype and OpType <./user_guide_supported_optype_datatype.html>`__
* `Accuracy Improvement <./user_guide_accuracy_improvement.html>`__
* `Optional Utilities <./user_guide_optional_utilities.html>`__
* `Tools <./user_guide_tools.html>`__

.. raw:: html

   <!-- 
   ## License
   Copyright (C) 2023, Advanced Micro Devices, Inc. All rights reserved. SPDX-License-Identifier: MIT
   -->
