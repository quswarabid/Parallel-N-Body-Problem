### Running the code

To run the Serial version:

```sh
$ g++ -o nbody_serial n_body.cpp
$ ./nbody_serial
```

To run the openMP version:

Pre-requisites:
CUDA, openMP and openGL libraries should be present

```sh
 g++ -o nbody_omp n_body_omp.cpp -fopenmp
$ ./nbody_omp
```

To run the CUDA version
```sh
$ nvcc -o nbody_cuda n_body_cuda.cu
$ ./nbody_cuda
```