# Microsoft adds 3D parallelism and ZeRO-Offload to DeepSpeed

- **Date:** 2020-09-14
- **Who:** Microsoft Research
- **Type:** software

In September 2020 Microsoft added four technologies to its open-source DeepSpeed training library. The additions included 3D parallelism, which combines ZeRO data parallelism, pipeline parallelism and tensor slicing, and ZeRO-Offload, which moves optimizer states and gradients to CPU memory. ZeRO-Offload let a single V100 GPU train models of up to about 13 billion parameters. It lowered the hardware barrier for training very large language models.

Note: the date is the date of the Synced report covering the release; the exact Microsoft announcement day was not confirmed.

## Sources
- https://syncedreview.com/2020/09/14/microsoft-democratizes-deepspeed-with-four-new-technologies/
