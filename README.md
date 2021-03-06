# A list of Go GUI/graphics/image related projects

### native GUI and utility bindings

[dlgs](https://github.com/gen2brain/dlgs) is a cross-platform library for displaying dialogs and input boxes.

[glfw](https://github.com/go-gl/glfw) is a Go bindings for GLFW 3.

[go-mobile](https://github.com/golang/mobile) adds support for mobile platforms (Android and iOS) and provides tools to build mobile applications. (A [Go bindings for OpenGL ES 2.0 and ES 3.0](https://godoc.org/golang.org/x/mobile/gl) is included.)

[go-sdl2](https://github.com/veandco/go-sdl2) is SDL2 wrapped for Go users.

[go-gtk](https://github.com/mattn/go-gtk) is a Go binding for GTK2.
* [RenderView](https://github.com/TheGrum/renderview) is an easy Go GUI wrapper for interactive manipulation of visual algorithms/backend code. Support go-gtk (default), gotk3 and shiny backends.

[gotk3](https://github.com/gotk3/gotk3) provides Go bindings for GTK+3 and dependent projects.

[GXUI](https://github.com/google/gxui) is a Go cross platform UI library.

[qt](https://github.com/therecipe/qt) allows you to write Qt applications entirely in Go and makes deploying them later very easy.

[shiny](https://github.com/golang/exp/tree/master/shiny) is a Go cross platform UI package.

[systray](https://github.com/getlantern/systray) is a cross platfrom Go library to place an icon and menu in the notification area. Tested on Windows 8, Mac OSX, Ubuntu 14.10 and Debian 7.6.

[trayhost](https://github.com/shurcooL/trayhost) is a cross-platform Go library to place an icon in the host operating system's taskbar.

[ui](https://github.com/andlabs/ui) aims to provide simple GUI software development in Go.

[Walk](https://github.com/lxn/walk) is a "Windows Application Library Kit" for the Go Programming Language.

[w32.go](https://gist.github.com/nathan-osman/18c2e227ad00a223b61c0b3c16d452c3) is a simple example on show to create Windows GUI by using the `syscall` pacakge.

[XGB](https://github.com/BurntSushi/xgb) is the X Go Binding, which is a low-level API to communicate with the
core X protocol and many of the X extensions.

[xgbutil](https://github.com/BurntSushi/xgbutil) is a utility library designed to work with the X Go Binding.

### HTML based GUI

[go-astilectron](https://github.com/asticode/go-astilectron) helps use build cross platform GUI apps with GO and HTML/JS/CSS. It is the official GO bindings of astilectron and is powered by Electron.

[go-sciter](https://github.com/sciter-sdk/go-sciter) is a Golang bindings of Sciter: the Embeddable HTML/CSS/script engine for modern UI development。

[gowd](https://github.com/dtylman/gowd) help us build cross platform GUI apps with GO and HTML/JS/CSS (powered by nwjs)。

[Gowut](https://github.com/icza/gowut) is a Web UI Toolkit written in pure Go. Apps are rendered as HTML pages. It doesn't bundle browsers.

[Lorca](https://github.com/zserge/lorca) is a very small library to build modern HTML5 desktop apps in Go. It doesn't bundle Chrome but reuses the installed Chrome on your machine.

[Muon](https://github.com/ImVexed/muon) is a lightweight alternative to Electron written in Golang

[Wails](https://github.com/wailsapp/wails) is a framework for building desktop applications using Go & Web Technologies.

[webview](https://github.com/zserge/webview) is a tiny cross-platform webview library for C/C++/Golang to build modern cross-platform GUIs.

### custom GUI

[duit](https://github.com/mjl-/duit) is a pure go, cross-platform, MIT-licensed ui toolkit for developers.

[Fyne](https://github.com/fyne-io/fyne) is an easy to use UI toolkit and app API written in Go. We use OpenGL (through the go-gl and go-glfw projects) to provide cross platform graphics.

[gi](https://github.com/goki/gi) is a scenegraph-based 2D and 3D GUI / graphics interface (Gi) in Go.

[Gio](https://git.sr.ht/~eliasnaur/gio) implements portable immediate mode GUI programs in Go. Gio programs run on all the major platforms: iOS/tvOS, Android, Linux (Wayland), macOS, Windows and browsers (Webassembly/WebGL).

[go-flutter](https://github.com/go-flutter-desktop/go-flutter) is a package that brings Flutter to the desktop.

[goey](https://bitbucket.org/rj/goey) provides a declarative, cross-platform GUI for the Go language. The range of controls, their supported properties and events, should roughly match what is available in HTML. However, properties and events may be limited to support portability. Additionally, styling of the controls will be limited, with the look of controls matching the native platform.

[gui](https://github.com/faiface/gui) provides super minimal, rock-solid foundation for concurrent GUI in Go.

[imgui-go](https://github.com/inkyblackness/imgui-go) is a Go wrapper for Dear ImGui.
* [giu](https://github.com/AllenDang/giu) is a GUI framework based on imgui-go. (Another similar one from the same auther, [gimu](https://github.com/AllenDang/gimu), but for nucular.)

[nk](https://github.com/golang-ui/nuklear) provides Go bindings for nuklear.h. 
* Another one: [nucular](https://github.com/aarzilli/nucular).

### 3D graphics and computing API bindings

[d3d9](https://github.com/gonutz/d3d9) is a pure Go wrapper for Microsoft's Direct3D9 API.

[gl](https://github.com/go-gl/gl) repository holds Go bindings to various OpenGL versions. They are auto-generated using Glow. 
* And [GLHF](https://github.com/faiface/glhf), a gl3.3 wrapper.
* And the above mentioned [OpenGL ES 2.0 and ES 3.0 bindings](https://godoc.org/golang.org/x/mobile/gl) from the go-mobile project.

[vulkan](https://github.com/vulkan-go/vulkan) provides Go bindings for Vulkan — a low-overhead, cross-platform 3D graphics and compute API.

### 2D vector graphics and computing APIs

[gg](https://github.com/fogleman/gg) is a library for rendering 2D graphics in pure Go.

[go-cairo](https://github.com/ungerik/go-cairo) is a Go binding for the cairo graphics library.

[go-skia](https://github.com/go101/go-skia) is a Go skia binding based on skia C library through cgo.

[svgo](https://github.com/ajstarks/svgo) generates SVG as defined by the Scalable Vector Graphics 1.1 Specification.

### font processing related

[freetype](https://github.com/golang/freetype) is a Freetype font rasterizer in the Go programming language.

[pixfont](https://github.com/pbnjay/pixfont) is a simple, lightweight Pixel Font (aka bitmap fonts) package for Go that works with the standard image/draw package

### game development related

[godot-go](https://github.com/ShadowApex/godot-go) - Go language bindings for the [Godot Engine](https://godotengine.org/)'s [GDNative API](https://github.com/GodotNativeTools/godot_headers).

Please visit [Awesome Go](https://github.com/avelino/awesome-go#game-development) for the list.

### image processing related

The standard Go [image](https://golang.org/pkg/image/) packages.

The [image](https://github.com/golang/image/) repository holds supplementary Go image libraries.

Please visit [Awesome Go](https://github.com/avelino/awesome-go#images) for more.

### terminal UI

BTW, if you have interests in developing terminal UI Go programs, please check
[tcell](https://github.com/gdamore/tcell), [tview](https://github.com/rivo/tview), [cview](https://gitlab.com/tslocum/cview/), and [more listed on Awesome Go](https://github.com/avelino/awesome-go#advanced-console-uis).

