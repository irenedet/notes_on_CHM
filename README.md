# notes_on_CHM

## Home folder
```/scratch/trueba/CHM/chm-compiled-r2013a-2.1.367```

## 1. How to load:

```module load MCR/R2013a```

```export LD_LIBRARY_PATH=/g/easybuild/x86_64/CentOS/7/haswell/software/MCR/R2013a/v81/bin/glnxa64:/g/easybuild/x86_64/CentOS/7/haswell/software/MCR/R2013a/v81/sys/opengl/lib/glnxa64:/g/easybuild/x86_64/CentOS/7/haswell/software/MCR/R2013a/v81/sys/os/glnxa64:/g/easybuild/x86_64/CentOS/7/haswell/software/MCR/R2013a/v81/runtime/glnxa64```

```export PATH=/g/easybuild/x86_64/CentOS/7/haswell/software/MCR/R2013a/v81/bin:$PATH```

toy example:

```bash CHM_train.sh /scratch/trueba/yeast/mitochondria/raw /scratch/trueba/yeast/mitochondria/label```

Obs. All training images must have the same size
