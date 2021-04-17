project(MobileNetBench)

add_executable(mnet-32
  src/mobilenet_32.c)

add_executable(mnet-64
  src/mobilenet_64.c)

add_executable(mnet-128
  src/mobilenet_128.c)

add_executable(mnet-224
  src/mobilenet_224.c)
