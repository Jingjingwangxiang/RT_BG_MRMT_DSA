This code is developed to explore the microbial-catalyzed denitrification processes in a woodchip bioreactor at the Kiruna pilot site. It was developed based on the previous code RT_MRMT_DSA which can be freely download from https://github.com/Jingjingwangxiang/RT_MRMT_DSA. 

It has been submitted to Water Research on March 2023, with a manuscript titled "Multirate mass transfer simulation of denitrification in a woodchip bioreactor". 

Developer: Jingjing Wang

Contact detail: Department of Civil and Environmental Engineering, Universitat Politécnica de Catalunya (UPC), Jordi Girona 1-3, 08034 Barcelona, Spain

Geosciences Department, Institute of Environmental Assessment and Water Research (IDAEA), Severo Ochoa Excellence Center, Spanish Scientific Research Council (CSIC), Jordi Girona, 18-26, 08034 Barcelona, Spain 

Email: jingjingwangxiang@126.com or jingjing.wang.xiang@gmail.com 

Year first available: March, 2023

Latest version: updated on March, 2023 

Hardware required: The code was run on a computer with 12th Gen Intel(R) Core(TM) i7-12700KF 3.60 GHz, 32GB Installed memory (RAM), 64-bit Operating System, x64-based processor.

Software development platform: Microsoft Visual Studio 2022 

Program language: object-oriented programming FORTRAN2003

Compiler: Intel oneAPI 2022 

Library: Intel Math Kernel Library (Intel® MKL).

To solve the system equation (14), we call routine dgbtrf() to compute the LU factorization of the left hand side matrix of system equation (14), then we call routine dgbtrs() to solve the linear system with the LU-factored square coefficient matrix returned by routine dgbtrf().

Details on how to access the open-source code: the source code can be freely download from GitHub on the public repository https://github.com/Jingjingwangxiang/RT_MRMT_DSA_BG.git 
