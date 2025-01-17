# JUCE toys CMake configuration

# Add all the modules in this directory as JUCE modules
juce_add_module("${CMAKE_CURRENT_SOURCE_DIR}/jcf_advanced_leak_detector")
juce_add_module("${CMAKE_CURRENT_SOURCE_DIR}/jcf_debug")
# Add other modules here if needed
