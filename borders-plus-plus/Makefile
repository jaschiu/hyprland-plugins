all:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -shared -fPIC --no-gnu-unique main.cpp borderDeco.cpp BorderppPassElement.cpp -o borders-plus-plus.so `pkg-config --cflags pixman-1 libdrm hyprland pangocairo libinput libudev wayland-server xkbcommon` -std=c++2b
clean:
	rm ./borders-plus-plus.so
