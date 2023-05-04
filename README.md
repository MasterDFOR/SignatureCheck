# SignatureCheck
This code is written in C++ and designed to scan PE files in a given direcotry. It checks the signature of a PE file and returns whether it is signed or not. 
If a PE file is not signed, it generates a list of unsigned files on the Desktop and kills them. 
This code is tested with the CLion IDE, it may have errors if have it run within Visual Studio. 
Make sure that your CMakeList.txt contains target_link_libraries(untitled3 wintrust), which links the code to Wintrust library.
