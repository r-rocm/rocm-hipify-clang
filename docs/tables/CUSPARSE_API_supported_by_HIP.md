# CUSPARSE API supported by HIP

## **4. CUSPARSE Types References**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`CUSPARSE_ACTION_NUMERIC`| | | | |`HIPSPARSE_ACTION_NUMERIC`|1.9.2| | | | |
|`CUSPARSE_ACTION_SYMBOLIC`| | | | |`HIPSPARSE_ACTION_SYMBOLIC`|1.9.2| | | | |
|`CUSPARSE_ALG0`|8.0| | |11.0| | | | | | |
|`CUSPARSE_ALG1`|8.0| | |11.0| | | | | | |
|`CUSPARSE_ALG_MERGE_PATH`|9.2| | |12.0| | | | | | |
|`CUSPARSE_ALG_NAIVE`|9.2| | |11.0| | | | | | |
|`CUSPARSE_COLOR_ALG0`|8.0|12.2| | | | | | | | |
|`CUSPARSE_COLOR_ALG1`|8.0|12.2| | | | | | | | |
|`CUSPARSE_COOMM_ALG1`|10.1|11.0| |12.0|`HIPSPARSE_COOMM_ALG1`|4.2.0| | | | |
|`CUSPARSE_COOMM_ALG2`|10.1|11.0| |12.0|`HIPSPARSE_COOMM_ALG2`|4.2.0| | | | |
|`CUSPARSE_COOMM_ALG3`|10.1|11.0| |12.0|`HIPSPARSE_COOMM_ALG3`|4.2.0| | | | |
|`CUSPARSE_COOMV_ALG`|10.2|11.2| |12.0|`HIPSPARSE_COOMV_ALG`|4.1.0| | | | |
|`CUSPARSE_CSR2CSC_ALG1`|10.1| | | |`HIPSPARSE_CSR2CSC_ALG1`|5.4.0| | | | |
|`CUSPARSE_CSR2CSC_ALG2`|10.1| | |12.0|`HIPSPARSE_CSR2CSC_ALG2`|5.4.0| | | | |
|`CUSPARSE_CSR2CSC_ALG_DEFAULT`|12.0| | | |`HIPSPARSE_CSR2CSC_ALG_DEFAULT`|5.6.0| | | | |
|`CUSPARSE_CSRMM_ALG1`|10.2|11.0| |12.0|`HIPSPARSE_CSRMM_ALG1`|4.2.0| | | | |
|`CUSPARSE_CSRMV_ALG1`|10.2|11.2| |12.0|`HIPSPARSE_CSRMV_ALG1`|4.1.0| | | | |
|`CUSPARSE_CSRMV_ALG2`|10.2|11.2| |12.0|`HIPSPARSE_CSRMV_ALG2`|4.1.0| | | | |
|`CUSPARSE_DENSETOSPARSE_ALG_DEFAULT`|11.1| | | |`HIPSPARSE_DENSETOSPARSE_ALG_DEFAULT`|4.2.0| | | | |
|`CUSPARSE_DIAG_TYPE_NON_UNIT`| | | | |`HIPSPARSE_DIAG_TYPE_NON_UNIT`|1.9.2| | | | |
|`CUSPARSE_DIAG_TYPE_UNIT`| | | | |`HIPSPARSE_DIAG_TYPE_UNIT`|1.9.2| | | | |
|`CUSPARSE_DIRECTION_COLUMN`| | | | |`HIPSPARSE_DIRECTION_COLUMN`|3.2.0| | | | |
|`CUSPARSE_DIRECTION_ROW`| | | | |`HIPSPARSE_DIRECTION_ROW`|3.2.0| | | | |
|`CUSPARSE_FILL_MODE_LOWER`| | | | |`HIPSPARSE_FILL_MODE_LOWER`|1.9.2| | | | |
|`CUSPARSE_FILL_MODE_UPPER`| | | | |`HIPSPARSE_FILL_MODE_UPPER`|1.9.2| | | | |
|`CUSPARSE_FORMAT_BLOCKED_ELL`|11.2| | | |`HIPSPARSE_FORMAT_BLOCKED_ELL`|4.5.0| | | | |
|`CUSPARSE_FORMAT_BSR`|12.1| | | | | | | | | |
|`CUSPARSE_FORMAT_COO`|10.1| | | |`HIPSPARSE_FORMAT_COO`|4.1.0| | | | |
|`CUSPARSE_FORMAT_COO_AOS`|10.2| | |12.0|`HIPSPARSE_FORMAT_COO_AOS`|4.1.0| | | | |
|`CUSPARSE_FORMAT_CSC`|10.1| | | |`HIPSPARSE_FORMAT_CSC`|4.1.0| | | | |
|`CUSPARSE_FORMAT_CSR`|10.1| | | |`HIPSPARSE_FORMAT_CSR`|4.1.0| | | | |
|`CUSPARSE_FORMAT_SLICED_ELLPACK`|12.1| | | | | | | | | |
|`CUSPARSE_HYB_PARTITION_AUTO`| |10.2| |11.0|`HIPSPARSE_HYB_PARTITION_AUTO`|1.9.2| | | | |
|`CUSPARSE_HYB_PARTITION_MAX`| |10.2| |11.0|`HIPSPARSE_HYB_PARTITION_MAX`|1.9.2| | | | |
|`CUSPARSE_HYB_PARTITION_USER`| |10.2| |11.0|`HIPSPARSE_HYB_PARTITION_USER`|1.9.2| | | | |
|`CUSPARSE_INDEX_16U`|10.1| | | |`HIPSPARSE_INDEX_16U`|4.1.0| | | | |
|`CUSPARSE_INDEX_32I`|10.1| | | |`HIPSPARSE_INDEX_32I`|4.1.0| | | | |
|`CUSPARSE_INDEX_64I`|10.1| | | |`HIPSPARSE_INDEX_64I`|4.1.0| | | | |
|`CUSPARSE_INDEX_BASE_ONE`| | | | |`HIPSPARSE_INDEX_BASE_ONE`|1.9.2| | | | |
|`CUSPARSE_INDEX_BASE_ZERO`| | | | |`HIPSPARSE_INDEX_BASE_ZERO`|1.9.2| | | | |
|`CUSPARSE_MATRIX_TYPE_GENERAL`| | | | |`HIPSPARSE_MATRIX_TYPE_GENERAL`|1.9.2| | | | |
|`CUSPARSE_MATRIX_TYPE_HERMITIAN`| | | | |`HIPSPARSE_MATRIX_TYPE_HERMITIAN`|1.9.2| | | | |
|`CUSPARSE_MATRIX_TYPE_SYMMETRIC`| | | | |`HIPSPARSE_MATRIX_TYPE_SYMMETRIC`|1.9.2| | | | |
|`CUSPARSE_MATRIX_TYPE_TRIANGULAR`| | | | |`HIPSPARSE_MATRIX_TYPE_TRIANGULAR`|1.9.2| | | | |
|`CUSPARSE_MM_ALG_DEFAULT`|10.2|11.0| |12.0|`HIPSPARSE_MM_ALG_DEFAULT`|4.2.0| | | | |
|`CUSPARSE_MV_ALG_DEFAULT`|10.2|11.3| |12.0|`HIPSPARSE_MV_ALG_DEFAULT`|4.1.0| | | | |
|`CUSPARSE_OPERATION_CONJUGATE_TRANSPOSE`| | | | |`HIPSPARSE_OPERATION_CONJUGATE_TRANSPOSE`|1.9.2| | | | |
|`CUSPARSE_OPERATION_NON_TRANSPOSE`| | | | |`HIPSPARSE_OPERATION_NON_TRANSPOSE`|1.9.2| | | | |
|`CUSPARSE_OPERATION_TRANSPOSE`| | | | |`HIPSPARSE_OPERATION_TRANSPOSE`|1.9.2| | | | |
|`CUSPARSE_ORDER_COL`|10.1| | | |`HIPSPARSE_ORDER_COL`|5.4.0| | | | |
|`CUSPARSE_ORDER_ROW`|10.1| | | |`HIPSPARSE_ORDER_ROW`|4.2.0| | | | |
|`CUSPARSE_POINTER_MODE_DEVICE`| | | | |`HIPSPARSE_POINTER_MODE_DEVICE`|1.9.2| | | | |
|`CUSPARSE_POINTER_MODE_HOST`| | | | |`HIPSPARSE_POINTER_MODE_HOST`|1.9.2| | | | |
|`CUSPARSE_SDDMM_ALG_DEFAULT`|11.2| | | |`HIPSPARSE_SDDMM_ALG_DEFAULT`|4.3.0| | | | |
|`CUSPARSE_SIDE_LEFT`| | | |11.5| | | | | | |
|`CUSPARSE_SIDE_RIGHT`| | | |11.5| | | | | | |
|`CUSPARSE_SOLVE_POLICY_NO_LEVEL`| |12.2| | |`HIPSPARSE_SOLVE_POLICY_NO_LEVEL`|1.9.2| | | | |
|`CUSPARSE_SOLVE_POLICY_USE_LEVEL`| |12.2| | |`HIPSPARSE_SOLVE_POLICY_USE_LEVEL`|1.9.2| | | | |
|`CUSPARSE_SPARSETODENSE_ALG_DEFAULT`|11.1| | | |`HIPSPARSE_SPARSETODENSE_ALG_DEFAULT`|4.2.0| | | | |
|`CUSPARSE_SPGEMM_ALG1`|12.0| | | |`HIPSPARSE_SPGEMM_ALG1`|5.6.0| | | | |
|`CUSPARSE_SPGEMM_ALG2`|12.0| | | |`HIPSPARSE_SPGEMM_ALG2`|5.6.0| | | | |
|`CUSPARSE_SPGEMM_ALG3`|12.0| | | |`HIPSPARSE_SPGEMM_ALG3`|5.6.0| | | | |
|`CUSPARSE_SPGEMM_CSR_ALG_DETERMINITIC`|11.3| | | |`HIPSPARSE_SPGEMM_CSR_ALG_DETERMINISTIC`|5.1.0| | | | |
|`CUSPARSE_SPGEMM_CSR_ALG_NONDETERMINITIC`|11.3| | | |`HIPSPARSE_SPGEMM_CSR_ALG_NONDETERMINISTIC`|5.1.0| | | | |
|`CUSPARSE_SPGEMM_DEFAULT`|11.0| | | |`HIPSPARSE_SPGEMM_DEFAULT`|4.1.0| | | | |
|`CUSPARSE_SPMAT_DIAG_TYPE`|11.3| | | |`HIPSPARSE_SPMAT_DIAG_TYPE`|4.5.0| | | | |
|`CUSPARSE_SPMAT_FILL_MODE`|11.3| | | |`HIPSPARSE_SPMAT_FILL_MODE`|4.5.0| | | | |
|`CUSPARSE_SPMMA_ALG1`|11.1| | |11.2| | | | | | |
|`CUSPARSE_SPMMA_ALG2`|11.1| | |11.2| | | | | | |
|`CUSPARSE_SPMMA_ALG3`|11.1| | |11.2| | | | | | |
|`CUSPARSE_SPMMA_ALG4`|11.1| | |11.2| | | | | | |
|`CUSPARSE_SPMMA_PREPROCESS`|11.1| | |11.2| | | | | | |
|`CUSPARSE_SPMM_ALG_DEFAULT`|11.0| | | |`HIPSPARSE_SPMM_ALG_DEFAULT`|4.2.0| | | | |
|`CUSPARSE_SPMM_BLOCKED_ELL_ALG1`|11.2| | | |`HIPSPARSE_SPMM_BLOCKED_ELL_ALG1`|4.5.0| | | | |
|`CUSPARSE_SPMM_BSR_ALG1`|12.5| | | | | | | | | |
|`CUSPARSE_SPMM_COO_ALG1`|11.0| | | |`HIPSPARSE_SPMM_COO_ALG1`|4.2.0| | | | |
|`CUSPARSE_SPMM_COO_ALG2`|11.0| | | |`HIPSPARSE_SPMM_COO_ALG2`|4.2.0| | | | |
|`CUSPARSE_SPMM_COO_ALG3`|11.0| | | |`HIPSPARSE_SPMM_COO_ALG3`|4.2.0| | | | |
|`CUSPARSE_SPMM_COO_ALG4`|11.0| | | |`HIPSPARSE_SPMM_COO_ALG4`|4.2.0| | | | |
|`CUSPARSE_SPMM_CSR_ALG1`|11.0| | | |`HIPSPARSE_SPMM_CSR_ALG1`|4.2.0| | | | |
|`CUSPARSE_SPMM_CSR_ALG2`|11.0| | | |`HIPSPARSE_SPMM_CSR_ALG2`|4.2.0| | | | |
|`CUSPARSE_SPMM_CSR_ALG3`|11.2| | | |`HIPSPARSE_SPMM_CSR_ALG3`|4.5.0| | | | |
|`CUSPARSE_SPMM_OP_ALG_DEFAULT`|11.5| | | | | | | | | |
|`CUSPARSE_SPMV_ALG_DEFAULT`|11.2| | | |`HIPSPARSE_SPMV_ALG_DEFAULT`|4.5.0| | | | |
|`CUSPARSE_SPMV_COO_ALG1`|11.2| | | |`HIPSPARSE_SPMV_COO_ALG1`|4.5.0| | | | |
|`CUSPARSE_SPMV_COO_ALG2`|11.2| | | |`HIPSPARSE_SPMV_COO_ALG2`|4.5.0| | | | |
|`CUSPARSE_SPMV_CSR_ALG1`|11.2| | | |`HIPSPARSE_SPMV_CSR_ALG1`|4.5.0| | | | |
|`CUSPARSE_SPMV_CSR_ALG2`|11.2| | | |`HIPSPARSE_SPMV_CSR_ALG2`|4.5.0| | | | |
|`CUSPARSE_SPMV_SELL_ALG1`|12.1| | | | | | | | | |
|`CUSPARSE_SPSM_ALG_DEFAULT`|11.3| | | |`HIPSPARSE_SPSM_ALG_DEFAULT`|4.5.0| | | | |
|`CUSPARSE_SPSM_UPDATE_DIAGONAL`|12.4| | | | | | | | | |
|`CUSPARSE_SPSM_UPDATE_GENERAL`|12.4| | | | | | | | | |
|`CUSPARSE_SPSV_ALG_DEFAULT`|11.3| | | |`HIPSPARSE_SPSV_ALG_DEFAULT`|4.5.0| | | | |
|`CUSPARSE_SPSV_UPDATE_DIAGONAL`|12.1| | | | | | | | | |
|`CUSPARSE_SPSV_UPDATE_GENERAL`|12.1| | | | | | | | | |
|`CUSPARSE_STATUS_ALLOC_FAILED`| | | | |`HIPSPARSE_STATUS_ALLOC_FAILED`|1.9.2| | | | |
|`CUSPARSE_STATUS_ARCH_MISMATCH`| | | | |`HIPSPARSE_STATUS_ARCH_MISMATCH`|1.9.2| | | | |
|`CUSPARSE_STATUS_EXECUTION_FAILED`| | | | |`HIPSPARSE_STATUS_EXECUTION_FAILED`|1.9.2| | | | |
|`CUSPARSE_STATUS_INSUFFICIENT_RESOURCES`|11.0| | | |`HIPSPARSE_STATUS_INSUFFICIENT_RESOURCES`|4.1.0| | | | |
|`CUSPARSE_STATUS_INTERNAL_ERROR`| | | | |`HIPSPARSE_STATUS_INTERNAL_ERROR`|1.9.2| | | | |
|`CUSPARSE_STATUS_INVALID_VALUE`| | | | |`HIPSPARSE_STATUS_INVALID_VALUE`|1.9.2| | | | |
|`CUSPARSE_STATUS_MAPPING_ERROR`| | | | |`HIPSPARSE_STATUS_MAPPING_ERROR`|1.9.2| | | | |
|`CUSPARSE_STATUS_MATRIX_TYPE_NOT_SUPPORTED`| | | | |`HIPSPARSE_STATUS_MATRIX_TYPE_NOT_SUPPORTED`|1.9.2| | | | |
|`CUSPARSE_STATUS_NOT_INITIALIZED`| | | | |`HIPSPARSE_STATUS_NOT_INITIALIZED`|1.9.2| | | | |
|`CUSPARSE_STATUS_NOT_SUPPORTED`|10.2| | | |`HIPSPARSE_STATUS_NOT_SUPPORTED`|4.1.0| | | | |
|`CUSPARSE_STATUS_SUCCESS`| | | | |`HIPSPARSE_STATUS_SUCCESS`|1.9.2| | | | |
|`CUSPARSE_STATUS_ZERO_PIVOT`| | | | |`HIPSPARSE_STATUS_ZERO_PIVOT`|1.9.2| | | | |
|`bsric02Info`| | | | |`bsric02Info`|3.8.0| | | | |
|`bsric02Info_t`| | | | |`bsric02Info_t`|3.8.0| | | | |
|`bsrilu02Info`| |12.2| | |`bsrilu02Info`|3.9.0| | | | |
|`bsrilu02Info_t`| |12.2| | |`bsrilu02Info_t`|3.9.0| | | | |
|`bsrsm2Info`| |12.2| | |`bsrsm2Info`|4.5.0| | | | |
|`bsrsm2Info_t`| |12.2| | |`bsrsm2Info_t`|4.5.0| | | | |
|`bsrsv2Info`| |12.2| | |`bsrsv2Info`|3.6.0| | | | |
|`bsrsv2Info_t`| |12.2| | |`bsrsv2Info_t`|3.6.0| | | | |
|`csrgemm2Info`| | | |12.0|`csrgemm2Info`|2.8.0| | | | |
|`csrgemm2Info_t`| | | |12.0|`csrgemm2Info_t`|2.8.0| | | | |
|`csric02Info`| |12.2| | |`csric02Info`|3.1.0| | | | |
|`csric02Info_t`| |12.2| | |`csric02Info_t`|3.1.0| | | | |
|`csrilu02Info`| |12.2| | |`csrilu02Info`|1.9.2| | | | |
|`csrilu02Info_t`| |12.2| | |`csrilu02Info_t`|1.9.2| | | | |
|`csrsm2Info`|9.2| | |12.0| | | | | | |
|`csrsm2Info_t`|9.2| | |12.0|`csrsm2Info_t`|3.1.0| | | | |
|`csrsv2Info`| | | |12.0| | | | | | |
|`csrsv2Info_t`| | | |12.0|`csrsv2Info_t`|1.9.2| | | | |
|`csru2csrInfo`| |12.2| | |`csru2csrInfo`|4.2.0| | | | |
|`csru2csrInfo_t`| |12.2| | |`csru2csrInfo_t`|4.2.0| | | | |
|`cusparseAction_t`| | | | |`hipsparseAction_t`|1.9.2| | | | |
|`cusparseAlgMode_t`|8.0| | |12.0| | | | | | |
|`cusparseColorAlg_t`|8.0|12.2| | | | | | | | |
|`cusparseColorInfo`| |12.2| | | | | | | | |
|`cusparseColorInfo_t`| |12.2| | |`hipsparseColorInfo_t`|4.5.0| | | | |
|`cusparseConstDnMatDescr_t`|12.0| | | |`hipsparseConstDnMatDescr_t`|6.0.0| | | | |
|`cusparseConstDnVecDescr_t`|12.0| | | |`hipsparseConstDnVecDescr_t`|6.0.0| | | | |
|`cusparseConstSpMatDescr_t`|12.0| | | |`hipsparseConstSpMatDescr_t`|6.0.0| | | | |
|`cusparseConstSpVecDescr_t`|12.0| | | |`hipsparseConstSpVecDescr_t`|6.0.0| | | | |
|`cusparseContext`| | | | | | | | | | |
|`cusparseCsr2CscAlg_t`|10.1| | | |`hipsparseCsr2CscAlg_t`|5.4.0| | | | |
|`cusparseDenseToSparseAlg_t`|11.1| | | |`hipsparseDenseToSparseAlg_t`|4.2.0| | | | |
|`cusparseDiagType_t`| | | | |`hipsparseDiagType_t`|1.9.2| | | | |
|`cusparseDirection_t`| | | | |`hipsparseDirection_t`|3.2.0| | | | |
|`cusparseDnMatDescr`|10.1| | | | | | | | | |
|`cusparseDnMatDescr_t`|10.1| | | |`hipsparseDnMatDescr_t`|4.2.0| | | | |
|`cusparseDnVecDescr`|10.2| | | | | | | | | |
|`cusparseDnVecDescr_t`|10.2| | | |`hipsparseDnVecDescr_t`|4.1.0| | | | |
|`cusparseFillMode_t`| | | | |`hipsparseFillMode_t`|1.9.2| | | | |
|`cusparseFormat_t`|10.1| | | |`hipsparseFormat_t`|4.1.0| | | | |
|`cusparseHandle_t`| | | | |`hipsparseHandle_t`|1.9.2| | | | |
|`cusparseHybMat`| |10.2| |11.0| | | | | | |
|`cusparseHybMat_t`| |10.2| |11.0|`hipsparseHybMat_t`|1.9.2| | | | |
|`cusparseHybPartition_t`| |10.2| |11.0|`hipsparseHybPartition_t`|1.9.2| | | | |
|`cusparseIndexBase_t`| | | | |`hipsparseIndexBase_t`|1.9.2| | | | |
|`cusparseIndexType_t`|10.1| | | |`hipsparseIndexType_t`|4.1.0| | | | |
|`cusparseLoggerCallback_t`|11.5| | | | | | | | | |
|`cusparseMatDescr`| | | | | | | | | | |
|`cusparseMatDescr_t`| | | | |`hipsparseMatDescr_t`|1.9.2| | | | |
|`cusparseMatrixType_t`| | | | |`hipsparseMatrixType_t`|1.9.2| | | | |
|`cusparseOperation_t`| | | | |`hipsparseOperation_t`|1.9.2| | | | |
|`cusparseOrder_t`|10.1| | | |`hipsparseOrder_t`|4.2.0| | | | |
|`cusparsePointerMode_t`| | | | |`hipsparsePointerMode_t`|1.9.2| | | | |
|`cusparseSDDMMAlg_t`|11.2| | | |`hipsparseSDDMMAlg_t`|4.3.0| | | | |
|`cusparseSideMode_t`| | | |11.5| | | | | | |
|`cusparseSolveAnalysisInfo`| |10.2| |11.0| | | | | | |
|`cusparseSolveAnalysisInfo_t`| |10.2| |11.0| | | | | | |
|`cusparseSolvePolicy_t`| |12.2| | |`hipsparseSolvePolicy_t`|1.9.2| | | | |
|`cusparseSpGEMMAlg_t`|11.0| | | |`hipsparseSpGEMMAlg_t`|4.1.0| | | | |
|`cusparseSpGEMMDescr`|11.0| | | |`hipsparseSpGEMMDescr`|4.1.0| | | | |
|`cusparseSpGEMMDescr_t`|11.0| | | |`hipsparseSpGEMMDescr_t`|4.1.0| | | | |
|`cusparseSpMMAlg_t`|10.1| | | |`hipsparseSpMMAlg_t`|4.2.0| | | | |
|`cusparseSpMMOpAlg_t`|11.5| | | | | | | | | |
|`cusparseSpMMOpPlan`|11.5| | | | | | | | | |
|`cusparseSpMMOpPlan_t`|11.5| | | | | | | | | |
|`cusparseSpMVAlg_t`|10.2| | | |`hipsparseSpMVAlg_t`|4.1.0| | | | |
|`cusparseSpMatAttribute_t`|11.3| | | |`hipsparseSpMatAttribute_t`|4.5.0| | | | |
|`cusparseSpMatDescr`|10.1| | | | | | | | | |
|`cusparseSpMatDescr_t`|10.1| | | |`hipsparseSpMatDescr_t`|4.1.0| | | | |
|`cusparseSpSMAlg_t`|11.3| | | |`hipsparseSpSMAlg_t`|4.5.0| | | | |
|`cusparseSpSMDescr`|11.3| | | |`hipsparseSpSMDescr`|4.5.0| | | | |
|`cusparseSpSMDescr_t`|11.3| | | |`hipsparseSpSMDescr_t`|4.5.0| | | | |
|`cusparseSpSMUpdate_t`|12.4| | | | | | | | | |
|`cusparseSpSVAlg_t`|11.3| | | |`hipsparseSpSVAlg_t`|4.5.0| | | | |
|`cusparseSpSVDescr`|11.3| | | |`hipsparseSpSVDescr`|4.5.0| | | | |
|`cusparseSpSVDescr_t`|11.3| | | |`hipsparseSpSVDescr_t`|4.5.0| | | | |
|`cusparseSpSVUpdate_t`|12.1| | | | | | | | | |
|`cusparseSpVecDescr`|10.2| | | | | | | | | |
|`cusparseSpVecDescr_t`|10.2| | | |`hipsparseSpVecDescr_t`|4.1.0| | | | |
|`cusparseSparseToDenseAlg_t`|11.1| | | |`hipsparseSparseToDenseAlg_t`|4.2.0| | | | |
|`cusparseStatus_t`| | | | |`hipsparseStatus_t`|1.9.2| | | | |
|`pruneInfo`|9.0|12.2| | |`pruneInfo`|3.9.0| | | | |
|`pruneInfo_t`|9.0|12.2| | |`pruneInfo_t`|3.9.0| | | | |

