# CUDNN API supported by MIOPEN

## **1. CUDNN Data types**

|**CUDA**|**A**|**D**|**C**|**R**|**MIOPEN**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`CUDNN_16BIT_INDICES`|6.0.0|9.0.0| | |`MIOPEN_16BIT_INDICES`| | | | | |
|`CUDNN_32BIT_INDICES`|6.0.0|9.0.0| | |`MIOPEN_32BIT_INDICES`| | | | | |
|`CUDNN_64BIT_INDICES`|6.0.0|9.0.0| | |`MIOPEN_64BIT_INDICES`| | | | | |
|`CUDNN_8BIT_INDICES`|6.0.0|9.0.0| | |`MIOPEN_8BIT_INDICES`| | | | | |
|`CUDNN_ACTIVATION_CLIPPED_RELU`|4.0.0|9.0.0| | |`miopenActivationCLIPPEDRELU`| | | | | |
|`CUDNN_ACTIVATION_ELU`|6.0.0|9.0.0| | |`miopenActivationELU`| | | | | |
|`CUDNN_ACTIVATION_IDENTITY`|7.1.3|9.0.0| | |`miopenActivationPASTHRU`| | | | | |
|`CUDNN_ACTIVATION_RELU`|1.0.0|9.0.0| | |`miopenActivationRELU`| | | | | |
|`CUDNN_ACTIVATION_SIGMOID`|1.0.0|9.0.0| | | | | | | | |
|`CUDNN_ACTIVATION_SWISH`|8.2.0|9.0.0| | | | | | | | |
|`CUDNN_ACTIVATION_TANH`|1.0.0|9.0.0| | |`miopenActivationTANH`| | | | | |
|`CUDNN_ATTN_DISABLE_PROJ_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_ATTN_ENABLE_PROJ_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_ATTN_QUERYMAP_ALL_TO_ONE`|7.5.0| | | | | | | | | |
|`CUDNN_ATTN_QUERYMAP_ONE_TO_ONE`|7.5.0| | | | | | | | | |
|`CUDNN_ATTN_WKIND_COUNT`|7.6.3| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_COMP_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_CONV_MODE`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_DILATIONS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_FILTER_STRIDES`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_POST_PADDINGS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_PRE_PADDINGS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_CONVOLUTION_SPATIAL_DIMS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINECFG_ENGINE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINECFG_INTERMEDIATE_INFO`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINECFG_KNOB_CHOICES`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINECFG_SHARED_MEMORY_USED`|9.2.0| | | | | | | | | |
|`CUDNN_ATTR_ENGINECFG_WORKSPACE_SIZE`|9.2.0| | | | | | | | | |
|`CUDNN_ATTR_ENGINEHEUR_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINEHEUR_OPERATION_GRAPH`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINEHEUR_RESULTS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINEHEUR_SM_COUNT_TARGET`|8.9.5| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_BEHAVIOR_NOTE`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_GLOBAL_INDEX`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_KNOB_INFO`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_LAYOUT_INFO`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_NUMERICAL_NOTE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_OPERATION_GRAPH`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_ENGINE_SM_COUNT_TARGET`|8.9.5| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_COMPUTED_INTERMEDIATE_UIDS`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_ENGINE_CONFIG`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_HANDLE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_JSON_REPRESENTATION`|8.4.0| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_RUN_ONLY_INTERMEDIATE_UIDS`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_EXECUTION_PLAN_WORKSPACE_SIZE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_INTERMEDIATE_INFO_DEPENDENT_ATTRIBUTES`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_INTERMEDIATE_INFO_DEPENDENT_DATA_UIDS`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_INTERMEDIATE_INFO_SIZE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_INTERMEDIATE_INFO_UNIQUE_ID`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_KNOB_CHOICE_KNOB_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_KNOB_CHOICE_KNOB_VALUE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_KNOB_INFO_MAXIMUM_VALUE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_KNOB_INFO_MINIMUM_VALUE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_KNOB_INFO_STRIDE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_KNOB_INFO_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_LAYOUT_INFO_TENSOR_UID`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_LAYOUT_INFO_TYPES`|8.0.2| | | | | | | | | |
|`CUDNN_ATTR_MATMUL_COMP_TYPE`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_MATMUL_PADDING_VALUE`|8.9.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATIONGRAPH_ENGINE_GLOBAL_COUNT`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATIONGRAPH_HANDLE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATIONGRAPH_OPS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_BN_SCALE_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_DBN_BIAS_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_DBN_SCALE_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_DY_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_EQ_BIAS`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_EQ_DY_SCALE_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_EQ_X_SCALE_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_INVSTD_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_MATH_PREC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_MEAN_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_BWD_WEIGHTS_X_DESC`|8.2.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_ACCUM_COUNT_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_BIAS_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_EPSILON_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_EQ_BIAS_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_EQ_SCALE_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_EXP_AVERATE_FACTOR_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_MATH_PREC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_PREV_RUNNING_MEAN_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_PREV_RUNNING_VAR_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_SAVED_INV_STD_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_SAVED_MEAN_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_SCALE_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_STATS_MODE`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_UPDATED_RUNNING_MEAN_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_UPDATED_RUNNING_VAR_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_Y_SQ_SUM_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_BN_FINALIZE_Y_SUM_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONCAT_AXIS`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONCAT_INPLACE_INDEX`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONCAT_INPUT_DESCS`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONCAT_OUTPUT_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_ALPHA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_BETA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_CONV_DESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_DX`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_DY`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_DATA_W`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_ALPHA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_BETA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_CONV_DESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_DW`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_DY`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_BWD_FILTER_X`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_ALPHA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_BETA`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_CONV_DESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_W`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_X`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_CONVOLUTION_FORWARD_Y`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_GENSTATS_MATH_PREC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_GENSTATS_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_GENSTATS_SQSUMDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_GENSTATS_SUMDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_GENSTATS_XDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_ADESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_BDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_CDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_GEMM_K_OVERRIDE_DESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_GEMM_M_OVERRIDE_DESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_GEMM_N_OVERRIDE_DESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_MATMUL_IRREGULARLY_STRIDED_BATCH_COUNT`|8.1.0|9.0.0| | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_DBIAS_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_DSCALE_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_DXDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_DYDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_EPSILON_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_INV_VARIANCE_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_MEAN_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_MODE`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_PEER_STAT_DESCS`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_SCALE_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_BWD_XDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_BIAS_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_EPSILON_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_EXP_AVG_FACTOR_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_INPUT_RUNNING_MEAN_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_INPUT_RUNNING_VAR_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_INV_VARIANCE_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_MEAN_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_MODE`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_OUTPUT_RUNNING_MEAN_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_OUTPUT_RUNNING_VAR_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_PEER_STAT_DESCS`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_PHASE`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_SCALE_DESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_XDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_NORM_FWD_YDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_ALPHA1`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_ALPHA2`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_BDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_DXDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_DYDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_PW_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_TDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_XDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_POINTWISE_YDESC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_REDUCTION_DESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_REDUCTION_XDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_REDUCTION_YDESC`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_ALPHA`|8.3.0|9.0.0| | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_BETA`|8.3.0|9.0.0| | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_DESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_DXDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_DYDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_IDXDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_XDESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_BWD_YDESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_ALPHA`|8.3.0|9.0.0| | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_BETA`|8.3.0|9.0.0| | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_DESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_IDXDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_XDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESAMPLE_FWD_YDESC`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESHAPE_XDESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RESHAPE_YDESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RNG_DESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RNG_OFFSET_DESC`|8.8.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RNG_SEED`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_RNG_YDESC`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_SIGNAL_FLAGDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_SIGNAL_MODE`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_SIGNAL_VALUE`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_SIGNAL_XDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_OPERATION_SIGNAL_YDESC`|8.5.0| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_AXIS`|8.4.0| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_ELU_ALPHA`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_MATH_PREC`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_NAN_PROPAGATION`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_RELU_LOWER_CLIP`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_RELU_LOWER_CLIP_SLOPE`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_RELU_UPPER_CLIP`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_SOFTPLUS_BETA`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_POINTWISE_SWISH_BETA`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_REDUCTION_COMP_TYPE`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_REDUCTION_OPERATOR`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_COMP_TYPE`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_NAN_PROPAGATION`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_PADDING_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_POST_PADDINGS`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_PRE_PADDINGS`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_SPATIAL_DIMS`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_STRIDES`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RESAMPLE_WINDOW_DIMS`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_BERNOULLI_DIST_PROBABILITY`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_DISTRIBUTION`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_NORMAL_DIST_MEAN`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_NORMAL_DIST_STANDARD_DEVIATION`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_UNIFORM_DIST_MAXIMUM`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_RNG_UNIFORM_DIST_MINIMUM`|8.7.0| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_BYTE_ALIGNMENT`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_DATA_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_DIMENSIONS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_IS_BY_VALUE`|8.1.0| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_IS_VIRTUAL`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_RAGGED_OFFSET_DESC`|8.9.0| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_REORDERING_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_STRIDES`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_UNIQUE_ID`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_VECTORIZED_DIMENSION`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_TENSOR_VECTOR_COUNT`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_VARIANT_PACK_DATA_POINTERS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_VARIANT_PACK_INTERMEDIATES`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_VARIANT_PACK_UNIQUE_IDS`|8.0.1| | | | | | | | | |
|`CUDNN_ATTR_VARIANT_PACK_WORKSPACE`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_CONVOLUTION_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_ENGINECFG_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_ENGINEHEUR_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_ENGINE_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_EXECUTION_PLAN_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_INTERMEDIATE_INFO_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_KNOB_CHOICE_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_KNOB_INFO_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_LAYOUT_INFO_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_MATMUL_DESCRIPTOR`|8.1.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATIONGRAPH_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_BN_BWD_WEIGHTS_DESCRIPTOR`|8.2.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_BN_FINALIZE_STATISTICS_DESCRIPTOR`|8.1.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_CONCAT_DESCRIPTOR`|8.5.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_CONVOLUTION_BACKWARD_DATA_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_CONVOLUTION_BACKWARD_FILTER_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_CONVOLUTION_FORWARD_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_GEN_STATS_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_MATMUL_DESCRIPTOR`|8.1.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_NORM_BACKWARD_DESCRIPTOR`|8.5.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_NORM_FORWARD_DESCRIPTOR`|8.5.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_POINTWISE_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_REDUCTION_DESCRIPTOR`|8.1.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_RESAMPLE_BWD_DESCRIPTOR`|8.3.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_RESAMPLE_FWD_DESCRIPTOR`|8.3.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_RESHAPE_DESCRIPTOR`|8.7.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_RNG_DESCRIPTOR`|8.7.0| | | | | | | | | |
|`CUDNN_BACKEND_OPERATION_SIGNAL_DESCRIPTOR`|8.5.0| | | | | | | | | |
|`CUDNN_BACKEND_POINTWISE_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_REDUCTION_DESCRIPTOR`|8.1.0| | | | | | | | | |
|`CUDNN_BACKEND_RESAMPLE_DESCRIPTOR`|8.3.0| | | | | | | | | |
|`CUDNN_BACKEND_RNG_DESCRIPTOR`|8.7.0| | | | | | | | | |
|`CUDNN_BACKEND_TENSOR_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BACKEND_VARIANT_PACK_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_BATCHNORM_OPS_BN`|7.4.1|9.0.0| | | | | | | | |
|`CUDNN_BATCHNORM_OPS_BN_ACTIVATION`|7.4.1|9.0.0| | | | | | | | |
|`CUDNN_BATCHNORM_OPS_BN_ADD_ACTIVATION`|7.4.1|9.0.0| | | | | | | | |
|`CUDNN_BATCHNORM_PER_ACTIVATION`|4.0.0|9.0.0| | |`miopenBNPerActivation`| | | | | |
|`CUDNN_BATCHNORM_SPATIAL`|4.0.0|9.0.0| | |`miopenBNSpatial`| | | | | |
|`CUDNN_BATCHNORM_SPATIAL_PERSISTENT`|7.0.5|9.0.0| | | | | | | | |
|`CUDNN_BATCH_NORM`|8.5.0| | | | | | | | | |
|`CUDNN_BEHAVIOR_NOTE_REQUIRES_BIAS_INT8x32_REORDER`|8.3.0| | | | | | | | | |
|`CUDNN_BEHAVIOR_NOTE_REQUIRES_FILTER_INT8x32_REORDER`|8.3.0| | | | | | | | | |
|`CUDNN_BEHAVIOR_NOTE_RUNTIME_COMPILATION`|8.2.0| | | | | | | | | |
|`CUDNN_BEHAVIOR_NOTE_TYPE_COUNT`|8.2.0| | | | | | | | | |
|`CUDNN_BIDIRECTIONAL`|5.0.0| | | |`miopenRNNbidirection`| | | | | |
|`CUDNN_BN_FINALIZE_STATISTICS_INFERENCE`|8.1.0| | | | | | | | | |
|`CUDNN_BN_FINALIZE_STATISTICS_TRAINING`|8.1.0| | | | | | | | | |
|`CUDNN_BN_MIN_EPSILON`|4.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION`|1.0.0|9.0.0| | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_0`|3.0.0| | | |`miopenConvolutionBwdDataAlgoGEMM`| | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_1`|3.0.0| | | |`miopenConvolutionBwdDataAlgoDirect`| | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_COUNT`|6.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_FFT`|3.0.0| | | |`miopenConvolutionBwdDataAlgoFFT`| | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_FFT_TILING`|4.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_WINOGRAD`|5.0.0| | | |`miopenConvolutionBwdDataAlgoWinograd`| | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_ALGO_WINOGRAD_NONFUSED`|5.1.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_NO_WORKSPACE`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_PREFER_FASTEST`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_BWD_DATA_SPECIFY_WORKSPACE_LIMIT`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_0`|3.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_1`|3.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_3`|3.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_COUNT`|6.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_FFT`|3.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_FFT_TILING`|6.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_WINOGRAD`|5.1.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_ALGO_WINOGRAD_NONFUSED`|5.1.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_NO_WORKSPACE`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_PREFER_FASTEST`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_BWD_FILTER_SPECIFY_WORKSPACE_LIMIT`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_COUNT`|6.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_DIRECT`|2.0.0| | | |`miopenConvolutionFwdAlgoDirect`| | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_FFT`|3.0.0| | | |`miopenConvolutionFwdAlgoFFT`| | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_FFT_TILING`|4.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_GEMM`|2.0.0| | | |`miopenConvolutionFwdAlgoGEMM`| | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_IMPLICIT_GEMM`|2.0.0| | | |`miopenConvolutionFwdAlgoImplicitGEMM`| | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_IMPLICIT_PRECOMP_GEMM`|2.0.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_WINOGRAD`|5.0.0| | | |`miopenConvolutionFwdAlgoWinograd`| | | | | |
|`CUDNN_CONVOLUTION_FWD_ALGO_WINOGRAD_NONFUSED`|5.1.0| | | | | | | | | |
|`CUDNN_CONVOLUTION_FWD_NO_WORKSPACE`|2.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_FWD_PREFER_FASTEST`|2.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CONVOLUTION_FWD_SPECIFY_WORKSPACE_LIMIT`|2.0.0|7.6.5| |8.0.1| | | | | | |
|`CUDNN_CROSS_CORRELATION`|1.0.0|9.0.0| | | | | | | | |
|`CUDNN_CTC_LOSS_ALGO_DETERMINISTIC`|7.0.5| | | |`MIOPEN_CTC_LOSS_ALGO_DETERMINISTIC`| | | | | |
|`CUDNN_CTC_LOSS_ALGO_NON_DETERMINISTIC`|7.0.5| | | | | | | | | |
|`CUDNN_DATA_BFLOAT16`|8.1.0| | | |`miopenBFloat16`| | | | | |
|`CUDNN_DATA_BOOLEAN`|8.3.0| | | | | | | | | |
|`CUDNN_DATA_DOUBLE`|1.0.0| | | |`miopenDouble`| | | | | |
|`CUDNN_DATA_FAST_FLOAT_FOR_FP8`|8.7.0| | | | | | | | | |
|`CUDNN_DATA_FLOAT`|1.0.0| | | |`miopenFloat`| | | | | |
|`CUDNN_DATA_FP8_E4M3`|8.6.0| | | | | | | | | |
|`CUDNN_DATA_FP8_E5M2`|8.6.0| | | | | | | | | |
|`CUDNN_DATA_HALF`|3.0.0| | | |`miopenHalf`| | | | | |
|`CUDNN_DATA_INT32`|6.0.0| | | |`miopenInt32`| | | | | |
|`CUDNN_DATA_INT64`|8.1.0| | | | | | | | | |
|`CUDNN_DATA_INT8`|6.0.0| | | |`miopenInt8`| | | | | |
|`CUDNN_DATA_INT8x32`|7.2.1|9.0.0| | | | | | | | |
|`CUDNN_DATA_INT8x4`|6.0.0|9.0.0| | |`miopenInt8x4`| | | | | |
|`CUDNN_DATA_UINT8`|7.1.3| | | | | | | | | |
|`CUDNN_DATA_UINT8x4`|7.1.3|9.0.0| | | | | | | | |
|`CUDNN_DEFAULT_MATH`|7.0.5| | | | | | | | | |
|`CUDNN_DEFAULT_REORDER`|7.6.0|9.0.0| | | | | | | | |
|`CUDNN_DETERMINISTIC`|6.0.0| | | | | | | | | |
|`CUDNN_DIM_MAX`|4.0.0| | | | | | | | | |
|`CUDNN_DIVNORM_PRECOMPUTED_MEANS`|3.0.0| | | | | | | | | |
|`CUDNN_EDGE_VAL_PAD`|8.3.0| | | | | | | | | |
|`CUDNN_ERRQUERY_BLOCKING`|7.0.5| | | | | | | | | |
|`CUDNN_ERRQUERY_NONBLOCKING`|7.0.5| | | | | | | | | |
|`CUDNN_ERRQUERY_RAWCODE`|7.0.5| | | | | | | | | |
|`CUDNN_FMA_MATH`|8.0.1| | | | | | | | | |
|`CUDNN_FUSED_BN_FINALIZE_STATISTICS_INFERENCE`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_BN_FINALIZE_STATISTICS_TRAINING`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_CONV_SCALE_BIAS_ADD_ACTIVATION`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_DACTIVATION_FORK_DBATCHNORM`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_SCALE_BIAS_ACTIVATION_CONV_BNSTATS`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_SCALE_BIAS_ACTIVATION_WGRAD`|7.6.0| | | | | | | | | |
|`CUDNN_FUSED_SCALE_BIAS_ADD_ACTIVATION_GEN_BITMASK`|7.6.0| | | | | | | | | |
|`CUDNN_FWD_MODE_INFERENCE`|8.0.1| | | | | | | | | |
|`CUDNN_FWD_MODE_TRAINING`|8.0.1| | | | | | | | | |
|`CUDNN_GENSTATS_SUM_SQSUM`|8.0.1| | | | | | | | | |
|`CUDNN_GROUP_NORM`|8.5.0| | | | | | | | | |
|`CUDNN_GRU`|5.0.0| | | |`miopenGRU`| | | | | |
|`CUDNN_HEUR_MODES_COUNT`|8.0.1| | | | | | | | | |
|`CUDNN_HEUR_MODE_A`|8.3.0| | | | | | | | | |
|`CUDNN_HEUR_MODE_B`|8.0.1| | | | | | | | | |
|`CUDNN_HEUR_MODE_FALLBACK`|8.3.0| | | | | | | | | |
|`CUDNN_HEUR_MODE_INSTANT`|8.0.1| | | | | | | | | |
|`CUDNN_INSTANCE_NORM`|8.5.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_ARRAY_SIZE_PER_THREAD`|8.9.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_BLOCK_SIZE`|8.8.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_CHUNK_K`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_COUNTS`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_CTA_SPLIT_K_MODE`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_EDGE`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_IDX_MODE`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_KBLOCK`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_KERNEL_CFG`|8.1.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_LDGA`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_LDGB`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_LDGC`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_LOAD_SIZE`|8.9.5| | | | | | | | | |
|`CUDNN_KNOB_TYPE_MULTIPLY`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_NUM_C_PER_BLOCK`|8.9.0|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_OCCUPANCY`|8.9.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_REDUCTION_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SINGLEBUFFER`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_SLICED`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_SPECFILT`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_COLS`|8.9.5| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_H`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_K`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_K_BUF`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_K_SLC`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SPLIT_RS`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_STAGES`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_SWIZZLE`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILEK`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_CGA`|8.6.0|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_CGA_M`|8.6.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_CGA_N`|8.6.0| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_COLS`|8.9.5| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_ROWS`|8.9.5| | | | | | | | | |
|`CUDNN_KNOB_TYPE_TILE_SIZE`|8.0.1| | | | | | | | | |
|`CUDNN_KNOB_TYPE_USE_TEX`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_WINO_TILE`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_KNOB_TYPE_WORKSPACE`|8.4.0| | | | | | | | | |
|`CUDNN_LAYER_NORM`|8.5.0| | | | | | | | | |
|`CUDNN_LAYOUT_TYPE_COUNT`|8.0.2| | | | | | | | | |
|`CUDNN_LAYOUT_TYPE_PREFERRED_NCHW`|8.0.1| | | | | | | | | |
|`CUDNN_LAYOUT_TYPE_PREFERRED_NHWC`|8.0.2| | | | | | | | | |
|`CUDNN_LAYOUT_TYPE_PREFERRED_PAD4CK`|8.0.2| | | | | | | | | |
|`CUDNN_LAYOUT_TYPE_PREFERRED_PAD8CK`|8.0.2| | | | | | | | | |
|`CUDNN_LINEAR_INPUT`|5.0.0| | | |`miopenRNNlinear`| | | | | |
|`CUDNN_LOSS_NORMALIZATION_NONE`|7.6.0| | | | | | | | | |
|`CUDNN_LOSS_NORMALIZATION_SOFTMAX`|7.6.0| | | | | | | | | |
|`CUDNN_LRN_CROSS_CHANNEL_DIM1`|3.0.0| | | |`miopenLRNCrossChannel`| | | | | |
|`CUDNN_LRN_MAX_N`|3.0.0| | | | | | | | | |
|`CUDNN_LRN_MIN_BETA`|3.0.0| | | | | | | | | |
|`CUDNN_LRN_MIN_K`|3.0.0| | | | | | | | | |
|`CUDNN_LRN_MIN_N`|3.0.0| | | | | | | | | |
|`CUDNN_LSTM`|5.0.0| | | |`miopenLSTM`| | | | | |
|`CUDNN_MH_ATTN_K_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_MH_ATTN_K_WEIGHTS`|7.5.0| | | | | | | | | |
|`CUDNN_MH_ATTN_O_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_MH_ATTN_O_WEIGHTS`|7.5.0| | | | | | | | | |
|`CUDNN_MH_ATTN_Q_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_MH_ATTN_Q_WEIGHTS`|7.5.0| | | | | | | | | |
|`CUDNN_MH_ATTN_V_BIASES`|7.6.3| | | | | | | | | |
|`CUDNN_MH_ATTN_V_WEIGHTS`|7.5.0| | | | | | | | | |
|`CUDNN_NEG_INF_PAD`|8.3.0| | | | | | | | | |
|`CUDNN_NON_DETERMINISTIC`|6.0.0| | | | | | | | | |
|`CUDNN_NORM_ALGO_PERSIST`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_ALGO_STANDARD`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_FWD_INFERENCE`|8.5.0| | | | | | | | | |
|`CUDNN_NORM_FWD_TRAINING`|8.5.0| | | | | | | | | |
|`CUDNN_NORM_OPS_NORM`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_OPS_NORM_ACTIVATION`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_OPS_NORM_ADD_ACTIVATION`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_PER_ACTIVATION`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NORM_PER_CHANNEL`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_NOT_PROPAGATE_NAN`|4.0.0|9.0.0| | |`MIOPEN_NOT_PROPAGATE_NAN`| | | | | |
|`CUDNN_NO_REORDER`|7.6.0|9.0.0| | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_DOWN_CONVERT_INPUTS`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_FFT`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_NONDETERMINISTIC`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_REDUCED_PRECISION_REDUCTION`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_STRICT_NAN_PROP`|9.1.0| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_TENSOR_CORE`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_TYPE_COUNT`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_WINOGRAD`|8.0.1| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_WINOGRAD_TILE_13x13`|8.3.0| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_WINOGRAD_TILE_4x4`|8.3.0| | | | | | | | | |
|`CUDNN_NUMERICAL_NOTE_WINOGRAD_TILE_6x6`|8.3.0| | | | | | | | | |
|`CUDNN_OP_TENSOR_ADD`|5.0.0| | | |`miopenTensorOpAdd`| | | | | |
|`CUDNN_OP_TENSOR_MAX`|5.0.0| | | |`miopenTensorOpMax`| | | | | |
|`CUDNN_OP_TENSOR_MIN`|5.0.0| | | |`miopenTensorOpMin`| | | | | |
|`CUDNN_OP_TENSOR_MUL`|5.0.0| | | |`miopenTensorOpMul`| | | | | |
|`CUDNN_OP_TENSOR_NOT`|7.0.5| | | | | | | | | |
|`CUDNN_OP_TENSOR_SQRT`|6.0.0| | | | | | | | | |
|`CUDNN_PARAM_ACTIVATION_BITMASK_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_ACTIVATION_BITMASK_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_ACTIVATION_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_BIAS_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_DBIAS_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_DSCALE_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_EQBIAS_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_EQSCALEBIAS_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_EQSCALE_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_MODE`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_RUNNING_MEAN_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_RUNNING_VAR_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_SAVED_INVSTD_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_SAVED_MEAN_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_SCALEBIAS_MEANVAR_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_SCALE_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_Z_EQBIAS_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_Z_EQSCALEBIAS_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_BN_Z_EQSCALE_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_CONV_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DWDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DWDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DXDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DXDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DYDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DYDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DZDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_DZDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_WDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_WDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_XDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_XDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_YDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_YDESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_YSQSUM_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_YSTATS_DESC`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_YSUM_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_ZDATA_PLACEHOLDER`|7.6.0| | | | | | | | | |
|`CUDNN_PARAM_ZDESC`|7.6.0| | | | | | | | | |
|`CUDNN_POINTWISE_ABS`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_ADD`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_ADD_SQUARE`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_ATAN2`|9.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_BINARY_SELECT`|8.4.0| | | | | | | | | |
|`CUDNN_POINTWISE_CEIL`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_EQ`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_GE`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_GT`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_LE`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_LT`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_CMP_NEQ`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_COS`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_DIV`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_ELU_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_ELU_FWD`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_ERF`|8.5.0| | | | | | | | | |
|`CUDNN_POINTWISE_EXP`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_FLOOR`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_GELU_APPROX_TANH_BWD`|8.5.0| | | | | | | | | |
|`CUDNN_POINTWISE_GELU_APPROX_TANH_FWD`|8.5.0| | | | | | | | | |
|`CUDNN_POINTWISE_GELU_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_GELU_FWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_GEN_INDEX`|8.4.0| | | | | | | | | |
|`CUDNN_POINTWISE_IDENTITY`|8.5.0| | | | | | | | | |
|`CUDNN_POINTWISE_LOG`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_LOGICAL_AND`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_LOGICAL_NOT`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_LOGICAL_OR`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_MAX`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_MIN`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_MOD`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_MUL`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_NEG`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_POW`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_RECIPROCAL`|8.9.0| | | | | | | | | |
|`CUDNN_POINTWISE_RELU_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_RELU_FWD`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_RSQRT`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_SIGMOID_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_SIGMOID_FWD`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_SIN`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_SOFTPLUS_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_SOFTPLUS_FWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_SQRT`|8.0.1| | | | | | | | | |
|`CUDNN_POINTWISE_SUB`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_SWISH_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_SWISH_FWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_TAN`|8.3.0| | | | | | | | | |
|`CUDNN_POINTWISE_TANH_BWD`|8.1.0| | | | | | | | | |
|`CUDNN_POINTWISE_TANH_FWD`|8.0.1| | | | | | | | | |
|`CUDNN_POOLING_AVERAGE_COUNT_EXCLUDE_PADDING`|2.0.0|9.0.0| | | | | | | | |
|`CUDNN_POOLING_AVERAGE_COUNT_INCLUDE_PADDING`|2.0.0|9.0.0| | | | | | | | |
|`CUDNN_POOLING_MAX`|1.0.0|9.0.0| | |`miopenPoolingMax`| | | | | |
|`CUDNN_POOLING_MAX_DETERMINISTIC`|6.0.0|9.0.0| | | | | | | | |
|`CUDNN_PROPAGATE_NAN`|4.0.0|9.0.0| | |`MIOPEN_PROPAGATE_NAN`| | | | | |
|`CUDNN_PTR_16B_ALIGNED`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_ACTIVATION_BITMASK`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_BIAS`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_DBIAS`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_DSCALE`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_EQBIAS`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_EQSCALE`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_RUNNING_MEAN`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_RUNNING_VAR`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_SAVED_INVSTD`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_SAVED_MEAN`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_SCALE`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_Z_EQBIAS`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_BN_Z_EQSCALE`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_DWDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_DXDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_DYDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_DZDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_ELEM_ALIGNED`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_NULL`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_WDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_WORKSPACE`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_XDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_YDATA`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_YSQSUM`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_YSUM`|7.6.0| | | | | | | | | |
|`CUDNN_PTR_ZDATA`|7.6.0| | | | | | | | | |
|`CUDNN_REDUCE_TENSOR_ADD`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_ADD`| | | | | |
|`CUDNN_REDUCE_TENSOR_AMAX`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_AMAX`| | | | | |
|`CUDNN_REDUCE_TENSOR_AVG`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_AVG`| | | | | |
|`CUDNN_REDUCE_TENSOR_FLATTENED_INDICES`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_FLATTENED_INDICES`| | | | | |
|`CUDNN_REDUCE_TENSOR_MAX`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_MAX`| | | | | |
|`CUDNN_REDUCE_TENSOR_MIN`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_MIN`| | | | | |
|`CUDNN_REDUCE_TENSOR_MUL`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_MUL`| | | | | |
|`CUDNN_REDUCE_TENSOR_MUL_NO_ZEROS`|7.0.5|9.0.0| | | | | | | | |
|`CUDNN_REDUCE_TENSOR_NORM1`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_NORM1`| | | | | |
|`CUDNN_REDUCE_TENSOR_NORM2`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_NORM2`| | | | | |
|`CUDNN_REDUCE_TENSOR_NO_INDICES`|6.0.0|9.0.0| | |`MIOPEN_REDUCE_TENSOR_NO_INDICES`| | | | | |
|`CUDNN_RESAMPLE_AVGPOOL`|8.3.0| | | | | | | | | |
|`CUDNN_RESAMPLE_AVGPOOL_EXCLUDE_PADDING`|8.6.0| | | | | | | | | |
|`CUDNN_RESAMPLE_AVGPOOL_INCLUDE_PADDING`|8.6.0| | | | | | | | | |
|`CUDNN_RESAMPLE_BILINEAR`|8.3.0| | | | | | | | | |
|`CUDNN_RESAMPLE_MAXPOOL`|8.3.0| | | | | | | | | |
|`CUDNN_RESAMPLE_NEAREST`|8.3.0| | | | | | | | | |
|`CUDNN_RMS_NORM`|8.9.6| | | | | | | | | |
|`CUDNN_RNG_DISTRIBUTION_BERNOULLI`|8.7.0| | | | | | | | | |
|`CUDNN_RNG_DISTRIBUTION_NORMAL`|8.7.0| | | | | | | | | |
|`CUDNN_RNG_DISTRIBUTION_UNIFORM`|8.7.0| | | | | | | | | |
|`CUDNN_RNN_ALGO_COUNT`|7.1.3| | | | | | | | | |
|`CUDNN_RNN_ALGO_PERSIST_DYNAMIC`|6.0.0| | | | | | | | | |
|`CUDNN_RNN_ALGO_PERSIST_STATIC`|6.0.0| | | | | | | | | |
|`CUDNN_RNN_ALGO_PERSIST_STATIC_SMALL_H`|8.1.0| | | | | | | | | |
|`CUDNN_RNN_ALGO_STANDARD`|6.0.0| | | |`miopenRNNdefault`| | | | | |
|`CUDNN_RNN_CLIP_MINMAX`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_CLIP_NONE`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_DATA_LAYOUT_BATCH_MAJOR_UNPACKED`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_DATA_LAYOUT_SEQ_MAJOR_PACKED`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_DATA_LAYOUT_SEQ_MAJOR_UNPACKED`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_DOUBLE_BIAS`|7.5.0| | | |`miopenRNNwithBias`| | | | | |
|`CUDNN_RNN_NO_BIAS`|7.5.0| | | |`miopenRNNNoBias`| | | | | |
|`CUDNN_RNN_PADDED_IO_DISABLED`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_PADDED_IO_ENABLED`|7.2.1| | | | | | | | | |
|`CUDNN_RNN_RELU`|5.0.0| | | |`miopenRNNRELU`| | | | | |
|`CUDNN_RNN_SINGLE_INP_BIAS`|7.5.0| | | |`miopenRNNwithBias`| | | | | |
|`CUDNN_RNN_SINGLE_REC_BIAS`|7.5.0| | | |`miopenRNNwithBias`| | | | | |
|`CUDNN_RNN_TANH`|5.0.0| | | |`miopenRNNTANH`| | | | | |
|`CUDNN_SAMPLER_BILINEAR`|5.0.0| | | | | | | | | |
|`CUDNN_SCALAR_DOUBLE_BN_EPSILON`|7.6.0| | | | | | | | | |
|`CUDNN_SCALAR_DOUBLE_BN_EXP_AVG_FACTOR`|7.6.0| | | | | | | | | |
|`CUDNN_SCALAR_INT64_T_BN_ACCUMULATION_COUNT`|7.6.0| | | | | | | | | |
|`CUDNN_SCALAR_SIZE_T_WORKSPACE_SIZE_IN_BYTES`|7.6.0| | | | | | | | | |
|`CUDNN_SEQDATA_BATCH_DIM`|7.5.0| | | | | | | | | |
|`CUDNN_SEQDATA_BEAM_DIM`|7.5.0| | | | | | | | | |
|`CUDNN_SEQDATA_DIM_COUNT`|7.5.0| | | | | | | | | |
|`CUDNN_SEQDATA_TIME_DIM`|7.5.0| | | | | | | | | |
|`CUDNN_SEQDATA_VECT_DIM`|7.5.0| | | | | | | | | |
|`CUDNN_SEV_ERROR`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_ERROR_EN`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_FATAL`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_INFO`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_INFO_EN`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_WARNING`|7.1.3| | | | | | | | | |
|`CUDNN_SEV_WARNING_EN`|7.1.3| | | | | | | | | |
|`CUDNN_SIGNAL_SET`|8.5.0| | | | | | | | | |
|`CUDNN_SIGNAL_WAIT`|8.5.0| | | | | | | | | |
|`CUDNN_SKIP_INPUT`|5.0.0| | | |`miopenRNNskip`| | | | | |
|`CUDNN_SOFTMAX_ACCURATE`|1.0.0| | | |`MIOPEN_SOFTMAX_ACCURATE`| | | | | |
|`CUDNN_SOFTMAX_FAST`|1.0.0| | | |`MIOPEN_SOFTMAX_FAST`| | | | | |
|`CUDNN_SOFTMAX_LOG`|3.0.0| | | |`MIOPEN_SOFTMAX_LOG`| | | | | |
|`CUDNN_SOFTMAX_MODE_CHANNEL`|1.0.0| | | |`MIOPEN_SOFTMAX_MODE_CHANNEL`| | | | | |
|`CUDNN_SOFTMAX_MODE_INSTANCE`|1.0.0| | | |`MIOPEN_SOFTMAX_MODE_INSTANCE`| | | | | |
|`CUDNN_STATUS_ALLOC_FAILED`|1.0.0|9.0.0| | |`miopenStatusAllocFailed`| | | | | |
|`CUDNN_STATUS_ARCH_MISMATCH`|1.0.0|9.0.0| | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM`|1.0.0| | | |`miopenStatusBadParm`| | | | | |
|`CUDNN_STATUS_BAD_PARAM_ATTRIBUTE_TYPE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_DUPLICATED_ENTRIES`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_MISALIGNED_POINTER`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_NOT_FINALIZED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_NULL_POINTER`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_OUT_OF_BOUND`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_SHAPE_MISMATCH`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_SIZE_INSUFFICIENT`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_BAD_PARAM_STREAM_MISMATCH`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_CATEGORY`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_DEPRECATED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_EXECUTION_FAILED`|1.0.0| | | | | | | | | |
|`CUDNN_STATUS_EXECUTION_FAILED_CUBLAS`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_EXECUTION_FAILED_CUDART`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_EXECUTION_FAILED_CUDA_DRIVER`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_EXECUTION_FAILED_CURAND`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_FULL_ERROR_CODE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR`|1.0.0| | | |`miopenStatusInternalError`| | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_BAD_LAUNCH_PARAM`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_COMPILATION_FAILED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_DEVICE_ALLOCATION_FAILED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_HOST_ALLOCATION_FAILED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_TEXTURE_CREATION_FAILED`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INTERNAL_ERROR_UNEXPECTED_VALUE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_INVALID_VALUE`|1.0.0|9.0.0| | |`miopenStatusInvalidValue`| | | | | |
|`CUDNN_STATUS_LICENSE_ERROR`|1.0.0| | | | | | | | | |
|`CUDNN_STATUS_MAPPING_ERROR`|1.0.0|9.0.0| | | | | | | | |
|`CUDNN_STATUS_NOT_INITIALIZED`|1.0.0| | | |`miopenStatusNotInitialized`| | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED`|1.0.0| | | |`miopenStatusUnsupportedOp`| | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_ARCH_MISMATCH`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_BAD_LAUNCH_PARAM`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_DATA_TYPE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_GRAPH_PATTERN`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_INCOMPATIBLE_CUDART`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_INCOMPATIBLE_CUDA_DRIVER`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_LAYOUT`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_PADDING`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_RUNTIME_PREREQUISITE_MISSING`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_SHAPE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_SHARED_MEMORY_INSUFFICIENT`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_NOT_SUPPORTED_SUBLIBRARY_UNAVAILABLE`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_RUNTIME_FP_OVERFLOW`|7.0.5| | | | | | | | | |
|`CUDNN_STATUS_RUNTIME_IN_PROGRESS`|7.0.5| | | | | | | | | |
|`CUDNN_STATUS_RUNTIME_PREREQUISITE_MISSING`|6.0.0|9.0.0| | | | | | | | |
|`CUDNN_STATUS_SERIALIZATION_VERSION_MISMATCH`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_SPECIFIC_ERROR`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_SUBLIBRARY_LOADING_FAILED`|9.2.0| | | | | | | | | |
|`CUDNN_STATUS_SUBLIBRARY_VERSION_MISMATCH`|9.0.0| | | | | | | | | |
|`CUDNN_STATUS_SUCCESS`|1.0.0| | | |`miopenStatusSuccess`| | | | | |
|`CUDNN_STATUS_VERSION_MISMATCH`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_TENSOR_NCHW`|1.0.0| | | | | | | | | |
|`CUDNN_TENSOR_NCHW_VECT_C`|6.0.0| | | | | | | | | |
|`CUDNN_TENSOR_NHWC`|1.0.0| | | | | | | | | |
|`CUDNN_TENSOR_OP_MATH`|7.0.5| | | | | | | | | |
|`CUDNN_TENSOR_OP_MATH_ALLOW_CONVERSION`|7.2.1| | | | | | | | | |
|`CUDNN_TENSOR_REORDERING_F16x16`|8.8.0| | | | | | | | | |
|`CUDNN_TENSOR_REORDERING_INT8x32`|8.3.0| | | | | | | | | |
|`CUDNN_TENSOR_REORDERING_NONE`|8.3.0| | | | | | | | | |
|`CUDNN_TRANSFORM_FOLD`|7.5.0| | | | | | | | | |
|`CUDNN_TRANSFORM_UNFOLD`|7.5.0| | | | | | | | | |
|`CUDNN_TYPE_ATTRIB_NAME`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_BACKEND_DESCRIPTOR`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_BEHAVIOR_NOTE`|8.2.0| | | | | | | | | |
|`CUDNN_TYPE_BN_FINALIZE_STATS_MODE`|8.1.0| | | | | | | | | |
|`CUDNN_TYPE_BOOLEAN`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_CHAR`|8.4.0| | | | | | | | | |
|`CUDNN_TYPE_CONVOLUTION_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_DATA_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_DOUBLE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_FLOAT`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_FRACTION`|8.5.0| | | | | | | | | |
|`CUDNN_TYPE_GENSTATS_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_HANDLE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_HEUR_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_INT32`|8.3.0| | | | | | | | | |
|`CUDNN_TYPE_INT64`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_KNOB_TYPE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_LAYOUT_TYPE`|8.0.2| | | | | | | | | |
|`CUDNN_TYPE_NAN_PROPOGATION`|8.0.1|9.0.0| | | | | | | | |
|`CUDNN_TYPE_NORM_FWD_PHASE`|8.5.0| | | | | | | | | |
|`CUDNN_TYPE_NORM_MODE`|8.5.0| | | | | | | | | |
|`CUDNN_TYPE_NUMERICAL_NOTE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_PADDING_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_TYPE_POINTWISE_MODE`|8.0.1| | | | | | | | | |
|`CUDNN_TYPE_REDUCTION_OPERATOR_TYPE`|8.1.0| | | | | | | | | |
|`CUDNN_TYPE_RESAMPLE_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_TYPE_RNG_DISTRIBUTION`|8.7.0| | | | | | | | | |
|`CUDNN_TYPE_SIGNAL_MODE`|8.5.0| | | | | | | | | |
|`CUDNN_TYPE_TENSOR_REORDERING_MODE`|8.3.0| | | | | | | | | |
|`CUDNN_TYPE_VOID_PTR`|8.0.1| | | | | | | | | |
|`CUDNN_UNIDIRECTIONAL`|5.0.0| | | |`miopenRNNunidirection`| | | | | |
|`CUDNN_WGRAD_MODE_ADD`|7.5.0| | | | | | | | | |
|`CUDNN_WGRAD_MODE_SET`|7.5.0| | | | | | | | | |
|`CUDNN_ZERO_PAD`|8.3.0| | | | | | | | | |
|`cudnnActivationDescriptor_t`|4.0.0|9.0.0| | |`miopenActivationDescriptor_t`| | | | | |
|`cudnnActivationMode_t`|1.0.0|9.0.0| | |`miopenActivationMode_t`| | | | | |
|`cudnnActivationStruct`|4.0.0|9.0.0| | | | | | | | |
|`cudnnAlgorithmDescriptor_t`|7.1.3| | |9.0.0| | | | | | |
|`cudnnAlgorithmPerformanceStruct`|7.1.3| | |9.0.0| | | | | | |
|`cudnnAlgorithmPerformance_t`|7.1.3| | |9.0.0| | | | | | |
|`cudnnAlgorithmStruct`|7.1.3| | |9.0.0| | | | | | |
|`cudnnAlgorithmUnionStruct`|8.2.0| | |9.0.0| | | | | | |
|`cudnnAlgorithm_t`|7.1.3| | |9.0.0| | | | | | |
|`cudnnAttnDescriptor_t`|7.5.0|9.0.0| | | | | | | | |
|`cudnnAttnQueryMap_t`|7.5.0| | |9.0.0| | | | | | |
|`cudnnAttnStruct`|7.5.0| | | | | | | | | |
|`cudnnBackendAttributeName_t`|8.0.1| | | | | | | | | |
|`cudnnBackendAttributeType_t`|8.0.1| | | | | | | | | |
|`cudnnBackendBehaviorNote_t`|8.2.0| | | | | | | | | |
|`cudnnBackendDescriptorType_t`|8.0.1| | | | | | | | | |
|`cudnnBackendDescriptor_t`|8.0.1| | | | | | | | | |
|`cudnnBackendHeurMode_t`|8.0.1| | | | | | | | | |
|`cudnnBackendKnobType_t`|8.0.1| | | | | | | | | |
|`cudnnBackendLayoutType_t`|8.0.1| | | | | | | | | |
|`cudnnBackendNormFwdPhase_t`|8.5.0| | | | | | | | | |
|`cudnnBackendNormMode_t`|8.5.0| | | | | | | | | |
|`cudnnBackendNumericalNote_t`|8.0.1| | | | | | | | | |
|`cudnnBackendTensorReordering_t`|8.3.0| | | | | | | | | |
|`cudnnBatchNormMode_t`|4.0.0|9.0.0| | |`miopenBatchNormMode_t`| | | | | |
|`cudnnBatchNormOps_t`|7.4.1|9.0.0| | | | | | | | |
|`cudnnBnFinalizeStatsMode_t`|8.1.0| | | | | | | | | |
|`cudnnCTCLossAlgo_t`|7.0.5| | | |`miopenCTCLossAlgo_t`| | | | | |
|`cudnnCTCLossDescriptor_t`|7.0.5| | | |`miopenCTCLossDescriptor_t`| | | | | |
|`cudnnCTCLossStruct`|7.0.5| | | | | | | | | |
|`cudnnCallback_t`|7.1.3| | | | | | | | | |
|`cudnnContext`|1.0.0| | | | | | | | | |
|`cudnnConvolutionBwdDataAlgoPerfStruct`|8.2.0|9.0.0| | |`miopenConvAlgoPerf_t`| | | | | |
|`cudnnConvolutionBwdDataAlgoPerf_t`|3.0.0|9.0.0| | |`miopenConvAlgoPerf_t`| | | | | |
|`cudnnConvolutionBwdDataAlgo_t`|3.0.0| | | |`miopenConvBwdDataAlgorithm_t`| | | | | |
|`cudnnConvolutionBwdDataPreference_t`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnConvolutionBwdFilterAlgoPerfStruct`|8.2.0| | | | | | | | | |
|`cudnnConvolutionBwdFilterAlgoPerf_t`|3.0.0|9.0.0| | | | | | | | |
|`cudnnConvolutionBwdFilterAlgo_t`|3.0.0| | | | | | | | | |
|`cudnnConvolutionBwdFilterPreference_t`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnConvolutionDescriptor_t`|1.0.0|9.0.0| | |`miopenConvolutionDescriptor_t`| | | | | |
|`cudnnConvolutionFwdAlgoPerfStruct`|8.2.0| | | |`miopenConvAlgoPerf_t`| | | | | |
|`cudnnConvolutionFwdAlgoPerf_t`|3.0.0|9.0.0| | |`miopenConvAlgoPerf_t`| | | | | |
|`cudnnConvolutionFwdAlgo_t`|2.0.0| | | |`miopenConvFwdAlgorithm_t`| | | | | |
|`cudnnConvolutionFwdPreference_t`|2.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnConvolutionMode_t`|1.0.0| | | |`miopenConvolutionMode_t`| | | | | |
|`cudnnConvolutionStruct`|1.0.0| | | | | | | | | |
|`cudnnDataType_t`|1.0.0| | | |`miopenDataType_t`| | | | | |
|`cudnnDebugStruct`|8.2.0| | | | | | | | | |
|`cudnnDebug_t`|7.1.3| | | | | | | | | |
|`cudnnDeterminism_t`|6.0.0| | | | | | | | | |
|`cudnnDirectionMode_t`|5.0.0| | | |`miopenRNNDirectionMode_t`| | | | | |
|`cudnnDivNormMode_t`|3.0.0| | | | | | | | | |
|`cudnnDropoutDescriptor_t`|5.0.0| | | |`miopenDropoutDescriptor_t`| | | | | |
|`cudnnDropoutStruct`|5.0.0| | | | | | | | | |
|`cudnnErrQueryMode_t`|7.0.5| | | | | | | | | |
|`cudnnFilterDescriptor_t`|1.0.0| | | |`miopenTensorDescriptor_t`| | | | | |
|`cudnnFilterStruct`|1.0.0|9.0.0| | | | | | | | |
|`cudnnFoldingDirection_t`|7.5.0| | | | | | | | | |
|`cudnnForwardMode_t`|8.0.1| | | | | | | | | |
|`cudnnFractionStruct`|8.5.0| | | | | | | | | |
|`cudnnFraction_t`|8.5.0| | | | | | | | | |
|`cudnnFusedOpsConstParamLabel_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsConstParamPack_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsConstParamStruct`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsPlanStruct`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsPlan_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsPointerPlaceHolder_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsVariantParamLabel_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsVariantParamPack_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOpsVariantParamStruct`|7.6.0|9.0.0| | | | | | | | |
|`cudnnFusedOps_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGenStatsMode_t`|8.0.1| | | | | | | | | |
|`cudnnHandle_t`|1.0.0| | | |`miopenHandle_t`| | | | | |
|`cudnnIndicesType_t`|6.0.0|9.0.0| | |`miopenIndicesType_t`| | | | | |
|`cudnnLRNDescriptor_t`|3.0.0| | | |`miopenLRNDescriptor_t`| | | | | |
|`cudnnLRNMode_t`|3.0.0| | | |`miopenLRNMode_t`| | | | | |
|`cudnnLRNStruct`|3.0.0| | | | | | | | | |
|`cudnnLossNormalizationMode_t`|7.6.0| | | | | | | | | |
|`cudnnMathType_t`|7.0.5| | | | | | | | | |
|`cudnnMultiHeadAttnWeightKind_t`|7.5.0| | | | | | | | | |
|`cudnnNanPropagation_t`|4.0.0| | | |`miopenNanPropagation_t`| | | | | |
|`cudnnNormAlgo_t`|8.0.1|9.0.0| | | | | | | | |
|`cudnnNormMode_t`|8.0.1|9.0.0| | | | | | | | |
|`cudnnNormOps_t`|8.0.1|9.0.0| | | | | | | | |
|`cudnnOpTensorDescriptor_t`|5.0.0|9.0.0| | | | | | | | |
|`cudnnOpTensorOp_t`|5.0.0| | | |`miopenTensorOp_t`| | | | | |
|`cudnnOpTensorStruct`|5.0.0|9.0.0| | | | | | | | |
|`cudnnPaddingMode_t`|8.3.0| | | | | | | | | |
|`cudnnPersistentRNNPlan`|6.0.0| | | | | | | | | |
|`cudnnPersistentRNNPlan_t`|6.0.0| | | | | | | | | |
|`cudnnPointwiseMode_t`|8.0.1| | | | | | | | | |
|`cudnnPoolingDescriptor_t`|1.0.0|9.0.0| | |`miopenPoolingDescriptor_t`| | | | | |
|`cudnnPoolingMode_t`|1.0.0|9.0.0| | |`miopenPoolingMode_t`| | | | | |
|`cudnnPoolingStruct`|1.0.0|9.0.0| | | | | | | | |
|`cudnnRNNAlgo_t`|6.0.0| | | |`miopenRNNAlgo_t`| | | | | |
|`cudnnRNNBiasMode_t`|7.5.0| | | |`miopenRNNBiasMode_t`| | | | | |
|`cudnnRNNClipMode_t`|7.2.1| | | | | | | | | |
|`cudnnRNNDataDescriptor_t`|7.2.1| | | | | | | | | |
|`cudnnRNNDataLayout_t`|7.2.1| | | | | | | | | |
|`cudnnRNNDataStruct`|7.2.1| | | | | | | | | |
|`cudnnRNNDescriptor_t`|5.0.0| | | |`miopenRNNDescriptor_t`| | | | | |
|`cudnnRNNInputMode_t`|5.0.0| | | |`miopenRNNInputMode_t`| | | | | |
|`cudnnRNNMode_t`|5.0.0| | | |`miopenRNNMode_t`| | | | | |
|`cudnnRNNPaddingMode_t`|7.2.1| | | | | | | | | |
|`cudnnRNNStruct`|5.0.0| | | | | | | | | |
|`cudnnReduceTensorDescriptor_t`|6.0.0|9.0.0| | |`miopenReduceTensorDescriptor_t`| | | | | |
|`cudnnReduceTensorIndices_t`|6.0.0|9.0.0| | |`miopenReduceTensorIndices_t`| | | | | |
|`cudnnReduceTensorOp_t`|6.0.0| | | |`miopenReduceTensorOp_t`| | | | | |
|`cudnnReduceTensorStruct`|6.0.0|9.0.0| | | | | | | | |
|`cudnnReorderType_t`|7.6.0|9.0.0| | | | | | | | |
|`cudnnResampleMode_t`|8.3.0| | | | | | | | | |
|`cudnnRngDistribution_t`|8.7.0| | | | | | | | | |
|`cudnnRuntimeTag_t`|7.0.5|9.0.0| | | | | | | | |
|`cudnnSamplerType_t`|5.0.0| | | | | | | | | |
|`cudnnSeqDataAxis_t`|7.5.0| | | | | | | | | |
|`cudnnSeqDataDescriptor_t`|7.5.0|9.0.0| | | | | | | | |
|`cudnnSeqDataStruct`|7.5.0| | | | | | | | | |
|`cudnnSeverity_t`|7.1.3| | | | | | | | | |
|`cudnnSignalMode_t`|8.5.0| | | | | | | | | |
|`cudnnSoftmaxAlgorithm_t`|1.0.0| | | |`miopenSoftmaxAlgorithm_t`| | | | | |
|`cudnnSoftmaxMode_t`|1.0.0| | | |`miopenSoftmaxMode_t`| | | | | |
|`cudnnSpatialTransformerDescriptor_t`|5.0.0| | | | | | | | | |
|`cudnnSpatialTransformerStruct`|5.0.0| | | | | | | | | |
|`cudnnStatus_t`|1.0.0| | | |`miopenStatus_t`| | | | | |
|`cudnnTensorDescriptor_t`|2.0.0| | | |`miopenTensorDescriptor_t`| | | | | |
|`cudnnTensorFormat_t`|1.0.0| | | | | | | | | |
|`cudnnTensorStruct`|2.0.0| | | | | | | | | |
|`cudnnTensorTransformDescriptor_t`|7.5.0|9.0.0| | | | | | | | |
|`cudnnTensorTransformStruct`|7.5.0|9.0.0| | | | | | | | |
|`cudnnWgradMode_t`|7.5.0| | | | | | | | | |
|`libraryPropertyType`|6.0.0| | | | | | | | | |
|`libraryPropertyType_t`|6.0.0| | |9.0.0| | | | | | |

