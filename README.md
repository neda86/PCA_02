# PCA_02
The data for this question comes from https://github.com/vincentarelbundock/Rdatasets/blob/master/csv/datasets/ EuStockMarkets.csv which can be imported from R datasets directly as ’EuStockMarkets’. Each row is a day of market values.

- Fit a PCA model to the normalized dataset.

- Plot the transformed data on the 2 largest eigenvalues on a scatter plot.

- Plot the transformed data on a scatter plot where the color of the marker corresponds to the rownumber of the datapoint.

- Plot the projection along each PCA component on a separate ’radial’ (polar) plot. Make the labels on the circumfrence the months of the year. In Julia the basic plot can be achieved ’angles = row numbers .* (2pi / 365)’, ’plot( angles, component1projections, proj=:polar)’.