## **5. CUSPARSE Management Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCreate`| | | | |`hipsparseCreate`|1.9.2| | | | |
|`cusparseDestroy`| | | | |`hipsparseDestroy`|1.9.2| | | | |
|`cusparseGetErrorName`|10.2| | | |`hipsparseGetErrorName`|6.0.0| | | | |
|`cusparseGetErrorString`|10.2| | | |`hipsparseGetErrorString`|6.0.0| | | | |
|`cusparseGetPointerMode`| | | | |`hipsparseGetPointerMode`|1.9.2| | | | |
|`cusparseGetStream`|8.0| | | |`hipsparseGetStream`|1.9.2| | | | |
|`cusparseGetVersion`| | | | |`hipsparseGetVersion`|1.9.2| | | | |
|`cusparseSetPointerMode`| | | | |`hipsparseSetPointerMode`|1.9.2| | | | |
|`cusparseSetStream`| | | | |`hipsparseSetStream`|1.9.2| | | | |

## **6. CUSPARSE Logging**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseLoggerForceDisable`|11.5| | | | | | | | | |
|`cusparseLoggerOpenFile`|11.5| | | | | | | | | |
|`cusparseLoggerSetCallback`|11.5| | | | | | | | | |
|`cusparseLoggerSetFile`|11.5| | | | | | | | | |
|`cusparseLoggerSetLevel`|11.5| | | | | | | | | |
|`cusparseLoggerSetMask`|11.5| | | | | | | | | |

