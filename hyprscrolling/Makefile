all:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -shared -fPIC --no-gnu-unique main.cpp Scrolling.cpp -o hyprscrolling.so `pkg-config --cflags pixman-1 libdrm hyprland pangocairo libinput libudev wayland-server xkbcommon` -std=c++2b
clean:
	rm ./hyprscrolling.so
