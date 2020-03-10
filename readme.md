# Webpack Assets Manifest

## The Fork specificity

This fork was made to improve performance for incremental builds during webpack watching. It allows you to stop webpack-assets-manifest working on a rebuild. For this functionality to work, it is necessary to activate the `isWatchMode` and ` skipOnIncrementialRebuilds` options.
