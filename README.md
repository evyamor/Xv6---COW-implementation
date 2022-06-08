# Xv6---COW-implementation
the patch is according to a clean Xv6 cloned from gi. The memory model that was in practice copied every process image upon fork()
This patch will allow the Xv6 operating system to fullfill a COPY-ON-WRITE mechanism which increases memory usage efficiency. 
