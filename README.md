# jaeger-ctx

`jaeger-ctx` provides a small kernel module that creates a procfs entry at `/proc/lttng_jaeger` to allow other programs to write their Jaeger context information into the kernel. It can be built simply by running `make`. 

