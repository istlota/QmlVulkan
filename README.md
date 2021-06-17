# QmlVulkan
Qt Implementation of the Vulkan examples from the EXCELLENT Vulkan tutorial at THIS site:
 https://vulkan-tutorial.com/
 
There appears to be this widepsread belief, among OpenGL developers, that Qt's OpenGL support is useful ONLY to provide a OOP C++ alternative to GLFW's window.
 I disagree.
 
It is also widely believed, among OpenGL developers, that Vulkan is the future of OpenGL, especially for game development.
 That I DO agree with.

The code I upload in this repository is meant to demonstrate Qt's viability for Vulkan apps.
 To demonstrate Qt's unrivaled support for Vulkan, these projects will be Qt SUBDIRS projects which implement Vulkan-Tutorial's examples, each project containing three subprojects:
  1) Qt Console subproject which renders Vulkan scene with Vulkan SDK, presented in a C++ GLFW UI.
  2) Qt Widgets subproject, rendered with QVulkanWindowRenderer, and presented within a C++ QVulkanWindow UI.
  3) Qt Quick subproject, rendered with QQuickWindow's vulkanRhi renderer. and presented within a QML UI.
