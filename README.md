# lf_benchmark_traces

## src/

This directory includes LF benchmark programs modified to stop within a short physical time, to reduce the output `.lft` file, so that it can be converted and loaded into the Chrome trace viewer.

## traces/

This directory includes the traces created from the modified LF benchmark programs.

### How to create files for Chrome trace viewer

JSON files for the Chrome trace viewer are too large, thus, not all of them is included in the repository.

To convert the `.lft` files into JSON files for the Chrome trace viewer, run

`trace_to_chrome [filename]` (No need to include `.lft` extension.)

And open the Chrome browser and type `chrome://tracing/` in the address bar.

Then open the JSON file created.
