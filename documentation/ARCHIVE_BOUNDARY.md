# Archive Boundary

This package contains the county-month derived analysis panel that matches the published Safety Science paper and the accompanying data-preparation documentation. The data are aggregate county-level crash/VMT/economic/control variables for Minnesota, not respondent-level human-subject records.

The source folder also contains `EconOfTranSafetyData.xls`, but it is not copied. It has the same visible sheet shape and headers as `MNcrashes.xls`, but differs in the `gasprice_adj` column. The mean adjusted gas price in `MNcrashes.xls` is approximately 1.515, matching the paper's reported average gasoline price used for elasticity calculations, so `MNcrashes.xls` is treated as the final aligned dataset.

Draft paper proposals and manuscript/review files are excluded.