## **2. CUDNN Functions**

|**CUDA**|**A**|**D**|**C**|**R**|**MIOPEN**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cudnnActivationBackward`|1.0.0|9.0.0| | |`miopenActivationBackward`| | | | | |
|`cudnnActivationForward`|1.0.0|9.0.0| | |`miopenActivationForward`| | | | | |
|`cudnnAddTensor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnAdvInferVersionCheck`|8.0.1| | |9.0.0| | | | | | |
|`cudnnAdvTrainVersionCheck`|8.0.1| | |9.0.0| | | | | | |
|`cudnnAdvVersionCheck`|9.0.0| | | | | | | | | |
|`cudnnBackendCreateDescriptor`|8.0.1| | | | | | | | | |
|`cudnnBackendDestroyDescriptor`|8.0.1| | | | | | | | | |
|`cudnnBackendExecute`|8.0.1| | | | | | | | | |
|`cudnnBackendFinalize`|8.0.1| | | | | | | | | |
|`cudnnBackendGetAttribute`|8.0.1| | | | | | | | | |
|`cudnnBackendInitialize`|8.0.1|9.3.0| | | | | | | | |
|`cudnnBackendSetAttribute`|8.0.1| | | | | | | | | |
|`cudnnBatchNormalizationBackward`|4.0.0|9.0.0| | |`miopenBatchNormalizationBackward`| | | | | |
|`cudnnBatchNormalizationBackwardEx`|7.4.1|9.0.0| | | | | | | | |
|`cudnnBatchNormalizationForwardInference`|4.0.0|9.0.0| | |`miopenBatchNormalizationForwardInference`| | | | | |
|`cudnnBatchNormalizationForwardTraining`|4.0.0|9.0.0| | |`miopenBatchNormalizationForwardTraining`| | | | | |
|`cudnnBatchNormalizationForwardTrainingEx`|7.4.1|9.0.0| | | | | | | | |
|`cudnnBuildRNNDynamic`|8.0.1| | | | | | | | | |
|`cudnnCTCLoss`|7.0.5| | | |`miopenCTCLoss`| | | | | |
|`cudnnCTCLoss_v8`|8.0.1| | | | | | | | | |
|`cudnnCnnInferVersionCheck`|8.0.2| | | | | | | | | |
|`cudnnCnnTrainVersionCheck`|8.0.2| | | | | | | | | |
|`cudnnConvolutionBackwardBias`|1.0.0|9.0.0| | |`miopenConvolutionBackwardBias`| | | | | |
|`cudnnConvolutionBackwardData`|1.0.0|9.0.0| | |`miopenConvolutionBackwardData`| | | | | |
|`cudnnConvolutionBackwardFilter`|1.0.0|9.0.0| | | | | | | | |
|`cudnnConvolutionBiasActivationForward`|6.0.0|9.0.0| | |`miopenConvolutionBiasActivationForward`| | | | | |
|`cudnnConvolutionForward`|1.0.0|9.0.0| | |`miopenConvolutionForward`| | | | | |
|`cudnnCopyAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnCreate`|1.0.0| | | |`miopenCreate`| | | | | |
|`cudnnCreateActivationDescriptor`|4.0.0|9.0.0| | |`miopenCreateActivationDescriptor`| | | | | |
|`cudnnCreateAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnCreateAlgorithmPerformance`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnCreateAttnDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnCreateCTCLossDescriptor`|7.0.5| | | |`miopenCreateCTCLossDescriptor`| | | | | |
|`cudnnCreateConvolutionDescriptor`|1.0.0|9.0.0| | |`miopenCreateConvolutionDescriptor`| | | | | |
|`cudnnCreateDropoutDescriptor`|5.0.0| | | |`miopenCreateDropoutDescriptor`| | | | | |
|`cudnnCreateFilterDescriptor`|1.0.0|9.0.0| | | | | | | | |
|`cudnnCreateFusedOpsConstParamPack`|7.6.0|9.0.0| | | | | | | | |
|`cudnnCreateFusedOpsPlan`|7.6.0|9.0.0| | | | | | | | |
|`cudnnCreateFusedOpsVariantParamPack`|7.6.0|9.0.0| | | | | | | | |
|`cudnnCreateLRNDescriptor`|3.0.0| | | |`miopenCreateLRNDescriptor`| | | | | |
|`cudnnCreateOpTensorDescriptor`|5.0.0|9.0.0| | | | | | | | |
|`cudnnCreatePersistentRNNPlan`|6.0.0|8.0.1| |9.0.0| | | | | | |
|`cudnnCreatePoolingDescriptor`|1.0.0|9.0.0| | |`miopenCreatePoolingDescriptor`| | | | | |
|`cudnnCreateRNNDataDescriptor`|7.2.1| | | | | | | | | |
|`cudnnCreateRNNDescriptor`|5.0.0| | | |`miopenCreateRNNDescriptor`| | | | | |
|`cudnnCreateReduceTensorDescriptor`|6.0.0|9.0.0| | |`miopenCreateReduceTensorDescriptor`| | | | | |
|`cudnnCreateSeqDataDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnCreateSpatialTransformerDescriptor`|5.0.0| | | | | | | | | |
|`cudnnCreateTensorDescriptor`|2.0.0| | | |`miopenCreateTensorDescriptor`| | | | | |
|`cudnnCreateTensorTransformDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnDeriveBNTensorDescriptor`|4.0.0|9.0.0| | |`miopenDeriveBNTensorDescriptor`| | | | | |
|`cudnnDeriveNormTensorDescriptor`|8.0.1|9.0.0| | | | | | | | |
|`cudnnDestroy`|1.0.0| | | |`miopenDestroy`| | | | | |
|`cudnnDestroyActivationDescriptor`|4.0.0|9.0.0| | |`miopenDestroyActivationDescriptor`| | | | | |
|`cudnnDestroyAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnDestroyAlgorithmPerformance`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnDestroyAttnDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnDestroyCTCLossDescriptor`|7.0.5| | | |`miopenDestroyCTCLossDescriptor`| | | | | |
|`cudnnDestroyConvolutionDescriptor`|1.0.0|9.0.0| | |`miopenDestroyConvolutionDescriptor`| | | | | |
|`cudnnDestroyDropoutDescriptor`|5.0.0| | | |`miopenDestroyDropoutDescriptor`| | | | | |
|`cudnnDestroyFilterDescriptor`|1.0.0|9.0.0| | | | | | | | |
|`cudnnDestroyFusedOpsConstParamPack`|7.6.0|9.0.0| | | | | | | | |
|`cudnnDestroyFusedOpsPlan`|7.6.0|9.0.0| | | | | | | | |
|`cudnnDestroyFusedOpsVariantParamPack`|7.6.0|9.0.0| | | | | | | | |
|`cudnnDestroyLRNDescriptor`|3.0.0| | | |`miopenDestroyLRNDescriptor`| | | | | |
|`cudnnDestroyOpTensorDescriptor`|5.0.0|9.0.0| | | | | | | | |
|`cudnnDestroyPersistentRNNPlan`|6.0.0|8.0.1| |9.0.0| | | | | | |
|`cudnnDestroyPoolingDescriptor`|1.0.0|9.0.0| | |`miopenDestroyPoolingDescriptor`| | | | | |
|`cudnnDestroyRNNDataDescriptor`|7.2.1| | | | | | | | | |
|`cudnnDestroyRNNDescriptor`|5.0.0| | | |`miopenDestroyRNNDescriptor`| | | | | |
|`cudnnDestroyReduceTensorDescriptor`|6.0.0|9.0.0| | |`miopenDestroyReduceTensorDescriptor`| | | | | |
|`cudnnDestroySeqDataDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnDestroySpatialTransformerDescriptor`|5.0.0| | | | | | | | | |
|`cudnnDestroyTensorDescriptor`|2.0.0| | | |`miopenDestroyTensorDescriptor`| | | | | |
|`cudnnDestroyTensorTransformDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnDivisiveNormalizationBackward`|3.0.0| | | | | | | | | |
|`cudnnDivisiveNormalizationForward`|3.0.0| | | | | | | | | |
|`cudnnDropoutBackward`|5.0.0| | | |`miopenDropoutBackward`| | | | | |
|`cudnnDropoutForward`|5.0.0| | | |`miopenDropoutForward`| | | | | |
|`cudnnDropoutGetReserveSpaceSize`|5.0.0| | | |`miopenDropoutGetReserveSpaceSize`| | | | | |
|`cudnnDropoutGetStatesSize`|5.0.0| | | |`miopenDropoutGetStatesSize`| | | | | |
|`cudnnFindConvolutionBackwardDataAlgorithm`|3.0.0|9.0.0| | | | | | | | |
|`cudnnFindConvolutionBackwardDataAlgorithmEx`|5.0.0|9.0.0| | | | | | | | |
|`cudnnFindConvolutionBackwardFilterAlgorithm`|3.0.0|9.0.0| | | | | | | | |
|`cudnnFindConvolutionBackwardFilterAlgorithmEx`|5.0.0|9.0.0| | | | | | | | |
|`cudnnFindConvolutionForwardAlgorithm`|3.0.0|9.0.0| | | | | | | | |
|`cudnnFindConvolutionForwardAlgorithmEx`|5.0.0|9.0.0| | |`miopenFindConvolutionForwardAlgorithm`| | | | | |
|`cudnnFindRNNBackwardDataAlgorithmEx`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnFindRNNBackwardWeightsAlgorithmEx`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnFindRNNForwardInferenceAlgorithmEx`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnFindRNNForwardTrainingAlgorithmEx`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnFusedOpsExecute`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetActivationDescriptor`|4.0.0|9.0.0| | | | | | | | |
|`cudnnGetActivationDescriptorSwishBeta`|8.2.0|9.0.0| | | | | | | | |
|`cudnnGetAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetAlgorithmPerformance`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetAlgorithmSpaceSize`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetAttnDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetBatchNormalizationBackwardExWorkspaceSize`|7.4.1|9.0.0| | | | | | | | |
|`cudnnGetBatchNormalizationForwardTrainingExWorkspaceSize`|7.4.1|9.0.0| | | | | | | | |
|`cudnnGetBatchNormalizationTrainingExReserveSpaceSize`|7.4.1|9.0.0| | | | | | | | |
|`cudnnGetCTCLossDescriptor`|7.0.5|9.0.0| | |`miopenGetCTCLossDescriptor`| | | | | |
|`cudnnGetCTCLossDescriptorEx`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetCTCLossDescriptor_v8`|8.0.1|9.0.0| | | | | | | | |
|`cudnnGetCTCLossDescriptor_v9`|9.0.0| | | | | | | | | |
|`cudnnGetCTCLossWorkspaceSize`|7.0.5| | | |`miopenGetCTCLossWorkspaceSize`| | | | | |
|`cudnnGetCTCLossWorkspaceSize_v8`|8.0.1| | | | | | | | | |
|`cudnnGetCallback`|7.1.3| | | | | | | | | |
|`cudnnGetConvolution2dDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnGetConvolution2dForwardOutputDim`|2.0.0|9.0.0| | |`miopenGetConvolutionForwardOutputDim`| | | | | |
|`cudnnGetConvolutionBackwardDataAlgorithm`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnGetConvolutionBackwardDataAlgorithmMaxCount`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionBackwardDataAlgorithm_v7`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionBackwardDataWorkspaceSize`|3.0.0|9.0.0| | |`miopenConvolutionBackwardDataGetWorkSpaceSize`| | | | | |
|`cudnnGetConvolutionBackwardFilterAlgorithm`|3.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnGetConvolutionBackwardFilterAlgorithmMaxCount`|7.0.5| | | | | | | | | |
|`cudnnGetConvolutionBackwardFilterAlgorithm_v7`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionBackwardFilterWorkspaceSize`|3.0.0|9.0.0| | | | | | | | |
|`cudnnGetConvolutionForwardAlgorithm`|2.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnGetConvolutionForwardAlgorithmMaxCount`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionForwardAlgorithm_v7`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionForwardWorkspaceSize`|2.0.0|9.0.0| | |`miopenConvolutionForwardGetWorkSpaceSize`| | | | | |
|`cudnnGetConvolutionGroupCount`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionMathType`|7.0.5|9.0.0| | | | | | | | |
|`cudnnGetConvolutionNdDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnGetConvolutionNdForwardOutputDim`|2.0.0|9.0.0| | | | | | | | |
|`cudnnGetConvolutionReorderType`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetCudartVersion`|6.0.0| | | | | | | | | |
|`cudnnGetDropoutDescriptor`|7.0.5| | | |`miopenGetDropoutDescriptor`| | | | | |
|`cudnnGetErrorString`|2.0.0| | | |`miopenGetErrorString`| | | | | |
|`cudnnGetFilter4dDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnGetFilterNdDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnGetFilterSizeInBytes`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetFoldedConvBackwardDataDescriptors`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetFusedOpsConstParamPackAttribute`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetFusedOpsVariantParamPackAttribute`|7.6.0|9.0.0| | | | | | | | |
|`cudnnGetLRNDescriptor`|3.0.0| | | |`miopenGetLRNDescriptor`| | | | | |
|`cudnnGetLastErrorString`|9.0.0| | | | | | | | | |
|`cudnnGetMaxDeviceVersion`|8.6.0| | | | | | | | | |
|`cudnnGetMultiHeadAttnBuffers`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetMultiHeadAttnWeights`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetNormalizationBackwardWorkspaceSize`|8.0.1|9.0.0| | | | | | | | |
|`cudnnGetNormalizationForwardTrainingWorkspaceSize`|8.0.1|9.0.0| | | | | | | | |
|`cudnnGetNormalizationTrainingReserveSpaceSize`|8.0.1|9.0.0| | | | | | | | |
|`cudnnGetOpTensorDescriptor`|5.0.0|9.0.0| | | | | | | | |
|`cudnnGetPooling2dDescriptor`|2.0.0|9.0.0| | |`miopenGet2dPoolingDescriptor`| | | | | |
|`cudnnGetPooling2dForwardOutputDim`|2.0.0|9.0.0| | |`miopenGetPoolingForwardOutputDim`| | | | | |
|`cudnnGetPoolingNdDescriptor`|2.0.0|9.0.0| | |`miopenGetNdPoolingDescriptor`| | | | | |
|`cudnnGetPoolingNdForwardOutputDim`|2.0.0|9.0.0| | |`miopenGetPoolingNdForwardOutputDim`| | | | | |
|`cudnnGetProperty`|6.0.0| | | | | | | | | |
|`cudnnGetRNNBackwardDataAlgorithmMaxCount`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetRNNBackwardWeightsAlgorithmMaxCount`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetRNNBiasMode`|7.5.0|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNDataDescriptor`|7.2.1| | | | | | | | | |
|`cudnnGetRNNDescriptor`|7.0.5|7.6.5| |8.0.1|`miopenGetRNNDescriptor_V2`| | | | | |
|`cudnnGetRNNDescriptor_v6`|8.0.1|8.0.1| |9.0.0|`miopenGetRNNDescriptor_V2`| | | | | |
|`cudnnGetRNNDescriptor_v8`|8.0.1| | | | | | | | | |
|`cudnnGetRNNForwardInferenceAlgorithmMaxCount`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetRNNForwardTrainingAlgorithmMaxCount`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnGetRNNLinLayerBiasParams`|5.0.0|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNLinLayerMatrixParams`|5.0.0|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNMatrixMathType`|7.1.3|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNPaddingMode`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNParamsSize`|5.0.0|8.0.1| |9.0.0|`miopenGetRNNParamsSize`| | | | | |
|`cudnnGetRNNProjectionLayers`|7.1.3|8.0.1| |9.0.0| | | | | | |
|`cudnnGetRNNTempSpaceSizes`|8.0.1| | | | | | | | | |
|`cudnnGetRNNTrainingReserveSize`|5.0.0|8.0.1| |9.0.0|`miopenGetRNNTrainingReserveSize`| | | | | |
|`cudnnGetRNNWeightParams`|8.0.1| | | | | | | | | |
|`cudnnGetRNNWeightSpaceSize`|8.0.1| | | | | | | | | |
|`cudnnGetRNNWorkspaceSize`|5.0.0|8.0.1| |9.0.0|`miopenGetRNNWorkspaceSize`| | | | | |
|`cudnnGetReduceTensorDescriptor`|6.0.0|9.0.0| | |`miopenGetReduceTensorDescriptor`| | | | | |
|`cudnnGetReductionIndicesSize`|6.0.0|9.0.0| | |`miopenGetReductionIndicesSize`| | | | | |
|`cudnnGetReductionWorkspaceSize`|6.0.0|9.0.0| | |`miopenGetReductionWorkspaceSize`| | | | | |
|`cudnnGetSeqDataDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetStream`|1.0.0| | | |`miopenGetStream`| | | | | |
|`cudnnGetTensor4dDescriptor`|1.0.0| | | |`miopenGet4dTensorDescriptor`| | | | | |
|`cudnnGetTensorNdDescriptor`|2.0.0| | | | | | | | | |
|`cudnnGetTensorSizeInBytes`|6.0.0| | | | | | | | | |
|`cudnnGetTensorTransformDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnGetVersion`|2.0.0| | | | | | | | | |
|`cudnnGraphVersionCheck`|9.0.0| | | | | | | | | |
|`cudnnIm2Col`|2.0.0|9.0.0| | | | | | | | |
|`cudnnInitTransformDest`|7.5.0|9.0.0| | | | | | | | |
|`cudnnLRNCrossChannelBackward`|3.0.0| | | | | | | | | |
|`cudnnLRNCrossChannelForward`|3.0.0| | | | | | | | | |
|`cudnnMakeFusedOpsPlan`|7.6.0|9.0.0| | | | | | | | |
|`cudnnMultiHeadAttnBackwardData`|7.5.0|9.0.0| | | | | | | | |
|`cudnnMultiHeadAttnBackwardWeights`|7.5.0|9.0.0| | | | | | | | |
|`cudnnMultiHeadAttnForward`|7.5.0|9.0.0| | | | | | | | |
|`cudnnNormalizationBackward`|8.0.1|9.0.0| | | | | | | | |
|`cudnnNormalizationForwardInference`|8.0.1|9.0.0| | | | | | | | |
|`cudnnNormalizationForwardTraining`|8.0.1|9.0.0| | | | | | | | |
|`cudnnOpTensor`|5.0.0|9.0.0| | | | | | | | |
|`cudnnOpsInferVersionCheck`|8.0.1| | | | | | | | | |
|`cudnnOpsTrainVersionCheck`|8.0.1| | |9.0.0| | | | | | |
|`cudnnOpsVersionCheck`|9.0.0| | | | | | | | | |
|`cudnnPoolingBackward`|1.0.0|9.0.0| | | | | | | | |
|`cudnnPoolingForward`|1.0.0|9.0.0| | | | | | | | |
|`cudnnQueryRuntimeError`|7.0.5|9.0.0| | | | | | | | |
|`cudnnRNNBackwardData`|5.0.0|8.0.2| |9.0.0|`miopenRNNBackwardData`| | | | | |
|`cudnnRNNBackwardDataEx`|7.2.1|8.0.2| |9.0.0| | | | | | |
|`cudnnRNNBackwardData_v8`|8.0.2| | | | | | | | | |
|`cudnnRNNBackwardWeights`|5.0.0|8.0.2| |9.0.0|`miopenRNNBackwardWeights`| | | | | |
|`cudnnRNNBackwardWeightsEx`|7.2.1|8.0.2| |9.0.0| | | | | | |
|`cudnnRNNBackwardWeights_v8`|8.0.2| | | | | | | | | |
|`cudnnRNNForward`|8.0.1| | | | | | | | | |
|`cudnnRNNForwardInference`|5.0.0|8.0.1| |9.0.0|`miopenRNNForwardInference`| | | | | |
|`cudnnRNNForwardInferenceEx`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnRNNForwardTraining`|5.0.0|8.0.1| |9.0.0|`miopenRNNForwardTraining`| | | | | |
|`cudnnRNNForwardTrainingEx`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnRNNGetClip`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnRNNGetClip_v8`|8.0.1| | | | | | | | | |
|`cudnnRNNGetClip_v9`|9.0.0| | | | | | | | | |
|`cudnnRNNSetClip`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnRNNSetClip_v8`|8.0.1| | | | | | | | | |
|`cudnnRNNSetClip_v9`|9.0.0| | | | | | | | | |
|`cudnnReduceTensor`|6.0.0|9.0.0| | |`miopenReduceTensor`| | | | | |
|`cudnnReorderFilterAndBias`|7.6.0|9.0.0| | | | | | | | |
|`cudnnRestoreAlgorithm`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnRestoreDropoutDescriptor`|7.0.5| | | |`miopenRestoreDropoutDescriptor`| | | | | |
|`cudnnSaveAlgorithm`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnScaleTensor`|2.0.0|9.0.0| | |`miopenScaleTensor`| | | | | |
|`cudnnSetActivationDescriptor`|4.0.0|9.0.0| | | | | | | | |
|`cudnnSetActivationDescriptorSwishBeta`|8.2.0|9.0.0| | | | | | | | |
|`cudnnSetAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnSetAlgorithmPerformance`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnSetAttnDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnSetCTCLossDescriptor`|7.0.5|9.0.0| | |`miopenSetCTCLossDescriptor`| | | | | |
|`cudnnSetCTCLossDescriptorEx`|7.6.0|9.0.0| | | | | | | | |
|`cudnnSetCTCLossDescriptor_v8`|8.0.1|9.0.0| | | | | | | | |
|`cudnnSetCTCLossDescriptor_v9`|9.0.0| | | | | | | | | |
|`cudnnSetCallback`|7.1.3| | | | | | | | | |
|`cudnnSetConvolution2dDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnSetConvolutionGroupCount`|7.0.5|9.0.0| | |`miopenSetConvolutionGroupCount`| | | | | |
|`cudnnSetConvolutionMathType`|7.0.5|9.0.0| | | | | | | | |
|`cudnnSetConvolutionNdDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnSetConvolutionReorderType`|7.6.0|9.0.0| | | | | | | | |
|`cudnnSetDropoutDescriptor`|5.0.0| | | |`miopenSetDropoutDescriptor`| | | | | |
|`cudnnSetFilter4dDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnSetFilterNdDescriptor`|2.0.0|9.0.0| | | | | | | | |
|`cudnnSetFusedOpsConstParamPackAttribute`|7.6.0|9.0.0| | | | | | | | |
|`cudnnSetFusedOpsVariantParamPackAttribute`|7.6.0|9.0.0| | | | | | | | |
|`cudnnSetLRNDescriptor`|3.0.0| | | |`miopenSetLRNDescriptor`| | | | | |
|`cudnnSetOpTensorDescriptor`|5.0.0|9.0.0| | | | | | | | |
|`cudnnSetPersistentRNNPlan`|6.0.0|8.0.1| |9.0.0| | | | | | |
|`cudnnSetPooling2dDescriptor`|2.0.0|9.0.0| | |`miopenSet2dPoolingDescriptor`| | | | | |
|`cudnnSetPoolingNdDescriptor`|2.0.0|9.0.0| | |`miopenSetNdPoolingDescriptor`| | | | | |
|`cudnnSetRNNAlgorithmDescriptor`|7.1.3|8.0.2| |9.0.0| | | | | | |
|`cudnnSetRNNBiasMode`|7.5.0|8.0.1| |9.0.0| | | | | | |
|`cudnnSetRNNDataDescriptor`|7.2.1| | | | | | | | | |
|`cudnnSetRNNDescriptor`|5.0.0|7.6.5| |8.0.1| | | | | | |
|`cudnnSetRNNDescriptor_v5`|7.0.5|7.6.5| |8.0.1| | | | | | |
|`cudnnSetRNNDescriptor_v6`|6.0.0|8.0.1| |9.0.0|`miopenSetRNNDescriptor_V2`| | | | | |
|`cudnnSetRNNDescriptor_v8`|8.0.1| | | | | | | | | |
|`cudnnSetRNNMatrixMathType`|7.0.5|8.0.1| |9.0.0| | | | | | |
|`cudnnSetRNNPaddingMode`|7.2.1|8.0.1| |9.0.0| | | | | | |
|`cudnnSetRNNProjectionLayers`|7.1.3|8.0.1| |9.0.0| | | | | | |
|`cudnnSetReduceTensorDescriptor`|6.0.0|9.0.0| | |`miopenSetReduceTensorDescriptor`| | | | | |
|`cudnnSetSeqDataDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnSetSpatialTransformerNdDescriptor`|5.0.0| | | | | | | | | |
|`cudnnSetStream`|1.0.0| | | |`miopenSetStream`| | | | | |
|`cudnnSetTensor`|2.0.0| | | |`miopenSetTensor`| | | | | |
|`cudnnSetTensor4dDescriptor`|1.0.0| | | | | | | | | |
|`cudnnSetTensor4dDescriptorEx`|1.0.0| | | |`miopenSet4dTensorDescriptorEx`| | | | | |
|`cudnnSetTensorNdDescriptor`|2.0.0| | | | | | | | | |
|`cudnnSetTensorNdDescriptorEx`|6.0.0| | | | | | | | | |
|`cudnnSetTensorTransformDescriptor`|7.5.0|9.0.0| | | | | | | | |
|`cudnnSoftmaxBackward`|1.0.0| | | |`miopenSoftmaxBackward_V2`| | | | | |
|`cudnnSoftmaxForward`|1.0.0| | | |`miopenSoftmaxForward_V2`| | | | | |
|`cudnnSpatialTfGridGeneratorBackward`|5.0.0| | | | | | | | | |
|`cudnnSpatialTfGridGeneratorForward`|5.0.0| | | | | | | | | |
|`cudnnSpatialTfSamplerBackward`|5.0.0| | | | | | | | | |
|`cudnnSpatialTfSamplerForward`|5.0.0| | | | | | | | | |
|`cudnnTransformFilter`|7.6.0|9.0.0| | | | | | | | |
|`cudnnTransformTensor`|2.0.0|9.0.0| | |`miopenTransformTensor`| | | | | |
|`cudnnTransformTensorEx`|7.5.0|9.0.0| | | | | | | | |


\*A - Added; D - Deprecated; C - Changed; R - Removed; E - Experimental