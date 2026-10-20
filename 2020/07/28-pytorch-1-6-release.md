# PyTorch 1.6 released with stable automatic mixed precision

- **Date:** 2020-07-28
- **Who:** Facebook AI / PyTorch team, with NVIDIA (AMP contribution) and Microsoft (Windows builds)
- **Type:** software

PyTorch 1.6 made automatic mixed precision (AMP) a stable feature through the torch.cuda.amp module, mixing float16 and float32 operations. The team claimed memory savings of up to 50% on Tensor Core GPUs. The release also added TensorPipe-based RPC, a tensor memory profiler, and a stable/beta/prototype feature classification, and Microsoft took over maintaining the Windows builds.

## Sources
- https://pytorch.org/blog/pytorch-1.6-released/
- https://devclass.com/2020/07/29/pytorch-1_6/
