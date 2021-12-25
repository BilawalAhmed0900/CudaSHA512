# CudaSHA512
Implementation of SHA512 using CUDA.
Inspiration from https://github.com/Horkyze/CudaSHA256.

# Note
Do the following before first use

    checkCudaErrors(cudaMemcpyToSymbol(sha512_dev_k, sha512_host_k, sizeof(sha512_host_k), 0, cudaMemcpyHostToDevice));