## **7. CUSPARSE Helper Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCopyMatDescr`|8.0| | |12.0|`hipsparseCopyMatDescr`|1.9.2| | | | |
|`cusparseCreateBsric02Info`| |12.2| | |`hipsparseCreateBsric02Info`|3.8.0|6.2.0| | | |
|`cusparseCreateBsrilu02Info`| |12.2| | |`hipsparseCreateBsrilu02Info`|3.9.0|6.2.0| | | |
|`cusparseCreateBsrsm2Info`| |12.2| | |`hipsparseCreateBsrsm2Info`|4.5.0|6.2.0| | | |
|`cusparseCreateBsrsv2Info`| |12.2| | |`hipsparseCreateBsrsv2Info`|3.6.0|6.2.0| | | |
|`cusparseCreateColorInfo`| |12.2| | |`hipsparseCreateColorInfo`|4.5.0|6.2.0| | | |
|`cusparseCreateCsrgemm2Info`| |11.0| |12.0|`hipsparseCreateCsrgemm2Info`|2.8.0|3.9.0| | | |
|`cusparseCreateCsric02Info`| |12.2| | |`hipsparseCreateCsric02Info`|3.1.0|6.2.0| | | |
|`cusparseCreateCsrilu02Info`| |12.2| | |`hipsparseCreateCsrilu02Info`|1.9.2|6.2.0| | | |
|`cusparseCreateCsrsm2Info`|9.2|11.3| |12.0|`hipsparseCreateCsrsm2Info`|3.1.0|5.6.0| | | |
|`cusparseCreateCsrsv2Info`| |11.3| |12.0|`hipsparseCreateCsrsv2Info`|1.9.2|5.6.0| | | |
|`cusparseCreateHybMat`| |10.2| |11.0|`hipsparseCreateHybMat`|1.9.2|3.9.0| | | |
|`cusparseCreateMatDescr`| | | | |`hipsparseCreateMatDescr`|1.9.2| | | | |
|`cusparseCreatePruneInfo`|9.0|12.2| | |`hipsparseCreatePruneInfo`|3.9.0|6.2.0| | | |
|`cusparseCreateSolveAnalysisInfo`| |10.2| |11.0| | | | | | |
|`cusparseDestroyBsric02Info`| |12.2| | |`hipsparseDestroyBsric02Info`|3.8.0|6.2.0| | | |
|`cusparseDestroyBsrilu02Info`| |12.2| | |`hipsparseDestroyBsrilu02Info`|3.9.0|6.2.0| | | |
|`cusparseDestroyBsrsm2Info`| |12.2| | |`hipsparseDestroyBsrsm2Info`|4.5.0|6.2.0| | | |
|`cusparseDestroyBsrsv2Info`| |12.2| | |`hipsparseDestroyBsrsv2Info`|3.6.0|6.2.0| | | |
|`cusparseDestroyColorInfo`| |12.2| | |`hipsparseDestroyColorInfo`|4.5.0|6.2.0| | | |
|`cusparseDestroyCsrgemm2Info`| |11.0| |12.0|`hipsparseDestroyCsrgemm2Info`|2.8.0|3.9.0| | | |
|`cusparseDestroyCsric02Info`| |12.2| | |`hipsparseDestroyCsric02Info`|3.1.0|6.2.0| | | |
|`cusparseDestroyCsrilu02Info`| |12.2| | |`hipsparseDestroyCsrilu02Info`|1.9.2|6.2.0| | | |
|`cusparseDestroyCsrsm2Info`|9.2|11.3| |12.0|`hipsparseDestroyCsrsm2Info`|3.1.0|5.6.0| | | |
|`cusparseDestroyCsrsv2Info`| |11.3| |12.0|`hipsparseDestroyCsrsv2Info`|1.9.2|5.6.0| | | |
|`cusparseDestroyHybMat`| |10.2| |11.0|`hipsparseDestroyHybMat`|1.9.2|3.9.0| | | |
|`cusparseDestroyMatDescr`| | | | |`hipsparseDestroyMatDescr`|1.9.2| | | | |
|`cusparseDestroyPruneInfo`|9.0|12.2| | |`hipsparseDestroyPruneInfo`|3.9.0|6.2.0| | | |
|`cusparseDestroySolveAnalysisInfo`| |10.2| |11.0| | | | | | |
|`cusparseGetLevelInfo`| | | |11.0| | | | | | |
|`cusparseGetMatDiagType`| | | | |`hipsparseGetMatDiagType`|1.9.2| | | | |
|`cusparseGetMatFillMode`| | | | |`hipsparseGetMatFillMode`|1.9.2| | | | |
|`cusparseGetMatIndexBase`| | | | |`hipsparseGetMatIndexBase`|1.9.2| | | | |
|`cusparseGetMatType`| | | | |`hipsparseGetMatType`|1.9.2| | | | |
|`cusparseSetMatDiagType`| | | | |`hipsparseSetMatDiagType`|1.9.2| | | | |
|`cusparseSetMatFillMode`| | | | |`hipsparseSetMatFillMode`|1.9.2| | | | |
|`cusparseSetMatIndexBase`| | | | |`hipsparseSetMatIndexBase`|1.9.2| | | | |
|`cusparseSetMatType`| | | | |`hipsparseSetMatType`|1.9.2| | | | |

## **8. CUSPARSE Level 1 Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCaxpyi`| |11.0| |12.0|`hipsparseCaxpyi`|3.1.0|3.9.0| | | |
|`cusparseCdotci`| |10.2| |11.0|`hipsparseCdotci`|3.1.0|3.9.0| | | |
|`cusparseCdoti`| |10.2| |11.0|`hipsparseCdoti`|3.1.0|3.9.0| | | |
|`cusparseCgthr`| |11.0| |12.0|`hipsparseCgthr`|3.1.0|3.9.0| | | |
|`cusparseCgthrz`| |11.0| |12.0|`hipsparseCgthrz`|3.1.0|3.9.0| | | |
|`cusparseCsctr`| |11.0| |12.0|`hipsparseCsctr`|3.1.0|3.9.0| | | |
|`cusparseDaxpyi`| |11.0| |12.0|`hipsparseDaxpyi`|1.9.2|3.9.0| | | |
|`cusparseDdoti`| |10.2| |11.0|`hipsparseDdoti`|1.9.2|3.9.0| | | |
|`cusparseDgthr`| |11.0| |12.0|`hipsparseDgthr`|1.9.2|3.9.0| | | |
|`cusparseDgthrz`| |11.0| |12.0|`hipsparseDgthrz`|1.9.2|3.9.0| | | |
|`cusparseDroti`| |11.0| |12.0|`hipsparseDroti`|1.9.2|3.9.0| | | |
|`cusparseDsctr`| |11.0| |12.0|`hipsparseDsctr`|1.9.2|3.9.0| | | |
|`cusparseSaxpyi`| |11.0| |12.0|`hipsparseSaxpyi`|1.9.2|3.9.0| | | |
|`cusparseSdoti`| |10.2| |11.0|`hipsparseSdoti`|1.9.2|3.9.0| | | |
|`cusparseSgthr`| |11.0| |12.0|`hipsparseSgthr`|1.9.2|3.9.0| | | |
|`cusparseSgthrz`| |11.0| |12.0|`hipsparseSgthrz`|1.9.2|3.9.0| | | |
|`cusparseSroti`| |11.0| |12.0|`hipsparseSroti`|1.9.2|3.9.0| | | |
|`cusparseSsctr`| |11.0| |12.0|`hipsparseSsctr`|1.9.2|3.9.0| | | |
|`cusparseZaxpyi`| |11.0| |12.0|`hipsparseZaxpyi`|3.1.0|3.9.0| | | |
|`cusparseZdotci`| |10.2| |11.0|`hipsparseZdotci`|3.1.0|3.9.0| | | |
|`cusparseZdoti`| |10.2| |11.0|`hipsparseZdoti`|3.1.0|3.9.0| | | |
|`cusparseZgthr`| |11.0| |12.0|`hipsparseZgthr`|3.1.0|3.9.0| | | |
|`cusparseZgthrz`| |11.0| |12.0|`hipsparseZgthrz`|3.1.0|3.9.0| | | |
|`cusparseZsctr`| |11.0| |12.0|`hipsparseZsctr`|3.1.0|3.9.0| | | |

## **9. CUSPARSE Level 2 Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCbsrmv`| | | | |`hipsparseCbsrmv`|3.5.0| | | | |
|`cusparseCbsrsv2_analysis`| |12.2| | |`hipsparseCbsrsv2_analysis`|3.6.0|6.2.0| | | |
|`cusparseCbsrsv2_bufferSize`| |12.2| | |`hipsparseCbsrsv2_bufferSize`|3.6.0|6.2.0| | | |
|`cusparseCbsrsv2_bufferSizeExt`| |12.2| | |`hipsparseCbsrsv2_bufferSizeExt`|3.6.0| | | | |
|`cusparseCbsrsv2_solve`| |12.2| | |`hipsparseCbsrsv2_solve`|3.6.0|6.2.0| | | |
|`cusparseCbsrxmv`| |12.2| | |`hipsparseCbsrxmv`|4.5.0|6.2.0| | | |
|`cusparseCcsrmv`| |10.2| |11.0|`hipsparseCcsrmv`|3.1.0|3.9.0| | | |
|`cusparseCcsrmv_mp`|8.0|10.2| |11.0| | | | | | |
|`cusparseCcsrsv2_analysis`| |11.3| |12.0|`hipsparseCcsrsv2_analysis`|3.1.0|5.6.0| | | |
|`cusparseCcsrsv2_bufferSize`| |11.3| |12.0|`hipsparseCcsrsv2_bufferSize`|3.1.0|5.6.0| | | |
|`cusparseCcsrsv2_bufferSizeExt`| |11.3| |12.0|`hipsparseCcsrsv2_bufferSizeExt`|3.1.0| | | | |
|`cusparseCcsrsv2_solve`| |11.3| |12.0|`hipsparseCcsrsv2_solve`|3.1.0|5.6.0| | | |
|`cusparseCcsrsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseCcsrsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseCgemvi`|7.5| | | |`hipsparseCgemvi`|4.3.0| | | | |
|`cusparseCgemvi_bufferSize`|7.5| | | |`hipsparseCgemvi_bufferSize`|4.3.0| | | | |
|`cusparseChybmv`| |10.2| |11.0|`hipsparseChybmv`|3.1.0|3.9.0| | | |
|`cusparseChybsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseChybsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseCsrmvEx`|8.0|11.2| |12.0| | | | | | |
|`cusparseCsrmvEx_bufferSize`|8.0|11.2| |12.0| | | | | | |
|`cusparseCsrsv_analysisEx`|8.0|10.2| |11.0| | | | | | |
|`cusparseCsrsv_solveEx`|8.0|10.2| |11.0| | | | | | |
|`cusparseDbsrmv`| | | | |`hipsparseDbsrmv`|3.5.0| | | | |
|`cusparseDbsrsv2_analysis`| |12.2| | |`hipsparseDbsrsv2_analysis`|3.6.0|6.2.0| | | |
|`cusparseDbsrsv2_bufferSize`| |12.2| | |`hipsparseDbsrsv2_bufferSize`|3.6.0|6.2.0| | | |
|`cusparseDbsrsv2_bufferSizeExt`| |12.2| | |`hipsparseDbsrsv2_bufferSizeExt`|3.6.0| | | | |
|`cusparseDbsrsv2_solve`| |12.2| | |`hipsparseDbsrsv2_solve`|3.6.0|6.2.0| | | |
|`cusparseDbsrxmv`| |12.2| | |`hipsparseDbsrxmv`|4.5.0|6.2.0| | | |
|`cusparseDcsrmv`| |10.2| |11.0|`hipsparseDcsrmv`|1.9.2|3.9.0| | | |
|`cusparseDcsrmv_mp`|8.0|10.2| |11.0| | | | | | |
|`cusparseDcsrsv2_analysis`| |11.3| |12.0|`hipsparseDcsrsv2_analysis`|1.9.2|5.6.0| | | |
|`cusparseDcsrsv2_bufferSize`| |11.3| |12.0|`hipsparseDcsrsv2_bufferSize`|1.9.2|5.6.0| | | |
|`cusparseDcsrsv2_bufferSizeExt`| |11.3| |12.0|`hipsparseDcsrsv2_bufferSizeExt`|1.9.2| | | | |
|`cusparseDcsrsv2_solve`| |11.3| |12.0|`hipsparseDcsrsv2_solve`|1.9.2|5.6.0| | | |
|`cusparseDcsrsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseDcsrsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseDgemvi`|7.5| | | |`hipsparseDgemvi`|4.3.0| | | | |
|`cusparseDgemvi_bufferSize`|7.5| | | |`hipsparseDgemvi_bufferSize`|4.3.0| | | | |
|`cusparseDhybmv`| |10.2| |11.0|`hipsparseDhybmv`|1.9.2|3.9.0| | | |
|`cusparseDhybsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseDhybsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseSbsrmv`| | | | |`hipsparseSbsrmv`|3.5.0| | | | |
|`cusparseSbsrsv2_analysis`| |12.2| | |`hipsparseSbsrsv2_analysis`|3.6.0|6.2.0| | | |
|`cusparseSbsrsv2_bufferSize`| |12.2| | |`hipsparseSbsrsv2_bufferSize`|3.6.0|6.2.0| | | |
|`cusparseSbsrsv2_bufferSizeExt`| |12.2| | |`hipsparseSbsrsv2_bufferSizeExt`|3.6.0| | | | |
|`cusparseSbsrsv2_solve`| |12.2| | |`hipsparseSbsrsv2_solve`|3.6.0|6.2.0| | | |
|`cusparseSbsrxmv`| |12.2| | |`hipsparseSbsrxmv`|4.5.0|6.2.0| | | |
|`cusparseScsrmv`| |10.2| |11.0|`hipsparseScsrmv`|1.9.2|3.9.0| | | |
|`cusparseScsrmv_mp`|8.0|10.2| |11.0| | | | | | |
|`cusparseScsrsv2_analysis`| |11.3| |12.0|`hipsparseScsrsv2_analysis`|1.9.2|5.6.0| | | |
|`cusparseScsrsv2_bufferSize`| |11.3| |12.0|`hipsparseScsrsv2_bufferSize`|1.9.2|5.6.0| | | |
|`cusparseScsrsv2_bufferSizeExt`| |11.3| |12.0|`hipsparseScsrsv2_bufferSizeExt`|1.9.2| | | | |
|`cusparseScsrsv2_solve`| |11.3| |12.0|`hipsparseScsrsv2_solve`|1.9.2|5.6.0| | | |
|`cusparseScsrsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseScsrsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseSgemvi`|7.5| | | |`hipsparseSgemvi`|4.3.0| | | | |
|`cusparseSgemvi_bufferSize`|7.5| | | |`hipsparseSgemvi_bufferSize`|4.3.0| | | | |
|`cusparseShybmv`| |10.2| |11.0|`hipsparseShybmv`|1.9.2|3.9.0| | | |
|`cusparseShybsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseShybsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseXbsrsv2_zeroPivot`| |12.2| | |`hipsparseXbsrsv2_zeroPivot`|3.6.0|6.2.0| | | |
|`cusparseXcsrsv2_zeroPivot`| |11.3| |12.0|`hipsparseXcsrsv2_zeroPivot`|1.9.2|5.6.0| | | |
|`cusparseZbsrmv`| | | | |`hipsparseZbsrmv`|3.5.0| | | | |
|`cusparseZbsrsv2_analysis`| |12.2| | |`hipsparseZbsrsv2_analysis`|3.6.0|6.2.0| | | |
|`cusparseZbsrsv2_bufferSize`| |12.2| | |`hipsparseZbsrsv2_bufferSize`|3.6.0|6.2.0| | | |
|`cusparseZbsrsv2_bufferSizeExt`| |12.2| | |`hipsparseZbsrsv2_bufferSizeExt`|3.6.0| | | | |
|`cusparseZbsrsv2_solve`| |12.2| | |`hipsparseZbsrsv2_solve`|3.6.0|6.2.0| | | |
|`cusparseZbsrxmv`| |12.2| | |`hipsparseZbsrxmv`|4.5.0|6.2.0| | | |
|`cusparseZcsrmv`| |10.2| |11.0|`hipsparseZcsrmv`|3.1.0|3.9.0| | | |
|`cusparseZcsrmv_mp`|8.0|10.2| |11.0| | | | | | |
|`cusparseZcsrsv2_analysis`| |11.3| |12.0|`hipsparseZcsrsv2_analysis`|3.1.0|5.6.0| | | |
|`cusparseZcsrsv2_bufferSize`| |11.3| |12.0|`hipsparseZcsrsv2_bufferSize`|3.1.0|5.6.0| | | |
|`cusparseZcsrsv2_bufferSizeExt`| |11.3| |12.0|`hipsparseZcsrsv2_bufferSizeExt`|3.1.0| | | | |
|`cusparseZcsrsv2_solve`| |11.3| |12.0|`hipsparseZcsrsv2_solve`|3.1.0|5.6.0| | | |
|`cusparseZcsrsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseZcsrsv_solve`| |10.2| |11.0| | | | | | |
|`cusparseZgemvi`|7.5| | | |`hipsparseZgemvi`|4.3.0| | | | |
|`cusparseZgemvi_bufferSize`|7.5| | | |`hipsparseZgemvi_bufferSize`|4.3.0| | | | |
|`cusparseZhybmv`| |10.2| |11.0|`hipsparseZhybmv`|3.1.0|3.9.0| | | |
|`cusparseZhybsv_analysis`| |10.2| |11.0| | | | | | |
|`cusparseZhybsv_solve`| |10.2| |11.0| | | | | | |

