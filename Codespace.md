![Lab Banner](./.assets/images/banner-advanced-cpp-light.png#gh-light-mode-only)
![Lab Banner](./.assets/images/banner-advanced-cpp-dark.png#gh-dark-mode-only)

# Lab Instructions

## Manual build and run

1. Open an integrated terminal tab in VS Code.
1. Run "cmake -S . -B build -G Ninja" to generate the build configuration for Ninja.
1. Change directory to the *build* folder.
1. Run "ninja" to build the project.
1. Run "./CxxTemplate" to run the compiled application.

## VS Code Build Release (or Debug)

1. Open the command pallet: View > Command Palette or Shift-Ctrl/Cmd-P.
1. Type "Tasks: Run" and click on "Tasks: Run Task".
1. Select "Pipeline: Build Release Target" (or Build Debug Target).
1. In the integrated terminal window run "build/CxxTemplate".

## VS Code Build and Run

1. Click on the *Run and Debug* tool in the left *Activity Bar*.
1. Select *CxxTemplate: Run Program* from the configuration dropdown list at the top.
1. Click the run arrow to the left of the dropdown to build and run the program.

## VS Code Build and Debug

1. In the *Explorer Panel* open the *src/CxxTemplate.cpp* file.
1. Set a breakpoint on line 12: *std::cout << "Hello CMake." << std::endl;*
1. Click on the *Run and Debug* tool in the left *Activity Bar*.
1. Select *CxxTemplate: Debug Program* from the configuration dropdown list at the top.
1. Click the run arrow to the left of the dropdown to build and run the program.
1. The program stops at the first line in the *main* function.
    Use the *continue* button in the debug terminal to let the program continue.
1. Verify the programs stops at the breakpoint on line 12.
1. Continue execution to let the program finish running.

