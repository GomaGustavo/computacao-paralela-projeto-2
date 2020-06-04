Projeto 2

`back.cpp`: Código do Perceptron Multicamada disponibilizado pelo professor
`back.cu`: Código do Perceptron Multicamada disponibilizado usando CUDA

Para executar:

```
# Compilar
nvcc -O3 back.cu -o back_cuda

# Analizar
nvprof --events warps_launched --metrics warp_execution_efficiency ./back_cuda
```