## **10. CUSPARSE Level 3 Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCbsrmm`| | | | |`hipsparseCbsrmm`|3.7.0| | | | |
|`cusparseCbsrsm2_analysis`| |12.2| | |`hipsparseCbsrsm2_analysis`|4.5.0|6.2.0| | | |
|`cusparseCbsrsm2_bufferSize`| |12.2| | |`hipsparseCbsrsm2_bufferSize`|4.5.0|6.2.0| | | |
|`cusparseCbsrsm2_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseCbsrsm2_solve`| |12.2| | |`hipsparseCbsrsm2_solve`|4.5.0|6.2.0| | | |
|`cusparseCcsrmm`| |10.2| |11.0|`hipsparseCcsrmm`|3.1.0|3.9.0| | | |
|`cusparseCcsrmm2`| |10.2| |11.0|`hipsparseCcsrmm2`|3.1.0|3.9.0| | | |
|`cusparseCcsrsm2_analysis`|9.2|11.3| |12.0|`hipsparseCcsrsm2_analysis`|3.1.0|5.6.0| | | |
|`cusparseCcsrsm2_bufferSizeExt`|9.2|11.3| |12.0|`hipsparseCcsrsm2_bufferSizeExt`|3.1.0|5.6.0| | | |
|`cusparseCcsrsm2_solve`|9.2|11.3| |12.0|`hipsparseCcsrsm2_solve`|3.1.0|5.6.0| | | |
|`cusparseCcsrsm_analysis`| |10.2| |11.0| | | | | | |
|`cusparseCcsrsm_solve`| |10.2| |11.0| | | | | | |
|`cusparseCgemmi`|8.0|11.0| |12.0|`hipsparseCgemmi`|3.7.0|3.9.0| | | |
|`cusparseDbsrmm`| | | | |`hipsparseDbsrmm`|3.7.0| | | | |
|`cusparseDbsrsm2_analysis`| |12.2| | |`hipsparseDbsrsm2_analysis`|4.5.0|6.2.0| | | |
|`cusparseDbsrsm2_bufferSize`| |12.2| | |`hipsparseDbsrsm2_bufferSize`|4.5.0|6.2.0| | | |
|`cusparseDbsrsm2_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseDbsrsm2_solve`| |12.2| | |`hipsparseDbsrsm2_solve`|4.5.0|6.2.0| | | |
|`cusparseDcsrmm`| |10.2| |11.0|`hipsparseDcsrmm`|1.9.2|3.9.0| | | |
|`cusparseDcsrmm2`| |10.2| |11.0|`hipsparseDcsrmm2`|1.9.2|3.9.0| | | |
|`cusparseDcsrsm2_analysis`|9.2|11.3| |12.0|`hipsparseDcsrsm2_analysis`|3.1.0|5.6.0| | | |
|`cusparseDcsrsm2_bufferSizeExt`|9.2|11.3| |12.0|`hipsparseDcsrsm2_bufferSizeExt`|3.1.0|5.6.0| | | |
|`cusparseDcsrsm2_solve`|9.2|11.3| |12.0|`hipsparseDcsrsm2_solve`|3.1.0|5.6.0| | | |
|`cusparseDcsrsm_analysis`| |10.2| |11.0| | | | | | |
|`cusparseDcsrsm_solve`| |10.2| |11.0| | | | | | |
|`cusparseDgemmi`|8.0|11.0| |12.0|`hipsparseDgemmi`|3.7.0|3.9.0| | | |
|`cusparseSbsrmm`| | | | |`hipsparseSbsrmm`|3.7.0| | | | |
|`cusparseSbsrsm2_analysis`| |12.2| | |`hipsparseSbsrsm2_analysis`|4.5.0|6.2.0| | | |
|`cusparseSbsrsm2_bufferSize`| |12.2| | |`hipsparseSbsrsm2_bufferSize`|4.5.0|6.2.0| | | |
|`cusparseSbsrsm2_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseSbsrsm2_solve`| |12.2| | |`hipsparseSbsrsm2_solve`|4.5.0|6.2.0| | | |
|`cusparseScsrmm`| |10.2| |11.0|`hipsparseScsrmm`|1.9.2|3.9.0| | | |
|`cusparseScsrmm2`| |10.2| |11.0|`hipsparseScsrmm2`|1.9.2|3.9.0| | | |
|`cusparseScsrsm2_analysis`|9.2|11.3| |12.0|`hipsparseScsrsm2_analysis`|3.1.0|5.6.0| | | |
|`cusparseScsrsm2_bufferSizeExt`|9.2|11.3| |12.0|`hipsparseScsrsm2_bufferSizeExt`|3.1.0|5.6.0| | | |
|`cusparseScsrsm2_solve`|9.2|11.3| |12.0|`hipsparseScsrsm2_solve`|3.1.0|5.6.0| | | |
|`cusparseScsrsm_analysis`| |10.2| |11.0| | | | | | |
|`cusparseScsrsm_solve`| |10.2| |11.0| | | | | | |
|`cusparseSgemmi`|8.0|11.0| |12.0|`hipsparseSgemmi`|3.7.0|3.9.0| | | |
|`cusparseXbsrsm2_zeroPivot`| |12.2| | |`hipsparseXbsrsm2_zeroPivot`|4.5.0|6.2.0| | | |
|`cusparseXcsrsm2_zeroPivot`|9.2|11.3| |12.0|`hipsparseXcsrsm2_zeroPivot`|3.1.0|5.6.0| | | |
|`cusparseZbsrmm`| | | | |`hipsparseZbsrmm`|3.7.0| | | | |
|`cusparseZbsrsm2_analysis`| |12.2| | |`hipsparseZbsrsm2_analysis`|4.5.0|6.2.0| | | |
|`cusparseZbsrsm2_bufferSize`| |12.2| | |`hipsparseZbsrsm2_bufferSize`|4.5.0|6.2.0| | | |
|`cusparseZbsrsm2_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseZbsrsm2_solve`| |12.2| | |`hipsparseZbsrsm2_solve`|4.5.0|6.2.0| | | |
|`cusparseZcsrmm`| |10.2| |11.0|`hipsparseZcsrmm`|3.1.0|3.9.0| | | |
|`cusparseZcsrmm2`| |10.2| |11.0|`hipsparseZcsrmm2`|3.1.0|3.9.0| | | |
|`cusparseZcsrsm2_analysis`|9.2|11.3| |12.0|`hipsparseZcsrsm2_analysis`|3.1.0|5.6.0| | | |
|`cusparseZcsrsm2_bufferSizeExt`|9.2|11.3| |12.0|`hipsparseZcsrsm2_bufferSizeExt`|3.1.0|5.6.0| | | |
|`cusparseZcsrsm2_solve`|9.2|11.3| |12.0|`hipsparseZcsrsm2_solve`|3.1.0|5.6.0| | | |
|`cusparseZcsrsm_analysis`| |10.2| |11.0| | | | | | |
|`cusparseZcsrsm_solve`| |10.2| |11.0| | | | | | |
|`cusparseZgemmi`|8.0|11.0| |12.0|`hipsparseZgemmi`|3.7.0|3.9.0| | | |

## **11. CUSPARSE Extra Function Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCcsrgeam`| |10.2| |11.0|`hipsparseCcsrgeam`|3.5.0|3.9.0| | | |
|`cusparseCcsrgeam2`|10.0| | | |`hipsparseCcsrgeam2`|3.5.0| | | | |
|`cusparseCcsrgeam2_bufferSizeExt`|10.0| | | |`hipsparseCcsrgeam2_bufferSizeExt`|3.5.0| | | | |
|`cusparseCcsrgemm`| |10.2| |11.0|`hipsparseCcsrgemm`|3.1.0|3.9.0| | | |
|`cusparseCcsrgemm2`| |11.0| |12.0|`hipsparseCcsrgemm2`|3.1.0|3.9.0| | | |
|`cusparseCcsrgemm2_bufferSizeExt`| |11.0| |12.0|`hipsparseCcsrgemm2_bufferSizeExt`|3.1.0|3.9.0| | | |
|`cusparseDcsrgeam`| |10.2| |11.0|`hipsparseDcsrgeam`|3.5.0|3.9.0| | | |
|`cusparseDcsrgeam2`|10.0| | | |`hipsparseDcsrgeam2`|3.5.0| | | | |
|`cusparseDcsrgeam2_bufferSizeExt`|10.0| | | |`hipsparseDcsrgeam2_bufferSizeExt`|3.5.0| | | | |
|`cusparseDcsrgemm`| |10.2| |11.0|`hipsparseDcsrgemm`|2.8.0|3.9.0| | | |
|`cusparseDcsrgemm2`| |11.0| |12.0|`hipsparseDcsrgemm2`|2.8.0|3.9.0| | | |
|`cusparseDcsrgemm2_bufferSizeExt`| |11.0| |12.0|`hipsparseDcsrgemm2_bufferSizeExt`|2.8.0|3.9.0| | | |
|`cusparseScsrgeam`| |10.2| |11.0|`hipsparseScsrgeam`|3.5.0|3.9.0| | | |
|`cusparseScsrgeam2`|10.0| | | |`hipsparseScsrgeam2`|3.5.0| | | | |
|`cusparseScsrgeam2_bufferSizeExt`|10.0| | | |`hipsparseScsrgeam2_bufferSizeExt`|3.5.0| | | | |
|`cusparseScsrgemm`| |10.2| |11.0|`hipsparseScsrgemm`|2.8.0|3.9.0| | | |
|`cusparseScsrgemm2`| |11.0| |12.0|`hipsparseScsrgemm2`|2.8.0|3.9.0| | | |
|`cusparseScsrgemm2_bufferSizeExt`| |11.0| |12.0|`hipsparseScsrgemm2_bufferSizeExt`|2.8.0|3.9.0| | | |
|`cusparseXcsrgeam2Nnz`|10.0| | | |`hipsparseXcsrgeam2Nnz`|3.5.0| | | | |
|`cusparseXcsrgeamNnz`| |10.2| |11.0|`hipsparseXcsrgeamNnz`|3.5.0|3.9.0| | | |
|`cusparseXcsrgemm2Nnz`| |11.0| |12.0|`hipsparseXcsrgemm2Nnz`|2.8.0|3.9.0| | | |
|`cusparseXcsrgemmNnz`| |10.2| |11.0|`hipsparseXcsrgemmNnz`|2.8.0|3.9.0| | | |
|`cusparseZcsrgeam`| |10.2| |11.0|`hipsparseZcsrgeam`|3.5.0|3.9.0| | | |
|`cusparseZcsrgeam2`|10.0| | | |`hipsparseZcsrgeam2`|3.5.0| | | | |
|`cusparseZcsrgeam2_bufferSizeExt`|10.0| | | |`hipsparseZcsrgeam2_bufferSizeExt`|3.5.0| | | | |
|`cusparseZcsrgemm`| |10.2| |11.0|`hipsparseZcsrgemm`|3.1.0|3.9.0| | | |
|`cusparseZcsrgemm2`| |11.0| |12.0|`hipsparseZcsrgemm2`|3.1.0|3.9.0| | | |
|`cusparseZcsrgemm2_bufferSizeExt`| |11.0| |12.0|`hipsparseZcsrgemm2_bufferSizeExt`|3.1.0|3.9.0| | | |

