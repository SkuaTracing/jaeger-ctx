# jaeger-ctx

`jaeger-ctx` provides a small kernel module that creates a procfs entry at `/proc/lttng_jaeger` to allow other programs to write their Jaeger context information into the kernel. 

## Installation
*Note: this requires a patched version of the Linux kernel. See [skua](https://github.com/docc-lab/skua) for details.*

It can be built simply by running `make`. To install the kernel module, run `sudo insmod jaeger_ctx.ko`. 
