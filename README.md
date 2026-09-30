# TRACE Executable Code for Reproducibility
Regenerates every table and figure in the paper from the released TRACE benchmark, and measures the runtime figures reported in Section 3.6.

Upload TRACE_Dataset.zip, then Runtime > Run all. Sections 1–7 run in under a minute on CPU. Section 8 (runtime measurement) downloads a sentence encoder and takes roughly 10–15 minutes; it is optional but produces the latency numbers.

Outputs are written to figures/ and tables/.
