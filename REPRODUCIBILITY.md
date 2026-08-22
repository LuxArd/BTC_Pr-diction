# Reproducibility notes

## Current status

The original course notebook is not reproducible from the public repository alone because its downloaded JSON inputs and generated finance CSV are absent.

This repository intentionally does not recreate or promote the original metrics until a clean, time-aware rerun is completed.

## A responsible rerun

1. Create a virtual environment and resolve exact package versions.
2. Retrieve permitted data and save it outside version control.
3. Build features using only information available at each historical point in time.
4. Split chronologically; never randomize the time order.
5. Validate with expanding-window or rolling-window evaluation.
6. Reserve the final holdout period until model selection is complete.
7. Report uncertainty, baseline comparisons, and errors in price units.

This repository does not operate a live prediction service, place trades, or distribute financial signals.

