A minimal Docker image based on [bitnami/minideb](https://github.com/bitnami/minideb) for running OpenCL applications in [nvidia-docker](https://github.com/NVIDIA/nvidia-docker).

    docker run --runtime=nvidia --rm neurology/opencl clinfo