## **12. CUSPARSE Preconditioners Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCbsric02`| |12.2| | |`hipsparseCbsric02`|3.8.0|6.2.0| | | |
|`cusparseCbsric02_analysis`| |12.2| | |`hipsparseCbsric02_analysis`|3.8.0|6.2.0| | | |
|`cusparseCbsric02_bufferSize`| |12.2| | |`hipsparseCbsric02_bufferSize`|3.8.0|6.2.0| | | |
|`cusparseCbsric02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseCbsrilu02`| |12.2| | |`hipsparseCbsrilu02`|3.9.0|6.2.0| | | |
|`cusparseCbsrilu02_analysis`| |12.2| | |`hipsparseCbsrilu02_analysis`|3.9.0|6.2.0| | | |
|`cusparseCbsrilu02_bufferSize`| |12.2| | |`hipsparseCbsrilu02_bufferSize`|3.9.0|6.2.0| | | |
|`cusparseCbsrilu02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseCbsrilu02_numericBoost`| |12.2| | |`hipsparseCbsrilu02_numericBoost`|3.9.0|6.2.0| | | |
|`cusparseCcsric0`| |10.2| |11.0| | | | | | |
|`cusparseCcsric02`| |12.2| | |`hipsparseCcsric02`|3.1.0|6.2.0| | | |
|`cusparseCcsric02_analysis`| |12.2| | |`hipsparseCcsric02_analysis`|3.1.0|6.2.0| | | |
|`cusparseCcsric02_bufferSize`| |12.2| | |`hipsparseCcsric02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseCcsric02_bufferSizeExt`| |12.2| | |`hipsparseCcsric02_bufferSizeExt`|3.1.0| | | | |
|`cusparseCcsrilu0`| |10.2| |11.0| | | | | | |
|`cusparseCcsrilu02`| |12.2| | |`hipsparseCcsrilu02`|3.1.0|6.2.0| | | |
|`cusparseCcsrilu02_analysis`| |12.2| | |`hipsparseCcsrilu02_analysis`|3.1.0|6.2.0| | | |
|`cusparseCcsrilu02_bufferSize`| |12.2| | |`hipsparseCcsrilu02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseCcsrilu02_bufferSizeExt`| |12.2| | |`hipsparseCcsrilu02_bufferSizeExt`|3.1.0| | | | |
|`cusparseCcsrilu02_numericBoost`| |12.2| | |`hipsparseCcsrilu02_numericBoost`|3.10.0|6.2.0| | | |
|`cusparseCgpsvInterleavedBatch`|9.2| | | |`hipsparseCgpsvInterleavedBatch`|5.1.0| | | | |
|`cusparseCgpsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseCgpsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseCgtsv`| |10.2| |11.0| | | | | | |
|`cusparseCgtsv2`|9.0| | | |`hipsparseCgtsv2`|4.3.0| | | | |
|`cusparseCgtsv2StridedBatch`|9.0| | | |`hipsparseCgtsv2StridedBatch`|4.5.0| | | | |
|`cusparseCgtsv2StridedBatch_bufferSizeExt`|9.0| | | |`hipsparseCgtsv2StridedBatch_bufferSizeExt`|4.5.0| | | | |
|`cusparseCgtsv2_bufferSizeExt`|9.0| | | |`hipsparseCgtsv2_bufferSizeExt`|4.3.0| | | | |
|`cusparseCgtsv2_nopivot`|9.0| | | |`hipsparseCgtsv2_nopivot`|4.3.0| | | | |
|`cusparseCgtsv2_nopivot_bufferSizeExt`|9.0| | | |`hipsparseCgtsv2_nopivot_bufferSizeExt`|4.3.0| | | | |
|`cusparseCgtsvInterleavedBatch`|9.2| | | |`hipsparseCgtsvInterleavedBatch`|5.1.0| | | | |
|`cusparseCgtsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseCgtsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseCgtsvStridedBatch`| |10.2| |11.0| | | | | | |
|`cusparseCgtsv_nopivot`| |10.2| |11.0| | | | | | |
|`cusparseCsrilu0Ex`|8.0|10.2| |11.0| | | | | | |
|`cusparseDbsric02`| |12.2| | |`hipsparseDbsric02`|3.8.0|6.2.0| | | |
|`cusparseDbsric02_analysis`| |12.2| | |`hipsparseDbsric02_analysis`|3.8.0|6.2.0| | | |
|`cusparseDbsric02_bufferSize`| |12.2| | |`hipsparseDbsric02_bufferSize`|3.8.0|6.2.0| | | |
|`cusparseDbsric02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseDbsrilu02`| |12.2| | |`hipsparseDbsrilu02`|3.9.0|6.2.0| | | |
|`cusparseDbsrilu02_analysis`| |12.2| | |`hipsparseDbsrilu02_analysis`|3.9.0|6.2.0| | | |
|`cusparseDbsrilu02_bufferSize`| |12.2| | |`hipsparseDbsrilu02_bufferSize`|3.9.0|6.2.0| | | |
|`cusparseDbsrilu02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseDbsrilu02_numericBoost`| |12.2| | |`hipsparseDbsrilu02_numericBoost`|3.9.0|6.2.0| | | |
|`cusparseDcsric0`| |10.2| |11.0| | | | | | |
|`cusparseDcsric02`| |12.2| | |`hipsparseDcsric02`|3.1.0|6.2.0| | | |
|`cusparseDcsric02_analysis`| |12.2| | |`hipsparseDcsric02_analysis`|3.1.0|6.2.0| | | |
|`cusparseDcsric02_bufferSize`| |12.2| | |`hipsparseDcsric02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseDcsric02_bufferSizeExt`| |12.2| | |`hipsparseDcsric02_bufferSizeExt`|3.1.0| | | | |
|`cusparseDcsrilu0`| |10.2| |11.0| | | | | | |
|`cusparseDcsrilu02`| |12.2| | |`hipsparseDcsrilu02`|1.9.2|6.2.0| | | |
|`cusparseDcsrilu02_analysis`| |12.2| | |`hipsparseDcsrilu02_analysis`|1.9.2|6.2.0| | | |
|`cusparseDcsrilu02_bufferSize`| |12.2| | |`hipsparseDcsrilu02_bufferSize`|1.9.2|6.2.0| | | |
|`cusparseDcsrilu02_bufferSizeExt`| |12.2| | |`hipsparseDcsrilu02_bufferSizeExt`|1.9.2| | | | |
|`cusparseDcsrilu02_numericBoost`| |12.2| | |`hipsparseDcsrilu02_numericBoost`|3.10.0|6.2.0| | | |
|`cusparseDgpsvInterleavedBatch`|9.2| | | |`hipsparseDgpsvInterleavedBatch`|5.1.0| | | | |
|`cusparseDgpsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseDgpsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseDgtsv`| |10.2| |11.0| | | | | | |
|`cusparseDgtsv2`|9.0| | | |`hipsparseDgtsv2`|4.3.0| | | | |
|`cusparseDgtsv2StridedBatch`|9.0| | | |`hipsparseDgtsv2StridedBatch`|4.5.0| | | | |
|`cusparseDgtsv2StridedBatch_bufferSizeExt`|9.0| | | |`hipsparseDgtsv2StridedBatch_bufferSizeExt`|4.5.0| | | | |
|`cusparseDgtsv2_bufferSizeExt`|9.0| | | |`hipsparseDgtsv2_bufferSizeExt`|4.3.0| | | | |
|`cusparseDgtsv2_nopivot`|9.0| | | |`hipsparseDgtsv2_nopivot`|4.3.0| | | | |
|`cusparseDgtsv2_nopivot_bufferSizeExt`|9.0| | | |`hipsparseDgtsv2_nopivot_bufferSizeExt`|4.3.0| | | | |
|`cusparseDgtsvInterleavedBatch`|9.2| | | |`hipsparseDgtsvInterleavedBatch`|5.1.0| | | | |
|`cusparseDgtsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseDgtsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseDgtsvStridedBatch`| |10.2| |11.0| | | | | | |
|`cusparseDgtsv_nopivot`| |10.2| |11.0| | | | | | |
|`cusparseSbsric02`| |12.2| | |`hipsparseSbsric02`|3.8.0|6.2.0| | | |
|`cusparseSbsric02_analysis`| |12.2| | |`hipsparseSbsric02_analysis`|3.8.0|6.2.0| | | |
|`cusparseSbsric02_bufferSize`| |12.2| | |`hipsparseSbsric02_bufferSize`|3.8.0|6.2.0| | | |
|`cusparseSbsric02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseSbsrilu02`| |12.2| | |`hipsparseSbsrilu02`|3.9.0|6.2.0| | | |
|`cusparseSbsrilu02_analysis`| |12.2| | |`hipsparseSbsrilu02_analysis`|3.9.0|6.2.0| | | |
|`cusparseSbsrilu02_bufferSize`| |12.2| | |`hipsparseSbsrilu02_bufferSize`|3.9.0|6.2.0| | | |
|`cusparseSbsrilu02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseSbsrilu02_numericBoost`| |12.2| | |`hipsparseSbsrilu02_numericBoost`|3.9.0|6.2.0| | | |
|`cusparseScsric0`| |10.2| |11.0| | | | | | |
|`cusparseScsric02`| |12.2| | |`hipsparseScsric02`|3.1.0|6.2.0| | | |
|`cusparseScsric02_analysis`| |12.2| | |`hipsparseScsric02_analysis`|3.1.0|6.2.0| | | |
|`cusparseScsric02_bufferSize`| |12.2| | |`hipsparseScsric02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseScsric02_bufferSizeExt`| |12.2| | |`hipsparseScsric02_bufferSizeExt`|3.1.0| | | | |
|`cusparseScsrilu0`| |10.2| |11.0| | | | | | |
|`cusparseScsrilu02`| |12.2| | |`hipsparseScsrilu02`|1.9.2|6.2.0| | | |
|`cusparseScsrilu02_analysis`| |12.2| | |`hipsparseScsrilu02_analysis`|1.9.2|6.2.0| | | |
|`cusparseScsrilu02_bufferSize`| |12.2| | |`hipsparseScsrilu02_bufferSize`|1.9.2|6.2.0| | | |
|`cusparseScsrilu02_bufferSizeExt`| |12.2| | |`hipsparseScsrilu02_bufferSizeExt`|1.9.2| | | | |
|`cusparseScsrilu02_numericBoost`| |12.2| | |`hipsparseScsrilu02_numericBoost`|3.10.0|6.2.0| | | |
|`cusparseSgpsvInterleavedBatch`|9.2| | | |`hipsparseSgpsvInterleavedBatch`|5.1.0| | | | |
|`cusparseSgpsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseSgpsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseSgtsv`| |10.2| |11.0| | | | | | |
|`cusparseSgtsv2`|9.0| | | |`hipsparseSgtsv2`|4.3.0| | | | |
|`cusparseSgtsv2StridedBatch`|9.0| | | |`hipsparseSgtsv2StridedBatch`|4.5.0| | | | |
|`cusparseSgtsv2StridedBatch_bufferSizeExt`|9.0| | | |`hipsparseSgtsv2StridedBatch_bufferSizeExt`|4.5.0| | | | |
|`cusparseSgtsv2_bufferSizeExt`|9.0| | | |`hipsparseSgtsv2_bufferSizeExt`|4.3.0| | | | |
|`cusparseSgtsv2_nopivot`|9.0| | | |`hipsparseSgtsv2_nopivot`|4.3.0| | | | |
|`cusparseSgtsv2_nopivot_bufferSizeExt`|9.0| | | |`hipsparseSgtsv2_nopivot_bufferSizeExt`|4.3.0| | | | |
|`cusparseSgtsvInterleavedBatch`|9.2| | | |`hipsparseSgtsvInterleavedBatch`|5.1.0| | | | |
|`cusparseSgtsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseSgtsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseSgtsvStridedBatch`| |10.2| |11.0| | | | | | |
|`cusparseSgtsv_nopivot`| |10.2| |11.0| | | | | | |
|`cusparseXbsric02_zeroPivot`| |12.2| | |`hipsparseXbsric02_zeroPivot`|3.8.0|6.2.0| | | |
|`cusparseXbsrilu02_zeroPivot`| |12.2| | |`hipsparseXbsrilu02_zeroPivot`|3.9.0|6.2.0| | | |
|`cusparseXcsric02_zeroPivot`| |12.2| | |`hipsparseXcsric02_zeroPivot`|3.1.0|6.2.0| | | |
|`cusparseXcsrilu02_zeroPivot`| |12.2| | |`hipsparseXcsrilu02_zeroPivot`|1.9.2|6.2.0| | | |
|`cusparseZbsric02`| |12.2| | |`hipsparseZbsric02`|3.8.0|6.2.0| | | |
|`cusparseZbsric02_analysis`| |12.2| | |`hipsparseZbsric02_analysis`|3.8.0|6.2.0| | | |
|`cusparseZbsric02_bufferSize`| |12.2| | |`hipsparseZbsric02_bufferSize`|3.8.0|6.2.0| | | |
|`cusparseZbsric02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseZbsrilu02`| |12.2| | |`hipsparseZbsrilu02`|3.9.0|6.2.0| | | |
|`cusparseZbsrilu02_analysis`| |12.2| | |`hipsparseZbsrilu02_analysis`|3.9.0|6.2.0| | | |
|`cusparseZbsrilu02_bufferSize`| |12.2| | |`hipsparseZbsrilu02_bufferSize`|3.9.0|6.2.0| | | |
|`cusparseZbsrilu02_bufferSizeExt`| |12.2| | | | | | | | |
|`cusparseZbsrilu02_numericBoost`| |12.2| | |`hipsparseZbsrilu02_numericBoost`|3.9.0|6.2.0| | | |
|`cusparseZcsric0`| |10.2| |11.0| | | | | | |
|`cusparseZcsric02`| |12.2| | |`hipsparseZcsric02`|3.1.0|6.2.0| | | |
|`cusparseZcsric02_analysis`| |12.2| | |`hipsparseZcsric02_analysis`|3.1.0|6.2.0| | | |
|`cusparseZcsric02_bufferSize`| |12.2| | |`hipsparseZcsric02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseZcsric02_bufferSizeExt`| |12.2| | |`hipsparseZcsric02_bufferSizeExt`|3.1.0| | | | |
|`cusparseZcsrilu0`| |10.2| |11.0| | | | | | |
|`cusparseZcsrilu02`| |12.2| | |`hipsparseZcsrilu02`|3.1.0|6.2.0| | | |
|`cusparseZcsrilu02_analysis`| |12.2| | |`hipsparseZcsrilu02_analysis`|3.1.0|6.2.0| | | |
|`cusparseZcsrilu02_bufferSize`| |12.2| | |`hipsparseZcsrilu02_bufferSize`|3.1.0|6.2.0| | | |
|`cusparseZcsrilu02_bufferSizeExt`| |12.2| | |`hipsparseZcsrilu02_bufferSizeExt`|3.1.0| | | | |
|`cusparseZcsrilu02_numericBoost`| |12.2| | |`hipsparseZcsrilu02_numericBoost`|3.10.0|6.2.0| | | |
|`cusparseZgpsvInterleavedBatch`|9.2| | | |`hipsparseZgpsvInterleavedBatch`|5.1.0| | | | |
|`cusparseZgpsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseZgpsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseZgtsv`| |10.2| |11.0| | | | | | |
|`cusparseZgtsv2`|9.0| | | |`hipsparseZgtsv2`|4.3.0| | | | |
|`cusparseZgtsv2StridedBatch`|9.0| | | |`hipsparseZgtsv2StridedBatch`|4.5.0| | | | |
|`cusparseZgtsv2StridedBatch_bufferSizeExt`|9.0| | | |`hipsparseZgtsv2StridedBatch_bufferSizeExt`|4.5.0| | | | |
|`cusparseZgtsv2_bufferSizeExt`|9.0| | | |`hipsparseZgtsv2_bufferSizeExt`|4.3.0| | | | |
|`cusparseZgtsv2_nopivot`|9.0| | | |`hipsparseZgtsv2_nopivot`|4.3.0| | | | |
|`cusparseZgtsv2_nopivot_bufferSizeExt`|9.0| | | |`hipsparseZgtsv2_nopivot_bufferSizeExt`|4.3.0| | | | |
|`cusparseZgtsvInterleavedBatch`|9.2| | | |`hipsparseZgtsvInterleavedBatch`|5.1.0| | | | |
|`cusparseZgtsvInterleavedBatch_bufferSizeExt`|9.2| | | |`hipsparseZgtsvInterleavedBatch_bufferSizeExt`|5.1.0| | | | |
|`cusparseZgtsvStridedBatch`| |10.2| |11.0| | | | | | |
|`cusparseZgtsv_nopivot`| |10.2| |11.0| | | | | | |

