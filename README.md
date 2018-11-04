## 准备工作、工具、环境和Demo
- 加入微信群：微信 -> 通讯录 -> 新的朋友 -> 添加朋友 -> 面对面建群
- 环境：
	- OS：Win7 / Win8.1 / Win10
	- IDE：VS2015 / VS2017
- 下载：[工具 & Demo](https://share.weiyun.com/5SHAbCW)

## 内容
- Prerequirements
	- Assembly Language
		- x86: [Architecture](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/x86-architecture), [Instructions](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/x86-instructions)
		- x64: [Architecture](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/x64-architecture), [Instructions](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/x64-instructions)
		- [Writing Functions with Inline Assembly](https://msdn.microsoft.com/en-us/library/5sds75we.aspx)
	- C++
		- [Welcome Back to C++ (Modern C++)](https://msdn.microsoft.com/en-us/library/hh279654.aspx)
		- [C++ Language Reference](https://msdn.microsoft.com/en-us/library/3bstk3k5.aspx)
		- [Lambda Expressions in C++](https://msdn.microsoft.com/en-us/library/dd293608.aspx)
		- [C++ Standard Library Reference](https://msdn.microsoft.com/en-us/library/cscc687y.aspx)
	- Python
		- [Download](https://www.python.org/downloads/)
		- [Installation](https://github.com/wu-wenxiang/Training-Python-Public/blob/master/doc/Installation-Python.md)
	- Windows操作系统基础
		- [Windows Internals Book](https://docs.microsoft.com/en-us/sysinternals/learn/windows-internals)
		- [Windows Sysinternals](https://docs.microsoft.com/en-us/sysinternals/): [Forums Support](https://social.technet.microsoft.com/Forums/en-US/home?category=sysinternals&amp;filter=alltypes&amp;sort=lastpostdesc), [一句话介绍](http://blog.wuwenxiang.net/Windows-Sysinternals), [使用文档](https://docs.microsoft.com/en-us/sysinternals/learn/troubleshooting-book)
- Native C++ Desktop Rendering Introduction & Best Practice
	- Rendering Pipeline
	- ![渲染管线.jpg](https://pic4.zhimg.com/v2-1e286dd517c717e3f1c48792275f7e87_r.jpg)
	- Rasterization
	- ![三角形的软件光栅化.png](http://hi.csdn.net/attachment/201103/8/8458191_1299585635RfNA.png)
	- [Overview of the Windows Graphics Architecture](https://docs.microsoft.com/en-us/windows/desktop/learnwin32/overview-of-the-windows-graphics-architecture)
		- [GDI](https://msdn.microsoft.com/en-us/library/ms969913.aspx)
		- [GDI+](https://docs.microsoft.com/en-us/windows/desktop/gdiplus/-gdiplus-gdi-start)
		- [OpenGL](https://learnopengl.com/Getting-started/OpenGL)
		- [Unity](https://link.zhihu.com/?target=http%3A//unity3d.com/learn/tutorials/modules) 
	- [Comparing Direct2D and GDI Hardware Acceleration](https://docs.microsoft.com/en-us/windows/desktop/direct2d/comparing-direct2d-and-gdi)
	- [Direct2D in action](https://docs.microsoft.com/en-us/windows/desktop/learnwin32/your-first-direct2d-program)
	- Howto: [Improving the performance of Direct2D apps](https://docs.microsoft.com/en-us/windows/desktop/direct2d/improving-direct2d-performance)
- Performance Tunning
	- [Debugging Tips for the Windows Display Driver Model](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/debugging-tips-for-the-windows-vista-display-driver-model)
	- Tools: [Sysinternals](https://docs.microsoft.com/en-us/sysinternals) (Procmon / ProcExp / Handle, etc)
	- [Profiling native C++ rendering apps](https://docs.microsoft.com/en-us/windows/desktop/direct2d/profiling-directx-applications)
		- [Xperf](https://blogs.msdn.microsoft.com/ntdebugging/2008/04/03/windows-performance-toolkit-xperf/) 
		- [GPUView](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/using-gpuview)
- Windbg Usage & Demo
	- [Windbg Download & Installation](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)
	- [Debugging with Symbols](https://docs.microsoft.com/en-us/windows/desktop/dxtecharts/debugging-with-symbols)
	- [Getting Started With Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg)
	- [Windbg Commands](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/commands)
	- [Debugging Using WinDbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-using-windbg)
	- [Standard Debugging Techniques](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/standard-debugging-techniques)
	- [CrashMe Project](https://mikedoszhang.blogspot.com/search?q=CrashMe+analysis+tutorial)
	- Tools: [Procdump](https://docs.microsoft.com/en-us/sysinternals/downloads/procdump)
	- Demo
		- [Crash](https://msdn.microsoft.com/library/windows/desktop/ee416349)
		- [Hang](https://blogs.msdn.microsoft.com/benjaminperkins/2013/01/08/debugging-a-hung-application-with-windbg/)
		- [Hang2](https://blogs.msdn.microsoft.com/msdnts/2006/11/24/how-to-debug-application-crashhang-in-production-environment/)
		- [Native Memory Leak](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/using-umdh-to-find-a-user-mode-memory-leak)
		- [Managed Memory Leak](https://blogs.msdn.microsoft.com/paullou/2011/06/28/debugging-managed-code-memory-leak-with-memory-dump-using-windbg/)
		- [CPU High](https://blogs.msdn.microsoft.com/ntdebugging/2008/05/15/how-to-track-down-high-cpu-in-user-mode-applications-a-live-debug/)
	- Scripts: [pykd](https://github.com/wu-wenxiang/Tool-Windbg-Pykd-Scripts)
	- Tools: [DebugDiag](https://www.microsoft.com/en-us/download/details.aspx?id=49924)
		- Demo: [How to use the Debug Diagnostics tool to troubleshoot a process that has stopped responding in IIS](https://support.microsoft.com/en-us/help/919792/how-to-use-the-debug-diagnostics-tool-to-troubleshoot-a-process-that-h)
		- Demo: [How to use the Debug Diagnostics Tool to troubleshoot high CPU usage by a process in IIS](https://support.microsoft.com/en-us/help/919791/how-to-use-the-debug-diagnostics-tool-to-troubleshoot-high-cpu-usage-b)
- What's More?
	- [Getting Started With Windbg Kernel Mode](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg--kernel-mode-)
	- [Mex Extension](https://www.microsoft.com/en-us/download/details.aspx?id=53304): [Usage Blog](https://blogs.msdn.microsoft.com/luisdem/2016/07/19/mex-debugging-extension-for-windbg-2/)
	- [Debugging Using Windbg Preview](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-using-windbg-preview)
	- [Time Travel Debugging Overview](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/time-travel-debugging-overview)
	- Scripts: [javascript](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/time-travel-debugging-javascript-automation)
