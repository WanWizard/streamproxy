bin_PROGRAMS = streamproxy

streamproxy_SOURCES = \
	acceptsocket.cpp \
	clientsocket.cpp \
	configmap.cpp \
	demuxer.cpp \
	enigma_settings.cpp \
	encoder-broadcom.cpp \
	filestreaming.cpp \
	filetranscoding-broadcom.cpp \
	livestreaming.cpp \
	livetranscoding-broadcom.cpp \
	mpegts.cpp \
	queue.cpp \
	service.cpp \
	stbtraits.cpp \
	streamproxy.cpp \
	time_offset.cpp \
	trap.cpp \
	transcoding-enigma.cpp \
	url.cpp \
	util.cpp \
	webifrequest.cpp \
	webrequest.cpp

streamproxy_CXXFLAGS = -Wall -Wextra -Wshadow -Wundef -Wformat=2 -Winit-self -Wunused -Werror -Wpointer-arith -Wcast-qual -Wmultichar
streamproxy_LDADD = -lpthread -lboost_program_options -lcrypt
