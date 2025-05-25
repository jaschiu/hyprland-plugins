all:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -shared -fPIC --no-gnu-unique main.cpp -o csgo-vulkan-fix.so `pkg-config --cflags pixman-1 libdrm hyprland pangocairo libinput libudev wayland-server xkbcommon` -std=c++2b
clean:
	rm ./csgo-vulkan-fix.so
