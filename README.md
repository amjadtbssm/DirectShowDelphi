# DSPack 2.3.3 (Sep 2004)
# Original Source by Henri Gourvest hgourvest@progdigy.com
DSPack is a set of Components and class to write Multimedia Applications using MS Direct Show and DirectX technologies. DSPack is designed to work with DirectX 9 on Win9X, ME, 2000, and Windows XP operating systems. Now VMR (Video Mixing Renderer) is available on all Windows Operating Systems. DSPack 2 is designed to work with Delphi 5,6,7 and CPP Builder 6.

# What can I do with DSPack ?
I've writen DSPack with the idea to provide a non limitative set of components and class to use DirectShow easier. With DSpack you can create all that you want: DVD, capture, compression, filters, TV, webcam, DV ...

# How to install ?
All Versions
1 - Install DirectX9 if you plan to use VMR or Direct3D :  http://www.microsoft.com/windows/directx/downloads/drx90.asp
2 - Install Direct3D libraries if you plan to use Direct3D :  http://clootie.narod.ru/delphi/download_dx90.html
3 - Install Windows Media if you plan to use ASF compression or streaming:  http://www.progdigy.com/download/wmfdist.exe

# Delphi 5,6 & 7
1 - Add this paths to your search directory: 
        - (DSPackDir)\src\Directx9 
        - (DSPackDir)\src\DSPack 
2 - Compile DirectX 9 Package (DirectX9_Dx.dpk) from the "packages" directtory.
3 - Compile DSPack Package (DSPack_Dx.dpk) from the "packages" directory.
4- Install Design Package (DSPackDesign_Dx.dpk) from the "packages" directory.
If you have a warning message during the last step on Win9x, probaby the path : "../Delphi.../bin" is not correctly defined in "c:\autoexec.bat", in most case the path is too long. To correct this problem you have to set this path again. Alternatively change the bpl output directory option on each package to "$(DELPHI)\Bin" (Options>Directories/Conditionals>Output directory).

# CPP Builder 6
1 - Download the DirectX9 SDK from MS and update the "$(BCB)\Include" directory. You must also updates the DX SDK with the file provided in the "(DSPackDir)\Include" directory.
2 - Add this paths to your search directory: 
        - (DSPackDir)\src\Directx9 
        - (DSPackDir)\src\DSPack 
2 - Compile DirectX 9 Package (DirectX9_BCB6.dpk) from the "packages" directtory.
3 - Compile DSPack Package (DSPack_BCB6.dpk) from the "packages" directory.
4- Install Design Package (DSPackDesign_BCB6.dpk) from the "packages" directory.

# What does it cost ?
Nothing, DSPack is distributed under the MPL 1.1
