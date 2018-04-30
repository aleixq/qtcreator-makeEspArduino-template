# Parameters for compiling

#some things that you could use
#  SKETCH               Main source file
#                         If not specified the first sketch in current
#                         directory will be used. If none is found there,
#                         a demo example will be used instead.
#  LIBS                   Includes in the sketch file of libraries from within
#                         the ESP Arduino directories are automatically
#                         detected. If this is not enough, define this
#                         variable with all libraries or directories needed.
#  CUSTOM_LIBS            It is also possible to add other directories/file 
#                         to search by defining the variable CUSTOM_LIBS. 
#  EXCLUDE_DIRS         Can be setup to exclude one or several directories 
#                       from the wildcard LIBS and CUSTOM_LIBS search.
#  CHIP                 Set to esp8266 or esp32.
#  BOARD                Name of the target board.
#  FLASH_DEF            Flash partitioning info.
#  BUILD_DIR            Directory for intermediate build files.
#  BUILD_EXTRA_FLAGS    Additional parameters for the compilation commands
#  FS_DIR               File system root directory
#  UPLOAD_PORT          Serial flashing port name.
#  UPLOAD_SPEED         Serial flashing baud rate.
#  FLASH_FILE           File name for dump and restore flash operations
#  VERBOSE              Set to 1 to get full printout of the build
#  SINGLE_THREAD        Use only one build thread

#this is all I need at the moment
UPLOAD_PORT = %{PORT}
BOARD = %{BOARD}
ESP_ROOT = %{ESP_DIR}
SKETCH = %{SKETCH}

#ARDUINO_LIBS = $(HOME)/Arduino/libraries
#CUSTOM_LIBS = $(HOME)/Arduino/libraries/Time \
#    $(ARDUINO_LIBS)/Adafruit_GFX_Library \
#    $(ARDUINO_LIBS)/XPT2046-master \
#    $(ARDUINO_LIBS)/Adafruit_ILI9341esp \
#    $(ARDUINO_LIBS)/ArduinoJson-master/ArduinoJson-master/ArduinoJson.h
#EXCLUDE_DIRS = $(ARDUINO_LIBS)/ArduinoJson-master/third-party \
#    $(ARDUINO_LIBS)/ArduinoJson-master/test \
#    $(ARDUINO_LIBS)/Adafruit_GFX_Library/fontconvert


# makeEspArduino makefile
include %{MAKEESPARDUINO_DIR}/makeEspArduino.mk

