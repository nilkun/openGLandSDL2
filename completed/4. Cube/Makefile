SOURCEFILES=main.cpp renderer.cpp buffer.cpp shader.cpp debug.cpp
TARGET_NAME=play
COMPILER=g++
COMPILER_FLAGS=-w

#LIBRARIES
LIBS=SDL2 GL GLEW SDL2_image

LIBRARIES=$(foreach library, $(LIBS), -l$(library))

all: $(SOURCEFILES)
	$(COMPILER) $(SOURCEFILES) $(COMPILER_FLAGS) $(LIBRARIES) -o $(TARGET_NAME)