## **13. CUSPARSE Reorderings Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCcsrcolor`| |12.2| | |`hipsparseCcsrcolor`|4.5.0|6.2.0| | | |
|`cusparseDcsrcolor`| |12.2| | |`hipsparseDcsrcolor`|4.5.0|6.2.0| | | |
|`cusparseScsrcolor`| |12.2| | |`hipsparseScsrcolor`|4.5.0|6.2.0| | | |
|`cusparseZcsrcolor`| |12.2| | |`hipsparseZcsrcolor`|4.5.0|6.2.0| | | |

## **14. CUSPARSE Format Conversion Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseCbsr2csr`| | | | |`hipsparseCbsr2csr`|3.5.0| | | | |
|`cusparseCcsc2dense`| |11.1| |12.0|`hipsparseCcsc2dense`|3.5.0|5.6.0| | | |
|`cusparseCcsc2hyb`| |10.2| |11.0| | | | | | |
|`cusparseCcsr2bsr`| |12.4| | |`hipsparseCcsr2bsr`|3.5.0| | | | |
|`cusparseCcsr2csc`| |10.2| |11.0|`hipsparseCcsr2csc`|3.1.0|3.9.0| | | |
|`cusparseCcsr2csr_compress`|8.0|12.2| | |`hipsparseCcsr2csr_compress`|3.5.0| | | | |
|`cusparseCcsr2csru`| |12.2| | |`hipsparseCcsr2csru`|4.2.0|6.2.0| | | |
|`cusparseCcsr2dense`| |11.1| |12.0|`hipsparseCcsr2dense`|3.5.0|5.6.0| | | |
|`cusparseCcsr2gebsr`| | | | |`hipsparseCcsr2gebsr`|4.1.0| | | | |
|`cusparseCcsr2gebsr_bufferSize`| | | | |`hipsparseCcsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseCcsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseCcsr2hyb`| |10.2| |11.0|`hipsparseCcsr2hyb`|3.1.0|3.9.0| | | |
|`cusparseCcsru2csr`| |12.2| | |`hipsparseCcsru2csr`|4.2.0|6.2.0| | | |
|`cusparseCcsru2csr_bufferSizeExt`| |12.2| | |`hipsparseCcsru2csr_bufferSizeExt`|4.2.0|6.2.0| | | |
|`cusparseCdense2csc`| |11.1| |12.0|`hipsparseCdense2csc`|3.5.0|5.6.0| | | |
|`cusparseCdense2csr`| |11.1| |12.0|`hipsparseCdense2csr`|3.5.0| | | | |
|`cusparseCdense2hyb`| |10.2| |11.0| | | | | | |
|`cusparseCgebsr2csr`| |12.4| | |`hipsparseCgebsr2csr`|4.1.0| | | | |
|`cusparseCgebsr2gebsc`| | | | |`hipsparseCgebsr2gebsc`|4.1.0| | | | |
|`cusparseCgebsr2gebsc_bufferSize`| | | | |`hipsparseCgebsr2gebsc_bufferSize`|4.1.0| | | | |
|`cusparseCgebsr2gebsc_bufferSizeExt`| | | | | | | | | | |
|`cusparseCgebsr2gebsr`| | | | |`hipsparseCgebsr2gebsr`|4.1.0| | | | |
|`cusparseCgebsr2gebsr_bufferSize`| | | | |`hipsparseCgebsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseCgebsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseChyb2csc`| |10.2| |11.0| | | | | | |
|`cusparseChyb2csr`| |10.2| |11.0|`hipsparseChyb2csr`|3.1.0|3.9.0| | | |
|`cusparseChyb2dense`| |10.2| |11.0| | | | | | |
|`cusparseCnnz`| | | | |`hipsparseCnnz`|3.2.0| | | | |
|`cusparseCnnz_compress`|8.0|12.2| | |`hipsparseCnnz_compress`|3.5.0|6.2.0| | | |
|`cusparseCreateCsru2csrInfo`| |12.2| | |`hipsparseCreateCsru2csrInfo`|4.2.0| | | | |
|`cusparseCreateIdentityPermutation`| |12.2| | |`hipsparseCreateIdentityPermutation`|1.9.2|6.2.0| | | |
|`cusparseCsr2cscEx`|8.0|10.2| |11.0| | | | | | |
|`cusparseCsr2cscEx2`|10.1| | | |`hipsparseCsr2cscEx2`|5.4.0| | | | |
|`cusparseCsr2cscEx2_bufferSize`|10.1| | | |`hipsparseCsr2cscEx2_bufferSize`|5.4.0| | | | |
|`cusparseDbsr2csr`| | | | |`hipsparseDbsr2csr`|3.5.0| | | | |
|`cusparseDcsc2dense`| |11.1| |12.0|`hipsparseDcsc2dense`|3.5.0|5.6.0| | | |
|`cusparseDcsc2hyb`| |10.2| |11.0| | | | | | |
|`cusparseDcsr2bsr`| |12.4| | |`hipsparseDcsr2bsr`|3.5.0| | | | |
|`cusparseDcsr2csc`| |10.2| |11.0|`hipsparseDcsr2csc`|1.9.2|3.9.0| | | |
|`cusparseDcsr2csr_compress`|8.0|12.2| | |`hipsparseDcsr2csr_compress`|3.5.0| | | | |
|`cusparseDcsr2csru`| |12.2| | |`hipsparseDcsr2csru`|4.2.0|6.2.0| | | |
|`cusparseDcsr2dense`| |11.1| |12.0|`hipsparseDcsr2dense`|3.5.0|5.6.0| | | |
|`cusparseDcsr2gebsr`| | | | |`hipsparseDcsr2gebsr`|4.1.0| | | | |
|`cusparseDcsr2gebsr_bufferSize`| | | | |`hipsparseDcsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseDcsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseDcsr2hyb`| |10.2| |11.0|`hipsparseDcsr2hyb`|1.9.2|3.9.0| | | |
|`cusparseDcsru2csr`| |12.2| | |`hipsparseDcsru2csr`|4.2.0|6.2.0| | | |
|`cusparseDcsru2csr_bufferSizeExt`| |12.2| | |`hipsparseDcsru2csr_bufferSizeExt`|4.2.0|6.2.0| | | |
|`cusparseDdense2csc`| |11.1| |12.0|`hipsparseDdense2csc`|3.5.0|5.6.0| | | |
|`cusparseDdense2csr`| |11.1| |12.0|`hipsparseDdense2csr`|3.5.0| | | | |
|`cusparseDdense2hyb`| |10.2| |11.0| | | | | | |
|`cusparseDestroyCsru2csrInfo`| |12.2| | |`hipsparseDestroyCsru2csrInfo`|4.2.0| | | | |
|`cusparseDgebsr2csr`| |12.4| | |`hipsparseDgebsr2csr`|4.1.0| | | | |
|`cusparseDgebsr2gebsc`| | | | |`hipsparseDgebsr2gebsc`|4.1.0| | | | |
|`cusparseDgebsr2gebsc_bufferSize`| | | | |`hipsparseDgebsr2gebsc_bufferSize`|4.1.0| | | | |
|`cusparseDgebsr2gebsc_bufferSizeExt`| | | | | | | | | | |
|`cusparseDgebsr2gebsr`| | | | |`hipsparseDgebsr2gebsr`|4.1.0| | | | |
|`cusparseDgebsr2gebsr_bufferSize`| | | | |`hipsparseDgebsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseDgebsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseDhyb2csc`| |10.2| |11.0| | | | | | |
|`cusparseDhyb2csr`| |10.2| |11.0|`hipsparseDhyb2csr`|3.1.0|3.9.0| | | |
|`cusparseDhyb2dense`| |10.2| |11.0| | | | | | |
|`cusparseDnnz`| | | | |`hipsparseDnnz`|3.2.0| | | | |
|`cusparseDnnz_compress`|8.0|12.2| | |`hipsparseDnnz_compress`|3.5.0|6.2.0| | | |
|`cusparseDpruneCsr2csr`|9.0|12.2| | |`hipsparseDpruneCsr2csr`|3.9.0|6.2.0| | | |
|`cusparseDpruneCsr2csrByPercentage`|9.0|12.2| | |`hipsparseDpruneCsr2csrByPercentage`|3.9.0|6.2.0| | | |
|`cusparseDpruneCsr2csrByPercentage_bufferSizeExt`|9.0|12.2| | |`hipsparseDpruneCsr2csrByPercentage_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseDpruneCsr2csrNnz`|9.0|12.2| | |`hipsparseDpruneCsr2csrNnz`|3.9.0|6.2.0| | | |
|`cusparseDpruneCsr2csrNnzByPercentage`|9.0|12.2| | |`hipsparseDpruneCsr2csrNnzByPercentage`|3.9.0|6.2.0| | | |
|`cusparseDpruneCsr2csr_bufferSizeExt`|9.0|12.2| | |`hipsparseDpruneCsr2csr_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csr`|9.0|12.2| | |`hipsparseDpruneDense2csr`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csrByPercentage`|9.0|12.2| | |`hipsparseDpruneDense2csrByPercentage`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csrByPercentage_bufferSizeExt`|9.0|12.2| | |`hipsparseDpruneDense2csrByPercentage_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csrNnz`|9.0|12.2| | |`hipsparseDpruneDense2csrNnz`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csrNnzByPercentage`|9.0|12.2| | |`hipsparseDpruneDense2csrNnzByPercentage`|3.9.0|6.2.0| | | |
|`cusparseDpruneDense2csr_bufferSizeExt`|9.0|12.2| | |`hipsparseDpruneDense2csr_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseHpruneCsr2csr`|9.0|12.2| | | | | | | | |
|`cusparseHpruneCsr2csrByPercentage`|9.0|12.2| | | | | | | | |
|`cusparseHpruneCsr2csrByPercentage_bufferSizeExt`|9.0|12.2| | | | | | | | |
|`cusparseHpruneCsr2csrNnz`|9.0|12.2| | | | | | | | |
|`cusparseHpruneCsr2csrNnzByPercentage`|9.0|12.2| | | | | | | | |
|`cusparseHpruneCsr2csr_bufferSizeExt`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csr`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csrByPercentage`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csrByPercentage_bufferSizeExt`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csrNnz`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csrNnzByPercentage`|9.0|12.2| | | | | | | | |
|`cusparseHpruneDense2csr_bufferSizeExt`|9.0|12.2| | | | | | | | |
|`cusparseSbsr2csr`| | | | |`hipsparseSbsr2csr`|3.5.0| | | | |
|`cusparseScsc2dense`| |11.1| |12.0|`hipsparseScsc2dense`|3.5.0|5.6.0| | | |
|`cusparseScsc2hyb`| |10.2| |11.0| | | | | | |
|`cusparseScsr2bsr`| |12.4| | |`hipsparseScsr2bsr`|3.5.0| | | | |
|`cusparseScsr2csc`| |10.2| |11.0|`hipsparseScsr2csc`|1.9.2|3.9.0| | | |
|`cusparseScsr2csr_compress`|8.0|12.2| | |`hipsparseScsr2csr_compress`|3.5.0| | | | |
|`cusparseScsr2csru`| |12.2| | |`hipsparseScsr2csru`|4.2.0|6.2.0| | | |
|`cusparseScsr2dense`| |11.1| |12.0|`hipsparseScsr2dense`|3.5.0|5.6.0| | | |
|`cusparseScsr2gebsr`| | | | |`hipsparseScsr2gebsr`|4.1.0| | | | |
|`cusparseScsr2gebsr_bufferSize`| | | | |`hipsparseScsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseScsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseScsr2hyb`| |10.2| |11.0|`hipsparseScsr2hyb`|1.9.2|3.9.0| | | |
|`cusparseScsru2csr`| |12.2| | |`hipsparseScsru2csr`|4.2.0|6.2.0| | | |
|`cusparseScsru2csr_bufferSizeExt`| |12.2| | |`hipsparseScsru2csr_bufferSizeExt`|4.2.0|6.2.0| | | |
|`cusparseSdense2csc`| |11.1| |12.0|`hipsparseSdense2csc`|3.5.0|5.6.0| | | |
|`cusparseSdense2csr`| |11.1| |12.0|`hipsparseSdense2csr`|3.5.0| | | | |
|`cusparseSdense2hyb`| |10.2| |11.0| | | | | | |
|`cusparseSgebsr2csr`| |12.4| | |`hipsparseSgebsr2csr`|4.1.0| | | | |
|`cusparseSgebsr2gebsc`| | | | |`hipsparseSgebsr2gebsc`|4.1.0| | | | |
|`cusparseSgebsr2gebsc_bufferSize`| | | | |`hipsparseSgebsr2gebsc_bufferSize`|4.1.0| | | | |
|`cusparseSgebsr2gebsc_bufferSizeExt`| | | | | | | | | | |
|`cusparseSgebsr2gebsr`| | | | |`hipsparseSgebsr2gebsr`|4.1.0| | | | |
|`cusparseSgebsr2gebsr_bufferSize`| | | | |`hipsparseSgebsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseSgebsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseShyb2csc`| |10.2| |11.0| | | | | | |
|`cusparseShyb2csr`| |10.2| |11.0|`hipsparseShyb2csr`|3.1.0|3.9.0| | | |
|`cusparseShyb2dense`| |10.2| |11.0| | | | | | |
|`cusparseSnnz`| | | | |`hipsparseSnnz`|3.2.0| | | | |
|`cusparseSnnz_compress`|8.0|12.2| | |`hipsparseSnnz_compress`|3.5.0|6.2.0| | | |
|`cusparseSpruneCsr2csr`|9.0|12.2| | |`hipsparseSpruneCsr2csr`|3.9.0|6.2.0| | | |
|`cusparseSpruneCsr2csrByPercentage`|9.0|12.2| | |`hipsparseSpruneCsr2csrByPercentage`|3.9.0|6.2.0| | | |
|`cusparseSpruneCsr2csrByPercentage_bufferSizeExt`|9.0|12.2| | |`hipsparseSpruneCsr2csrByPercentage_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseSpruneCsr2csrNnz`|9.0|12.2| | |`hipsparseSpruneCsr2csrNnz`|3.9.0|6.2.0| | | |
|`cusparseSpruneCsr2csrNnzByPercentage`|9.0|12.2| | |`hipsparseSpruneCsr2csrNnzByPercentage`|3.9.0|6.2.0| | | |
|`cusparseSpruneCsr2csr_bufferSizeExt`|9.0|12.2| | |`hipsparseSpruneCsr2csr_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csr`|9.0|12.2| | |`hipsparseSpruneDense2csr`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csrByPercentage`|9.0|12.2| | |`hipsparseSpruneDense2csrByPercentage`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csrByPercentage_bufferSizeExt`|9.0|12.2| | |`hipsparseSpruneDense2csrByPercentage_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csrNnz`|9.0|12.2| | |`hipsparseSpruneDense2csrNnz`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csrNnzByPercentage`|9.0|12.2| | |`hipsparseSpruneDense2csrNnzByPercentage`|3.9.0|6.2.0| | | |
|`cusparseSpruneDense2csr_bufferSizeExt`|9.0|12.2| | |`hipsparseSpruneDense2csr_bufferSizeExt`|3.9.0|6.2.0| | | |
|`cusparseXcoo2csr`| | | | |`hipsparseXcoo2csr`|1.9.2| | | | |
|`cusparseXcoosortByColumn`| | | | |`hipsparseXcoosortByColumn`|1.9.2| | | | |
|`cusparseXcoosortByRow`| | | | |`hipsparseXcoosortByRow`|1.9.2| | | | |
|`cusparseXcoosort_bufferSizeExt`| | | | |`hipsparseXcoosort_bufferSizeExt`|1.9.2| | | | |
|`cusparseXcscsort`| | | | |`hipsparseXcscsort`|2.10.0| | | | |
|`cusparseXcscsort_bufferSizeExt`| | | | |`hipsparseXcscsort_bufferSizeExt`|2.10.0| | | | |
|`cusparseXcsr2bsrNnz`| |12.4| | |`hipsparseXcsr2bsrNnz`|3.5.0| | | | |
|`cusparseXcsr2coo`| | | | |`hipsparseXcsr2coo`|1.9.2| | | | |
|`cusparseXcsr2gebsrNnz`| | | | |`hipsparseXcsr2gebsrNnz`|4.1.0| | | | |
|`cusparseXcsrsort`| | | | |`hipsparseXcsrsort`|1.9.2| | | | |
|`cusparseXcsrsort_bufferSizeExt`| | | | |`hipsparseXcsrsort_bufferSizeExt`|1.9.2| | | | |
|`cusparseXgebsr2csr`| |12.4| | | | | | | | |
|`cusparseXgebsr2gebsrNnz`| | | | |`hipsparseXgebsr2gebsrNnz`|4.1.0| | | | |
|`cusparseZbsr2csr`| | | | |`hipsparseZbsr2csr`|3.5.0| | | | |
|`cusparseZcsc2dense`| |11.1| |12.0|`hipsparseZcsc2dense`|3.5.0|5.6.0| | | |
|`cusparseZcsc2hyb`| |10.2| |11.0| | | | | | |
|`cusparseZcsr2bsr`| |12.4| | |`hipsparseZcsr2bsr`|3.5.0| | | | |
|`cusparseZcsr2csc`| |10.2| |11.0|`hipsparseZcsr2csc`|3.1.0|3.9.0| | | |
|`cusparseZcsr2csr_compress`|8.0|12.2| | |`hipsparseZcsr2csr_compress`|3.5.0| | | | |
|`cusparseZcsr2csru`| |12.2| | |`hipsparseZcsr2csru`|4.2.0|6.2.0| | | |
|`cusparseZcsr2dense`| |11.1| |12.0|`hipsparseZcsr2dense`|3.5.0|5.6.0| | | |
|`cusparseZcsr2gebsr`| | | | |`hipsparseZcsr2gebsr`|4.1.0| | | | |
|`cusparseZcsr2gebsr_bufferSize`| | | | |`hipsparseZcsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseZcsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseZcsr2hyb`| |10.2| |11.0|`hipsparseZcsr2hyb`|3.1.0|3.9.0| | | |
|`cusparseZcsru2csr`| |12.2| | |`hipsparseZcsru2csr`|4.2.0|6.2.0| | | |
|`cusparseZcsru2csr_bufferSizeExt`| |12.2| | |`hipsparseZcsru2csr_bufferSizeExt`|4.2.0|6.2.0| | | |
|`cusparseZdense2csc`| |11.1| |12.0|`hipsparseZdense2csc`|3.5.0|5.6.0| | | |
|`cusparseZdense2csr`| |11.1| |12.0|`hipsparseZdense2csr`|3.5.0| | | | |
|`cusparseZdense2hyb`| |10.2| |11.0| | | | | | |
|`cusparseZgebsr2csr`| |12.4| | |`hipsparseZgebsr2csr`|4.1.0| | | | |
|`cusparseZgebsr2gebsc`| | | | |`hipsparseZgebsr2gebsc`|4.1.0| | | | |
|`cusparseZgebsr2gebsc_bufferSize`| | | | |`hipsparseZgebsr2gebsc_bufferSize`|4.1.0| | | | |
|`cusparseZgebsr2gebsc_bufferSizeExt`| | | | | | | | | | |
|`cusparseZgebsr2gebsr`| | | | |`hipsparseZgebsr2gebsr`|4.1.0| | | | |
|`cusparseZgebsr2gebsr_bufferSize`| | | | |`hipsparseZgebsr2gebsr_bufferSize`|4.1.0| | | | |
|`cusparseZgebsr2gebsr_bufferSizeExt`| | | | | | | | | | |
|`cusparseZhyb2csc`| |10.2| |11.0| | | | | | |
|`cusparseZhyb2csr`| |10.2| |11.0|`hipsparseZhyb2csr`|3.1.0|3.9.0| | | |
|`cusparseZhyb2dense`| |10.2| |11.0| | | | | | |
|`cusparseZnnz`| | | | |`hipsparseZnnz`|3.2.0| | | | |
|`cusparseZnnz_compress`|8.0|12.2| | |`hipsparseZnnz_compress`|3.5.0|6.2.0| | | |

## **15. CUSPARSE Generic API Reference**

|**CUDA**|**A**|**D**|**C**|**R**|**HIP**|**A**|**D**|**C**|**R**|**E**|
|:--|:-:|:-:|:-:|:-:|:--|:-:|:-:|:-:|:-:|:-:|
|`cusparseAxpby`|11.0| |12.0| |`hipsparseAxpby`|4.1.0| |6.0.0| | |
|`cusparseBlockedEllGet`|11.2| | | |`hipsparseBlockedEllGet`|4.5.0| | | | |
|`cusparseBsrSetStridedBatch`|12.1| | | | | | | | | |
|`cusparseConstBlockedEllGet`|12.0| | | |`hipsparseConstBlockedEllGet`|6.0.0| | | | |
|`cusparseConstCooGet`|12.0| | | |`hipsparseConstCooGet`|6.0.0| | | | |
|`cusparseConstCscGet`|12.0| | | |`hipsparseConstCscGet`|6.2.0| | | | |
|`cusparseConstCsrGet`|12.0| | | |`hipsparseConstCsrGet`|6.0.0| | | | |
|`cusparseConstDnMatGet`|12.0| | | |`hipsparseConstDnMatGet`|6.0.0| | | | |
|`cusparseConstDnMatGetValues`|12.0| | | |`hipsparseConstDnMatGetValues`|6.0.0| | | | |
|`cusparseConstDnVecGet`|12.0| | | |`hipsparseConstDnVecGet`|6.0.0| | | | |
|`cusparseConstDnVecGetValues`|12.0| | | |`hipsparseConstDnVecGetValues`|6.0.0| | | | |
|`cusparseConstSpMatGetValues`|12.0| | | |`hipsparseConstSpMatGetValues`|6.0.0| | | | |
|`cusparseConstSpVecGet`|12.0| | | |`hipsparseConstSpVecGet`|6.0.0| | | | |
|`cusparseConstSpVecGetValues`|12.0| | | |`hipsparseConstSpVecGetValues`|6.0.0| | | | |
|`cusparseConstrainedGeMM`|10.2|11.2| |12.0| | | | | | |
|`cusparseConstrainedGeMM_bufferSize`|10.2|11.2| |12.0| | | | | | |
|`cusparseCooAoSGet`|10.2|11.2| |12.0|`hipsparseCooAoSGet`|4.1.0|5.6.0| | | |
|`cusparseCooGet`|10.1| | | |`hipsparseCooGet`|4.1.0| | | | |
|`cusparseCooSetPointers`|11.1| | | |`hipsparseCooSetPointers`|4.2.0| | | | |
|`cusparseCooSetStridedBatch`|11.0| | | |`hipsparseCooSetStridedBatch`|5.2.0| | | | |
|`cusparseCreateBlockedEll`|11.2| | | |`hipsparseCreateBlockedEll`|4.5.0| | | | |
|`cusparseCreateBsr`|12.1| | | | | | | | | |
|`cusparseCreateConstBlockedEll`|12.0| | | |`hipsparseCreateConstBlockedEll`|6.0.0| | | | |
|`cusparseCreateConstBsr`|12.1| | | | | | | | | |
|`cusparseCreateConstCoo`|12.0| | | |`hipsparseCreateConstCoo`|6.0.0| | | | |
|`cusparseCreateConstCsc`|12.0| | | |`hipsparseCreateConstCsc`|6.0.0| | | | |
|`cusparseCreateConstCsr`|12.0| | | |`hipsparseCreateConstCsr`|6.0.0| | | | |
|`cusparseCreateConstDnMat`|12.0| | | |`hipsparseCreateConstDnMat`|6.0.0| | | | |
|`cusparseCreateConstDnVec`|12.0| | | |`hipsparseCreateConstDnVec`|6.0.0| | | | |
|`cusparseCreateConstSlicedEll`|12.1| | | | | | | | | |
|`cusparseCreateConstSpVec`|12.0| | | |`hipsparseCreateConstSpVec`|6.0.0| | | | |
|`cusparseCreateCoo`|10.1| | | |`hipsparseCreateCoo`|4.1.0| | | | |
|`cusparseCreateCooAoS`|10.2|11.2| |12.0|`hipsparseCreateCooAoS`|4.1.0| | | | |
|`cusparseCreateCsc`|11.1| | | |`hipsparseCreateCsc`|4.2.0| | | | |
|`cusparseCreateCsr`|10.2| | | |`hipsparseCreateCsr`|4.1.0| | | | |
|`cusparseCreateDnMat`|10.1| | | |`hipsparseCreateDnMat`|4.2.0| | | | |
|`cusparseCreateDnVec`|10.2| | | |`hipsparseCreateDnVec`|4.1.0| | | | |
|`cusparseCreateSlicedEll`|12.1| | | | | | | | | |
|`cusparseCreateSpVec`|10.2| | | |`hipsparseCreateSpVec`|4.1.0| | | | |
|`cusparseCscGet`|11.7| | | |`hipsparseCscGet`|6.2.0| | | | |
|`cusparseCscSetPointers`|11.1| | | |`hipsparseCscSetPointers`|4.2.0| | | | |
|`cusparseCsrGet`|10.2| | | |`hipsparseCsrGet`|4.1.0| | | | |
|`cusparseCsrSetPointers`|11.0| | | |`hipsparseCsrSetPointers`|4.1.0| | | | |
|`cusparseCsrSetStridedBatch`|11.0| | | |`hipsparseCsrSetStridedBatch`|5.2.0| | | | |
|`cusparseDenseToSparse_analysis`|11.1| |12.0| |`hipsparseDenseToSparse_analysis`|4.2.0| |6.0.0| | |
|`cusparseDenseToSparse_bufferSize`|11.1| |12.0| |`hipsparseDenseToSparse_bufferSize`|4.2.0| |6.0.0| | |
|`cusparseDenseToSparse_convert`|11.1| |12.0| |`hipsparseDenseToSparse_convert`|4.2.0| |6.0.0| | |
|`cusparseDestroyDnMat`|10.1| |12.0| |`hipsparseDestroyDnMat`|4.2.0| |6.0.0| | |
|`cusparseDestroyDnVec`|10.2| |12.0| |`hipsparseDestroyDnVec`|4.1.0| |6.0.0| | |
|`cusparseDestroySpMat`|10.1| |12.0| |`hipsparseDestroySpMat`|4.1.0| |6.0.0| | |
|`cusparseDestroySpVec`|10.2| |12.0| |`hipsparseDestroySpVec`|4.1.0| |6.0.0| | |
|`cusparseDnMatGet`|10.1| | | |`hipsparseDnMatGet`|4.2.0| | | | |
|`cusparseDnMatGetStridedBatch`|10.1| |12.0| |`hipsparseDnMatGetStridedBatch`|5.2.0| |6.0.0| | |
|`cusparseDnMatGetValues`|10.2| | | |`hipsparseDnMatGetValues`|4.2.0| | | | |
|`cusparseDnMatSetStridedBatch`|10.1| | | |`hipsparseDnMatSetStridedBatch`|5.2.0| | | | |
|`cusparseDnMatSetValues`|10.2| | | |`hipsparseDnMatSetValues`|4.2.0| | | | |
|`cusparseDnVecGet`|10.2| | | |`hipsparseDnVecGet`|4.1.0| | | | |
|`cusparseDnVecGetValues`|10.2| | | |`hipsparseDnVecGetValues`|4.1.0| | | | |
|`cusparseDnVecSetValues`|10.2| | | |`hipsparseDnVecSetValues`|4.1.0| | | | |
|`cusparseGather`|11.0| |12.0| |`hipsparseGather`|4.1.0| |6.0.0| | |
|`cusparseRot`|11.0|12.2| | |`hipsparseRot`|4.1.0|6.2.0| | | |
|`cusparseSDDMM`|11.2| |12.0| |`hipsparseSDDMM`|4.3.0| |6.0.0| | |
|`cusparseSDDMM_bufferSize`|11.2| |12.0| |`hipsparseSDDMM_bufferSize`|4.3.0| |6.0.0| | |
|`cusparseSDDMM_preprocess`|11.2| |12.0| |`hipsparseSDDMM_preprocess`|4.3.0| |6.0.0| | |
|`cusparseScatter`|11.0| |12.0| |`hipsparseScatter`|4.1.0| |6.0.0| | |
|`cusparseSpGEMM_compute`|11.0| |12.0| |`hipsparseSpGEMM_compute`|4.1.0| |6.0.0| | |
|`cusparseSpGEMM_copy`|11.0| |12.0| |`hipsparseSpGEMM_copy`|4.1.0| |6.0.0| | |
|`cusparseSpGEMM_createDescr`|11.0| | | |`hipsparseSpGEMM_createDescr`|4.1.0| | | | |
|`cusparseSpGEMM_destroyDescr`|11.0| | | |`hipsparseSpGEMM_destroyDescr`|4.1.0| | | | |
|`cusparseSpGEMM_estimateMemory`|12.0| | | | | | | | | |
|`cusparseSpGEMM_getNumProducts`|12.0| | | | | | | | | |
|`cusparseSpGEMM_workEstimation`|11.0| |12.0| |`hipsparseSpGEMM_workEstimation`|4.1.0| |6.0.0| | |
|`cusparseSpGEMMreuse_compute`|11.3| |12.0| |`hipsparseSpGEMMreuse_compute`|5.1.0| |6.0.0| | |
|`cusparseSpGEMMreuse_copy`|11.3| |12.0| |`hipsparseSpGEMMreuse_copy`|5.1.0| |6.0.0| | |
|`cusparseSpGEMMreuse_nnz`|11.3| |12.0| |`hipsparseSpGEMMreuse_nnz`|5.1.0| |6.0.0| | |
|`cusparseSpGEMMreuse_workEstimation`|11.3| |12.0| |`hipsparseSpGEMMreuse_workEstimation`|5.1.0| |6.0.0| | |
|`cusparseSpMM`|10.1| |12.0| |`hipsparseSpMM`|4.2.0| |6.0.0| | |
|`cusparseSpMMOp`|11.5| | | | | | | | | |
|`cusparseSpMMOp_createPlan`|11.5| | | | | | | | | |
|`cusparseSpMMOp_destroyPlan`|11.5| | | | | | | | | |
|`cusparseSpMM_bufferSize`|10.1| |12.0| |`hipsparseSpMM_bufferSize`|4.2.0| |6.0.0| | |
|`cusparseSpMM_preprocess`|11.2| |12.0| |`hipsparseSpMM_preprocess`|4.5.0| |6.0.0| | |
|`cusparseSpMV`|10.1| |12.0| |`hipsparseSpMV`|4.1.0| |6.0.0| | |
|`cusparseSpMV_bufferSize`|10.1| |12.0| |`hipsparseSpMV_bufferSize`|4.1.0| |6.0.0| | |
|`cusparseSpMV_preprocess`|12.4| | | |`hipsparseSpMV_preprocess`|5.2.0| |6.0.0| | |
|`cusparseSpMatGetAttribute`|11.3| |12.0| |`hipsparseSpMatGetAttribute`|4.5.0| |6.0.0| | |
|`cusparseSpMatGetFormat`|10.1| |12.0| |`hipsparseSpMatGetFormat`|4.1.0| |6.0.0| | |
|`cusparseSpMatGetIndexBase`|10.1| |12.0| |`hipsparseSpMatGetIndexBase`|4.1.0| |6.0.0| | |
|`cusparseSpMatGetNumBatches`|10.1| | |10.2| | | | | | |
|`cusparseSpMatGetSize`|11.0| |12.0| |`hipsparseSpMatGetSize`|4.1.0| |6.0.0| | |
|`cusparseSpMatGetStridedBatch`|10.2| |12.0| |`hipsparseSpMatGetStridedBatch`|5.2.0| |6.0.0| | |
|`cusparseSpMatGetValues`|10.2| | | |`hipsparseSpMatGetValues`|4.1.0| | | | |
|`cusparseSpMatSetAttribute`|11.3| | | |`hipsparseSpMatSetAttribute`|4.5.0| | | | |
|`cusparseSpMatSetNumBatches`|10.1| | |10.2| | | | | | |
|`cusparseSpMatSetStridedBatch`|10.2| | |12.0|`hipsparseSpMatSetStridedBatch`|5.2.0|5.2.0| | | |
|`cusparseSpMatSetValues`|10.2| | | |`hipsparseSpMatSetValues`|4.1.0| | | | |
|`cusparseSpSM_analysis`|11.3| |12.0| |`hipsparseSpSM_analysis`|4.5.0| |6.0.0| | |
|`cusparseSpSM_bufferSize`|11.3| |12.0| |`hipsparseSpSM_bufferSize`|4.5.0| |6.0.0| | |
|`cusparseSpSM_createDescr`|11.3| | | |`hipsparseSpSM_createDescr`|4.5.0| | | | |
|`cusparseSpSM_destroyDescr`|11.3| | | |`hipsparseSpSM_destroyDescr`|4.5.0| | | | |
|`cusparseSpSM_solve`|11.3| |12.0| |`hipsparseSpSM_solve`|4.5.0| |6.0.0| | |
|`cusparseSpSM_updateMatrix`|12.4| | | | | | | | | |
|`cusparseSpSV_analysis`|11.3| |12.0| |`hipsparseSpSV_analysis`|4.5.0| |6.0.0| | |
|`cusparseSpSV_bufferSize`|11.3| |12.0| |`hipsparseSpSV_bufferSize`|4.5.0| |6.0.0| | |
|`cusparseSpSV_createDescr`|11.3| | | |`hipsparseSpSV_createDescr`|4.5.0| | | | |
|`cusparseSpSV_destroyDescr`|11.3| | | |`hipsparseSpSV_destroyDescr`|4.5.0| | | | |
|`cusparseSpSV_solve`|11.3| |12.0| |`hipsparseSpSV_solve`|4.5.0| |6.0.0| | |
|`cusparseSpSV_updateMatrix`|12.1| | | | | | | | | |
|`cusparseSpVV`|10.1| |12.0| |`hipsparseSpVV`|4.1.0| |6.0.0| | |
|`cusparseSpVV_bufferSize`|10.1| |12.0| |`hipsparseSpVV_bufferSize`|4.1.0| |6.0.0| | |
|`cusparseSpVecGet`|10.2| | | |`hipsparseSpVecGet`|4.1.0| | | | |
|`cusparseSpVecGetIndexBase`|10.2| |12.0| |`hipsparseSpVecGetIndexBase`|4.1.0| |6.0.0| | |
|`cusparseSpVecGetValues`|10.2| | | |`hipsparseSpVecGetValues`|4.1.0| | | | |
|`cusparseSpVecSetValues`|10.2| | | |`hipsparseSpVecSetValues`|4.1.0| | | | |
|`cusparseSparseToDense`|11.1| |12.0| |`hipsparseSparseToDense`|4.2.0| |6.0.0| | |
|`cusparseSparseToDense_bufferSize`|11.1| |12.0| |`hipsparseSparseToDense_bufferSize`|4.2.0| |6.0.0| | |


\*A - Added; D - Deprecated; C - Changed; R - Removed; E - Experimental