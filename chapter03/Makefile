all: enum_gpu hello_world 

enum_gpu: enum_gpu
	nvcc enum_gpu.cu -o enum_gpu

hello_world: hello_world.cu
	nvcc hello_world.cu -o hello_world

clean:
	rm -f enum_gpu hello_world
