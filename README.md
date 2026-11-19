Small Language Model on Emulated Raspberry Pi (ARM64)

How small can a language model get before it stops being useful, and what fits in the memory of a Raspberry Pi-sized device?

I trained a 70M-parameter English language model from scratch and ran it at several quantization levels with llama.cpp inside Raspberry Pi OS (64-bit) running under QEMU. This project measures quality, file size and memory use at Pi-sized RAM limits.

Important: I don't own a physical Raspberry Pi, so all timings come from an emulated ARM64 environment. Speed numbers in this repo are emulated and are only useful for comparing quantization levels with each other. They are not real Pi speeds.
