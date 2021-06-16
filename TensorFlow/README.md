# Tensor Flow Progress logs

## Work plan and goals
Main goal for now should be data-intensive surrogate model for confinement-time.
EFIT++ is already taken from data perspective by E.Lewis, and from GP perspective from J.Buchanan.
Disruption predictions is taken by K.Richards.
confinement-time seems free and relatively straight-forward, with possible experimental outcomes.

Progression in steps to get into TensorFlow:
1. Start with reduced 2D images. Use MAST fast camera images, reduced to small size, and clssify them as "full-view" or "half-view", and build network on that.
2. Try to predict a simple 1D signal from EFIT on MAST-U, based on engineering parameters. Don't care about the details, just learn how to process 1D data...
3. Start looking at confinement time.




