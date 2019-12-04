project(UltraFluidModelerLibrary)

add_executable(UltraFluidModelerLibrary src/main.cpp src/DrawingContext.cpp
    src/DrawingElements.cpp src/ElementContainer.cpp src/Element.cpp
    src/ElementFactory.cpp src/ElementManager.cpp src/Modeler1.cpp
    src/Modeler1Doc.cpp src/Modeler1View.cpp src/stdafx.cpp)
