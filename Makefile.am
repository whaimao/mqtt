AUTOMAKE_OPTIONS=foreign subdir-objects
noinst_LIBRARIES=libpaho_mqtt.a

libpaho_mqtt_a_SOURCES = \
src/Base64.c \
src/Log.c \
src/MQTTPacketOut.c \
src/MQTTProtocolClient.c \
src/OsWrapper.c \
src/SocketBuffer.c \
src/WebSocket.c \
src/Clients.c \
src/MQTTAsync.c \
src/MQTTPersistence.c \
src/MQTTProtocolOut.c \
src/SHA1.c \
src/StackTrace.c \
src/utf-8.c \
src/Heap.c \
src/MQTTClient.c \
src/MQTTPersistenceDefault.c \
src/MQTTReasonCodes.c \
src/SSLSocket.c \
src/Thread.c \
src/LinkedList.c \
src/MQTTPacket.c \
src/MQTTProperties.c \
src/Messages.c \
src/Socket.c \
src/Tree.c


AM_CPPFLAGS=-Isrc -Iinclude -I.

nobase_include_HEADERS = $(wildcard $(top_srcdir)/src/third/mqtt/include/*.h)

DEFS+=-DOPENSLL