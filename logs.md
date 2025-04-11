macOS 错误跟踪窗口：
```
-------------------------------------
Translated Report (Full Report Below)
-------------------------------------

Process:               Class Widgets [12744]
Path:                  /Users/USER/Downloads/*/Class Widgets.app/Contents/MacOS/Class Widgets
Identifier:            Class Widgets
Version:               0.0.0 (???)
Code Type:             X86-64 (Native)
Parent Process:        zsh [12728]
Responsible:           Terminal [10247]
User ID:               501

Date/Time:             2025-04-11 16:51:29.0839 +0800
OS Version:            macOS 15.3.2 (24D81)
Report Version:        12
Bridge OS Version:     9.3 (22P3060)
Anonymous UUID:        526C3592-2EAD-ADB2-7CE8-9CEF7D720D80

Sleep/Wake UUID:       25A2F530-C0BD-4608-A716-26148098E9B6

Time Awake Since Boot: 33000 seconds
Time Since Wake:       601 seconds

System Integrity Protection: enabled

Crashed Thread:        10  SystemThemeListener

Exception Type:        EXC_CRASH (SIGABRT)
Exception Codes:       0x0000000000000000, 0x0000000000000000

Termination Reason:    Namespace SIGNAL, Code 6 Abort trap: 6
Terminating Process:   Class Widgets [12744]

Application Specific Information:
abort() called


Thread 0::  Dispatch queue: com.apple.main-thread
0   libsystem_kernel.dylib        	    0x7ff806c75aaa __psynch_cvwait + 10
1   libsystem_pthread.dylib       	    0x7ff806cb47a8 _pthread_cond_wait + 1193
2   libpython3.8.dylib            	       0x10d0e979f take_gil + 591
3   libpython3.8.dylib            	       0x10d1653a3 PyGILState_Ensure + 131
4   sip.cpython-38-darwin.so      	       0x10e129751 sip_api_is_py_method_12_8 + 65
5   QtCore.abi3.so                	       0x10e45aeed sipQFile::readData(char*, long long) + 61
6   QtCore                        	       0x10ee3006b QIODevicePrivate::read(char*, long long, bool) + 571
7   QtCore                        	       0x10ee308a4 QIODevice::readAll() + 356
8   QtCore.abi3.so                	       0x10e518146 meth_QIODevice_readAll(_object*, _object*) + 102
9   libpython3.8.dylib            	       0x10cfb9ad5 cfunction_call_varargs + 197
10  libpython3.8.dylib            	       0x10cfb905c _PyObject_MakeTpCall + 188
11  libpython3.8.dylib            	       0x10d0f3e32 _PyEval_EvalFrameDefault + 31426
12  libpython3.8.dylib            	       0x10cfba1e5 _PyFunction_Vectorcall + 245
13  libpython3.8.dylib            	       0x10d0f1136 _PyEval_EvalFrameDefault + 19910
14  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
15  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
16  libpython3.8.dylib            	       0x10d0f1697 _PyEval_EvalFrameDefault + 21287
17  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
18  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
19  libpython3.8.dylib            	       0x10d0f1136 _PyEval_EvalFrameDefault + 19910
20  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
21  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
22  libpython3.8.dylib            	       0x10d0f1136 _PyEval_EvalFrameDefault + 19910
23  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
24  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
25  libpython3.8.dylib            	       0x10d0f1697 _PyEval_EvalFrameDefault + 21287
26  libpython3.8.dylib            	       0x10cfba1e5 _PyFunction_Vectorcall + 245
27  libpython3.8.dylib            	       0x10cfbdd4e method_vectorcall + 142
28  libpython3.8.dylib            	       0x10d0f26bb _PyEval_EvalFrameDefault + 25419
29  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
30  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
31  libpython3.8.dylib            	       0x10cfb8dc2 _PyObject_FastCallDict + 194
32  libpython3.8.dylib            	       0x10d0413e3 slot_tp_init + 179
33  libpython3.8.dylib            	       0x10d04ce19 type_call + 297
34  libpython3.8.dylib            	       0x10cfb905c _PyObject_MakeTpCall + 188
35  libpython3.8.dylib            	       0x10d0f2d34 _PyEval_EvalFrameDefault + 27076
36  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
37  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
38  libpython3.8.dylib            	       0x10cfbdd4e method_vectorcall + 142
39  libpython3.8.dylib            	       0x10d0f26bb _PyEval_EvalFrameDefault + 25419
40  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
41  libpython3.8.dylib            	       0x10cfba29a _PyFunction_Vectorcall + 426
42  libpython3.8.dylib            	       0x10cfb8d4f _PyObject_FastCallDict + 79
43  libpython3.8.dylib            	       0x10d0413e3 slot_tp_init + 179
44  libpython3.8.dylib            	       0x10d04ce19 type_call + 297
45  libpython3.8.dylib            	       0x10cfb905c _PyObject_MakeTpCall + 188
46  libpython3.8.dylib            	       0x10d0f2d5d _PyEval_EvalFrameDefault + 27117
47  libpython3.8.dylib            	       0x10cfba1e5 _PyFunction_Vectorcall + 245
48  libpython3.8.dylib            	       0x10d0f1697 _PyEval_EvalFrameDefault + 21287
49  libpython3.8.dylib            	       0x10cfba1e5 _PyFunction_Vectorcall + 245
50  libpython3.8.dylib            	       0x10d0f1136 _PyEval_EvalFrameDefault + 19910
51  libpython3.8.dylib            	       0x10d0ea501 _PyEval_EvalCodeWithName + 561
52  libpython3.8.dylib            	       0x10d0ea2c3 PyEval_EvalCode + 51
53  Class Widgets                 	       0x10c5e35f4 0x10c5e0000 + 13812
54  Class Widgets                 	       0x10c5e4015 0x10c5e0000 + 16405
55  dyld                          	    0x7ff8069252cd start + 1805

Thread 1:
0   libsystem_pthread.dylib       	    0x7ff806cafbcc start_wqthread + 0

Thread 2:
0   libsystem_pthread.dylib       	    0x7ff806cafbcc start_wqthread + 0

Thread 3:: caulk.messenger.shared:17
0   libsystem_kernel.dylib        	    0x7ff806c72e8a semaphore_wait_trap + 10
1   caulk                         	    0x7ff8120bcc9d caulk::semaphore::timed_wait(double) + 151
2   caulk                         	    0x7ff8120bcbc8 caulk::concurrent::details::worker_thread::run() + 30
3   caulk                         	    0x7ff8120bc90a void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*) + 41
4   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
5   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 4:: caulk.messenger.shared:high
0   libsystem_kernel.dylib        	    0x7ff806c72e8a semaphore_wait_trap + 10
1   caulk                         	    0x7ff8120bcc9d caulk::semaphore::timed_wait(double) + 151
2   caulk                         	    0x7ff8120bcbc8 caulk::concurrent::details::worker_thread::run() + 30
3   caulk                         	    0x7ff8120bc90a void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*) + 41
4   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
5   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 5:: AudioQueue thread
0   libsystem_kernel.dylib        	    0x7ff806c72f0e mach_msg2_trap + 10
1   libsystem_kernel.dylib        	    0x7ff806c815fa mach_msg2_internal + 84
2   libsystem_kernel.dylib        	    0x7ff806c7a016 mach_msg_overwrite + 649
3   libsystem_kernel.dylib        	    0x7ff806c731ff mach_msg + 19
4   CoreFoundation                	    0x7ff806d9ade2 __CFRunLoopServiceMachPort + 143
5   CoreFoundation                	    0x7ff806d9980f __CFRunLoopRun + 1393
6   CoreFoundation                	    0x7ff806d98c6e CFRunLoopRunSpecific + 550
7   libSDL2-2.0.0.dylib           	       0x11371b712 audioqueue_thread + 1090
8   libSDL2-2.0.0.dylib           	       0x11366dc6c SDL_RunThread + 44
9   libSDL2-2.0.0.dylib           	       0x1137019f9 RunThread + 9
10  libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
11  libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 6:: caulk::deferred_logger
0   libsystem_kernel.dylib        	    0x7ff806c72e8a semaphore_wait_trap + 10
1   caulk                         	    0x7ff8120bcc9d caulk::semaphore::timed_wait(double) + 151
2   caulk                         	    0x7ff8120bcbc8 caulk::concurrent::details::worker_thread::run() + 30
3   caulk                         	    0x7ff8120bc90a void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*) + 41
4   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
5   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 7:: AQConverterThread
0   libsystem_kernel.dylib        	    0x7ff806c75aaa __psynch_cvwait + 10
1   libsystem_pthread.dylib       	    0x7ff806cb47a8 _pthread_cond_wait + 1193
2   libAudioToolboxUtility.dylib  	    0x7ff817685cb2 CADeprecated::CAGuard::Wait() + 68
3   AudioToolbox                  	    0x7ff8189d6d74 AQConverterManager::AQConverterThread::ConverterThreadEntry(void*) + 578
4   libAudioToolboxUtility.dylib  	    0x7ff817665497 CADeprecated::CAPThread::Entry(void*) + 77
5   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
6   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 8:: com.apple.audio.IOThread.client
0   libsystem_kernel.dylib        	    0x7ff806c72e96 semaphore_wait_signal_trap + 10
1   caulk                         	    0x7ff8120d6315 caulk::mach::semaphore::wait_signal_or_error(caulk::mach::semaphore&) + 23
2   CoreAudio                     	    0x7ff809642be5 HALC_ProxyIOContext::IOWorkLoop() + 5515
3   CoreAudio                     	    0x7ff809640e5c invocation function for block in HALC_ProxyIOContext::HALC_ProxyIOContext(unsigned int, unsigned int) + 148
4   CoreAudio                     	    0x7ff8097f1feb HALC_IOThread::Entry(void*) + 73
5   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
6   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 9:
0   libsystem_pthread.dylib       	    0x7ff806cafbcc start_wqthread + 0

Thread 10 Crashed:: SystemThemeListener
0   libsystem_kernel.dylib        	    0x7ff806c79c52 __pthread_kill + 10
1   libsystem_pthread.dylib       	    0x7ff806cb3f85 pthread_kill + 262
2   libsystem_c.dylib             	    0x7ff806bd4b19 abort + 126
3   libc++abi.dylib               	    0x7ff806c6b163 abort_message + 258
4   libc++abi.dylib               	    0x7ff806c5c0ce demangling_terminate_handler() + 266
5   libobjc.A.dylib               	    0x7ff8068f8d61 _objc_terminate() + 96
6   libc++abi.dylib               	    0x7ff806c6a53b std::__terminate(void (*)()) + 6
7   libc++abi.dylib               	    0x7ff806c6a4f6 std::terminate() + 54
8   QtCore                        	       0x10ed1e275 0x10ecfe000 + 131701
9   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
10  libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15

Thread 11:: HIE: __ d000f42d2d95c51b 2025-04-11 16:51:29.059
0   libsystem_kernel.dylib        	    0x7ff806c72f0e mach_msg2_trap + 10
1   libsystem_kernel.dylib        	    0x7ff806c815fa mach_msg2_internal + 84
2   libsystem_kernel.dylib        	    0x7ff806c9989b thread_suspend + 83
3   HIServices                    	    0x7ff80d75169b SOME_OTHER_THREAD_SWALLOWED_AT_LEAST_ONE_EXCEPTION + 16
4   Foundation                    	    0x7ff807dcb483 __NSThread__start__ + 1007
5   libsystem_pthread.dylib       	    0x7ff806cb4253 _pthread_start + 99
6   libsystem_pthread.dylib       	    0x7ff806cafbef thread_start + 15


Thread 10 crashed with X86 Thread State (64-bit):
  rax: 0x0000000000000000  rbx: 0x0000000000000006  rcx: 0x00007000100fcd48  rdx: 0x0000000000000000
  rdi: 0x0000000000010c07  rsi: 0x0000000000000006  rbp: 0x00007000100fcd70  rsp: 0x00007000100fcd48
   r8: 0x00007000100fcc10   r9: 0xffffffffffffffff  r10: 0x0000000000000000  r11: 0x0000000000000246
  r12: 0x00007ff849bf2a00  r13: 0x0000003000000008  r14: 0x0000000000010c07  r15: 0x0000000000000016
  rip: 0x00007ff806c79c52  rfl: 0x0000000000000246  cr2: 0x0000000000000000
  
Logical CPU:     0
Error Code:      0x02000148 
Trap Number:     133


Binary Images:
       0x10c5e0000 -        0x10c5ebfff Class Widgets (0.0.0) <f0258b48-b4f2-3f50-8165-65c85abc9adc> /Users/USER/Downloads/*/Class Widgets.app/Contents/MacOS/Class Widgets
       0x10cf89000 -        0x10d2a8fff libpython3.8.dylib (*) <dfe181a3-5091-3fc5-b1e1-9df9ccbb33cf> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libpython3.8.dylib
       0x10cb59000 -        0x10cb64fff libintl.8.dylib (*) <005712ba-00b8-3168-beae-4e75513dea8e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libintl.8.dylib
       0x10ccb5000 -        0x10ccbcfff _struct.cpython-38-darwin.so (*) <44fd2f1e-d7ea-3343-baa8-020bab9cfca0> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_struct.cpython-38-darwin.so
       0x10cd11000 -        0x10cd18fff zlib.cpython-38-darwin.so (*) <6ad16d6d-6bf4-368e-99bd-78e61235a1dd> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/zlib.cpython-38-darwin.so
       0x10cd97000 -        0x10cdaafff _ctypes.cpython-38-darwin.so (*) <b65813ac-4bbe-3115-962b-6730220afd9a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_ctypes.cpython-38-darwin.so
       0x10cd69000 -        0x10cd6cfff _heapq.cpython-38-darwin.so (*) <af41cfc3-36d4-341f-972b-5d2624ae68b7> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_heapq.cpython-38-darwin.so
       0x10cd7d000 -        0x10cd84fff binascii.cpython-38-darwin.so (*) <d6ed2447-56b7-373f-badd-d53998ac9b10> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/binascii.cpython-38-darwin.so
       0x10cf64000 -        0x10cf6ffff math.cpython-38-darwin.so (*) <b91841bb-6be5-3290-8a55-211473581636> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/math.cpython-38-darwin.so
       0x10cf47000 -        0x10cf4afff _bisect.cpython-38-darwin.so (*) <cdec3ef8-508b-34ac-bd49-4e7e0c656b15> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_bisect.cpython-38-darwin.so
       0x10d3f5000 -        0x10d3fcfff _sha512.cpython-38-darwin.so (*) <b0e1ac5c-a5e4-39c0-b686-9c4b3acb4705> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_sha512.cpython-38-darwin.so
       0x10d40d000 -        0x10d410fff _random.cpython-38-darwin.so (*) <2fc78912-2b50-3f6d-be7f-77d1242c4b21> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_random.cpython-38-darwin.so
       0x10d484000 -        0x10d493fff _socket.cpython-38-darwin.so (*) <7a61b276-9177-3f4b-a091-132ea1408005> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_socket.cpython-38-darwin.so
       0x10d461000 -        0x10d464fff select.cpython-38-darwin.so (*) <3557257a-0764-3705-88a4-436d4bc718cb> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/select.cpython-38-darwin.so
       0x10d50d000 -        0x10d51cfff _datetime.cpython-38-darwin.so (*) <59013994-caf9-3bbb-bbc3-527e0ba965f4> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_datetime.cpython-38-darwin.so
       0x10d4e8000 -        0x10d4ebfff _opcode.cpython-38-darwin.so (*) <cfc88a86-37d4-3e53-98fe-1c53422997d5> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_opcode.cpython-38-darwin.so
       0x10d63d000 -        0x10d668fff pyexpat.cpython-38-darwin.so (*) <a92ce866-3fc9-30c5-82ae-af9320412037> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/pyexpat.cpython-38-darwin.so
       0x10d6c5000 -        0x10d6c8fff _bz2.cpython-38-darwin.so (*) <393f45ff-1f3a-3f3b-ae5f-0e79406139c3> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_bz2.cpython-38-darwin.so
       0x10d6d9000 -        0x10d6e0fff _lzma.cpython-38-darwin.so (*) <c8b62ed4-8ded-3728-b8b8-5e59d6d9f270> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_lzma.cpython-38-darwin.so
       0x10d71f000 -        0x10d73efff liblzma.5.dylib (*) <dbab8212-2071-3e7a-b416-ba92b59e8773> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/liblzma.5.dylib
       0x10d6f1000 -        0x10d6f4fff grp.cpython-38-darwin.so (*) <b063b470-ea6f-3249-b4f0-b36cf625e452> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/grp.cpython-38-darwin.so
       0x10d705000 -        0x10d708fff _posixsubprocess.cpython-38-darwin.so (*) <97836b3c-b43e-3b82-b0ce-d580f65cc986> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_posixsubprocess.cpython-38-darwin.so
       0x10d90f000 -        0x10d912fff _queue.cpython-38-darwin.so (*) <0d64a2c3-634b-35fc-9bde-1856503dfdc8> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_queue.cpython-38-darwin.so
       0x10d963000 -        0x10d966fff _hashlib.cpython-38-darwin.so (*) <7f05d31b-9421-3a98-bcd0-900125c37be6> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_hashlib.cpython-38-darwin.so
       0x10d9f7000 -        0x10da46fff libssl.1.1.dylib (*) <6f913138-95a2-33a3-92be-45a5d0b88c88> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libssl.1.1.dylib
       0x10dccd000 -        0x10de88fff libcrypto.1.1.dylib (*) <87e528a0-0329-33e5-a9b7-e37da4569b10> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libcrypto.1.1.dylib
       0x10d977000 -        0x10d97efff _blake2.cpython-38-darwin.so (*) <844c484a-248e-395f-a1aa-b56f15a65743> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_blake2.cpython-38-darwin.so
       0x10d9b3000 -        0x10d9c6fff _sha3.cpython-38-darwin.so (*) <e8e3dba3-5a0f-3f16-8b5b-15d89fcd5f7a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_sha3.cpython-38-darwin.so
       0x10daed000 -        0x10db04fff _ssl.cpython-38-darwin.so (*) <f56952f5-932b-3cc0-b45e-53e79051bea2> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_ssl.cpython-38-darwin.so
       0x10d98f000 -        0x10d992fff _scproxy.cpython-38-darwin.so (*) <cfb75b47-766b-3539-827f-01be4f263888> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_scproxy.cpython-38-darwin.so
       0x10e0a9000 -        0x10e0c4fff _pickle.cpython-38-darwin.so (*) <e7065d39-0c91-3be9-a626-19bad35eb838> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_pickle.cpython-38-darwin.so
       0x10d9d7000 -        0x10d9defff array.cpython-38-darwin.so (*) <e361d37b-7692-3d93-97f3-66a6117dbf9e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/array.cpython-38-darwin.so
       0x10e411000 -        0x10e598fff QtCore.abi3.so (*) <50e61d65-8075-353a-a072-4648e60cb069> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/QtCore.abi3.so
       0x10ecfe000 -        0x10f220fff QtCore (*) <44b06aca-cb6e-34bf-8360-c7b770c43e92> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtCore
       0x10e11d000 -        0x10e134fff sip.cpython-38-darwin.so (*) <64d78214-7612-323f-8871-2d85aa6287e6> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/sip.cpython-38-darwin.so
       0x10dace000 -        0x10dad5fff _json.cpython-38-darwin.so (*) <4b6d01cc-7915-3749-9b43-67f1a703923a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_json.cpython-38-darwin.so
       0x10dca5000 -        0x10dcacfff _csv.cpython-38-darwin.so (*) <f0574b3a-be31-39b7-a45f-a11e86d88084> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_csv.cpython-38-darwin.so
       0x10d4fc000 -        0x10d4fffff md.cpython-38-darwin.so (*) <143bfd0a-fbaa-3849-bbaa-9d3b2d44c38f> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/charset_normalizer/md.cpython-38-darwin.so
       0x10e386000 -        0x10e3a9fff md__mypyc.cpython-38-darwin.so (*) <16c06709-1b00-34a5-b632-e21f240da021> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/charset_normalizer/md__mypyc.cpython-38-darwin.so
       0x10e821000 -        0x10e928fff unicodedata.cpython-38-darwin.so (*) <2f381e19-e395-39db-ab40-acd8049f7ed0> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/unicodedata.cpython-38-darwin.so
       0x10e366000 -        0x10e36dfff _multibytecodec.cpython-38-darwin.so (*) <2404461f-f18a-361d-a0b7-68307a652d94> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_multibytecodec.cpython-38-darwin.so
       0x10e7e8000 -        0x10e7f3fff _elementtree.cpython-38-darwin.so (*) <7a61123a-447d-372d-980a-d8576d5bdb84> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_elementtree.cpython-38-darwin.so
       0x11125d000 -        0x1113f4fff QtGui.abi3.so (*) <24c335fe-64ec-319b-848a-97ce19425aeb> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/QtGui.abi3.so
       0x111c10000 -        0x112183fff QtGui (*) <f01340e7-d4fb-3710-8458-e407eac32f30> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtGui
       0x10e9e4000 -        0x10e9f4fff QtSvg.abi3.so (*) <65e8ddee-e60c-3482-9ad8-bf60789d4eaf> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/QtSvg.abi3.so
       0x10ea62000 -        0x10ea97fff QtSvg (*) <e3ed66a5-0b14-3059-8305-7ca311d0e457> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtSvg
       0x1122ac000 -        0x1126e9fff QtWidgets (*) <59fc7134-f414-3077-b2e0-8c20ff66965a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtWidgets
       0x11285e000 -        0x112b30fff QtWidgets.abi3.so (*) <8a63c017-cfa7-3b76-a5da-8068cfb5a1e2> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/QtWidgets.abi3.so
       0x10e34c000 -        0x10e34ffff _contextvars.cpython-38-darwin.so (*) <54cc0bab-3625-3a4a-8667-6b7968c772e1> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_contextvars.cpython-38-darwin.so
       0x10e9bd000 -        0x10e9c4fff _asyncio.cpython-38-darwin.so (*) <9a4da124-9002-396b-9d1a-8688048aedda> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_asyncio.cpython-38-darwin.so
       0x10ec9b000 -        0x10ecdefff _decimal.cpython-38-darwin.so (*) <e5971410-a0f0-3c4d-82c6-d5394402df32> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_decimal.cpython-38-darwin.so
       0x1116a8000 -        0x111773fff _objc.cpython-38-darwin.so (*) <451d815f-e5af-30e5-a4de-4550ab686df0> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/objc/_objc.cpython-38-darwin.so
       0x10e7c7000 -        0x10e7cefff _CoreFoundation.cpython-38-darwin.so (*) <42765bd0-149f-3358-bf3d-4c06d3ade426> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/CoreFoundation/_CoreFoundation.cpython-38-darwin.so
       0x10d475000 -        0x10d475fff _inlines.cpython-38-darwin.so (*) <abff7698-e14a-31f4-a188-3c6cc2edf6a5> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/CoreFoundation/_inlines.cpython-38-darwin.so
       0x10ec7b000 -        0x10ec81fff _Foundation.cpython-38-darwin.so (*) <f82d9a83-de87-38c5-96d1-63c723ca8ee2> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Foundation/_Foundation.cpython-38-darwin.so
       0x10dab7000 -        0x10dab8fff _inlines.cpython-38-darwin.so (*) <fab8fecd-0bc6-3d85-b10c-03d647fc039a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Foundation/_inlines.cpython-38-darwin.so
       0x111b93000 -        0x111ba8fff _AppKit.cpython-38-darwin.so (*) <803739fc-3c74-320e-a588-a98ab65c7156> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/AppKit/_AppKit.cpython-38-darwin.so
       0x10d9a3000 -        0x10d9a3fff _inlines.cpython-38-darwin.so (*) <55261834-bc74-30a7-b611-8b5df7a35f60> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/AppKit/_inlines.cpython-38-darwin.so
       0x112e8c000 -        0x112eb4fff QtXml.abi3.so (*) <f588dd9a-d393-311a-bc4e-a38d6f30dbb1> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/QtXml.abi3.so
       0x112ee5000 -        0x112f13fff QtXml (*) <8fa6c55e-50da-3a52-b409-e5dcabcfb816> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtXml
       0x10e80c000 -        0x10e810fff _callbacks.cpython-38-darwin.so (*) <e534277b-c87c-3cb5-9714-d8e12a91c725> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreGraphics/_callbacks.cpython-38-darwin.so
       0x10dac3000 -        0x10dac3fff _doubleindirect.abi3.so (*) <1c2999a7-38e4-3b5d-9f99-dc834606cf93> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreGraphics/_doubleindirect.abi3.so
       0x10ea4b000 -        0x10ea4cfff _sortandmap.abi3.so (*) <f600f753-93be-34bd-b159-82f09fe61264> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreGraphics/_sortandmap.abi3.so
       0x11167b000 -        0x11167cfff _coregraphics.cpython-38-darwin.so (*) <a151f513-f76d-3eb3-95af-033e573513f2> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreGraphics/_coregraphics.cpython-38-darwin.so
       0x10dcbd000 -        0x10dcbdfff _inlines.abi3.so (*) <7c85e945-be4d-3ad6-b898-d71cb7720706> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreGraphics/_inlines.abi3.so
       0x111687000 -        0x111688fff _imagekit.abi3.so (*) <14bdc2a8-ae57-37de-ab09-70475ec4d8ff> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/ImageKit/_imagekit.abi3.so
       0x10e406000 -        0x10e406fff _CVPixelBuffer.abi3.so (*) <e4caa010-46db-3512-8010-a0e79cf6eb36> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/CoreVideo/_CVPixelBuffer.abi3.so
       0x111bd1000 -        0x111bd6fff _quartzcore.abi3.so (*) <b708cf89-6fea-3b18-a9c1-5f176cecb585> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/QuartzCore/_quartzcore.abi3.so
       0x10e7dd000 -        0x10e7ddfff _PDFKit.abi3.so (*) <cf1e6800-63a5-3932-a1cf-4629a43e6045> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/PDFKit/_PDFKit.abi3.so
       0x10ea57000 -        0x10ea57fff _QuickLookUI.abi3.so (*) <03bbbd82-4960-38b7-8387-9f3ad4790fd7> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/Quartz/QuickLookUI/_QuickLookUI.abi3.so
       0x111b55000 -        0x111b5cfff base.cpython-38-darwin.so (*) <4ee1de6a-42cb-3bcd-bb69-eb7e68944b72> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/base.cpython-38-darwin.so
       0x1135ee000 -        0x11375dfff libSDL2-2.0.0.dylib (*) <4c09b3f9-7a3c-3ff6-ac1f-5e17fda7390c> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libSDL2-2.0.0.dylib
       0x1133aa000 -        0x1133b5fff constants.cpython-38-darwin.so (*) <532b6781-d275-3ba8-bccd-ac11defa4aea> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/constants.cpython-38-darwin.so
       0x111b69000 -        0x111b70fff rect.cpython-38-darwin.so (*) <d370b66d-e0dd-3f45-9bce-c7c3d8a24e8e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/rect.cpython-38-darwin.so
       0x111b81000 -        0x111b84fff rwobject.cpython-38-darwin.so (*) <5b4a9427-e3cc-39ec-9717-c08b8ee3dac7> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/rwobject.cpython-38-darwin.so
       0x112e76000 -        0x112e79fff surflock.cpython-38-darwin.so (*) <71f4097e-4863-3866-85eb-ecdb5bcbed27> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/surflock.cpython-38-darwin.so
       0x113402000 -        0x113409fff color.cpython-38-darwin.so (*) <0b8dc62b-f0bf-3bf4-be17-0904391dac91> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/color.cpython-38-darwin.so
       0x113416000 -        0x113419fff bufferproxy.cpython-38-darwin.so (*) <55e3fd66-0171-3c1c-96db-f770e0adf9f3> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/bufferproxy.cpython-38-darwin.so
       0x113445000 -        0x113454fff math.cpython-38-darwin.so (*) <1f299e6a-28bd-38f6-aad5-1f6cb3d6d8b8> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/math.cpython-38-darwin.so
       0x113426000 -        0x11342dfff display.cpython-38-darwin.so (*) <4828a107-7a53-3872-831d-112d87323a07> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/display.cpython-38-darwin.so
       0x1134ad000 -        0x1134e4fff surface.cpython-38-darwin.so (*) <e1dfe43c-d4ac-343d-bb77-cd0f5bbaa883> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/surface.cpython-38-darwin.so
       0x11347c000 -        0x113487fff draw.cpython-38-darwin.so (*) <104d509f-5b06-37a3-9d2f-2ef0823e571f> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/draw.cpython-38-darwin.so
       0x113494000 -        0x11349bfff event.cpython-38-darwin.so (*) <72929b1f-8b75-3ea4-ab06-82df24c4773d> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/event.cpython-38-darwin.so
       0x113465000 -        0x11346cfff image.cpython-38-darwin.so (*) <21c96b96-2918-3e8a-abcf-613640a4b212> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/image.cpython-38-darwin.so
       0x1134f5000 -        0x1134f8fff imageext.cpython-38-darwin.so (*) <30c21190-e287-35dc-89f1-70fc8e7e9dca> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/imageext.cpython-38-darwin.so
       0x113539000 -        0x11355cfff libSDL2_image-2.0.0.dylib (*) <097cb12c-1e47-3414-a520-536d5cd6cbeb> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libSDL2_image-2.0.0.dylib
       0x113832000 -        0x113861fff libpng16.16.dylib (*) <e881cc35-c895-3466-a3ee-39269498cfdf> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libpng16.16.dylib
       0x11393c000 -        0x1139dbfff libjpeg.62.3.0.dylib (*) <d926dcf5-263f-3399-998b-996067e0ea8b> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libjpeg.62.3.0.dylib
       0x1139fc000 -        0x113a73fff libtiff.5.8.0.dylib (*) <4e74b4c4-8261-3267-bd0f-a9cf2a864d58> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libtiff.5.8.0.dylib
       0x11356d000 -        0x113588fff libz.1.2.11.zlib-ng.dylib (*) <1db292da-07c1-3f22-918d-fb52e8836a37> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libz.1.2.11.zlib-ng.dylib
       0x113a88000 -        0x113b07fff libwebp.7.dylib (*) <edb0324e-35d8-3f86-acbe-abce96ed800e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libwebp.7.dylib
       0x113505000 -        0x113508fff libsharpyuv.0.dylib (*) <50e4611c-bfba-3c0f-b8aa-7cbc0836780e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libsharpyuv.0.dylib
       0x113515000 -        0x113518fff joystick.cpython-38-darwin.so (*) <e876a4d6-86cc-35dd-a55d-d50be9d1aad4> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/joystick.cpython-38-darwin.so
       0x113525000 -        0x113528fff key.cpython-38-darwin.so (*) <6c0bac1c-9430-34bd-a6cc-0d800f55da2b> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/key.cpython-38-darwin.so
       0x113595000 -        0x113598fff mouse.cpython-38-darwin.so (*) <59a3b322-446d-38c3-af99-f3c599dd4c5d> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/mouse.cpython-38-darwin.so
       0x11387e000 -        0x113881fff time.cpython-38-darwin.so (*) <27f8c6f0-0cf6-3ff7-88db-a8ad5b43aa0d> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/time.cpython-38-darwin.so
       0x1138aa000 -        0x1138b9fff mask.cpython-38-darwin.so (*) <f2fa612b-be3f-37d4-afeb-f9e1377c741e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/mask.cpython-38-darwin.so
       0x1138c6000 -        0x1138d1fff pixelcopy.cpython-38-darwin.so (*) <4607718b-366d-3e2d-9c45-c0a29ba697fb> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/pixelcopy.cpython-38-darwin.so
       0x1138de000 -        0x1138e9fff pixelarray.cpython-38-darwin.so (*) <6939f3aa-b04e-352e-bf82-f1135ef2e1ca> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/pixelarray.cpython-38-darwin.so
       0x1138f6000 -        0x113905fff transform.cpython-38-darwin.so (*) <41703246-49c0-39e3-b136-10fff5513d67> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/transform.cpython-38-darwin.so
       0x11388e000 -        0x113891fff font.cpython-38-darwin.so (*) <9d696773-adf5-3a82-84df-d9187d96d68f> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/font.cpython-38-darwin.so
       0x113d63000 -        0x113ee2fff libSDL2_ttf-2.0.0.dylib (*) <4a37c130-391c-3006-a9f7-036dbf861d1b> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libSDL2_ttf-2.0.0.dylib
       0x113912000 -        0x113915fff mixer_music.cpython-38-darwin.so (*) <c5d4cb43-4bff-3855-95bb-98d11e309842> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/mixer_music.cpython-38-darwin.so
       0x113b78000 -        0x113b9bfff libSDL2_mixer-2.0.0.dylib (*) <603d86df-3794-3a09-8096-d14082d0bbb4> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libSDL2_mixer-2.0.0.dylib
       0x113c2d000 -        0x113c88fff libfluidsynth.3.1.1.dylib (*) <e792305a-fe66-31cf-adc8-e2d74a0b2a46> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libfluidsynth.3.1.1.dylib
       0x113922000 -        0x113929fff libvorbisfile.3.3.8.dylib (*) <22f47dc1-9b68-3229-b52c-dffc0dc7fce8> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libvorbisfile.3.3.8.dylib
       0x113d01000 -        0x113d38fff libFLAC.8.dylib (*) <b8cbb2d1-babf-3c76-b7ef-6d60222523a6> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libFLAC.8.dylib
       0x113f8f000 -        0x113fd2fff libmpg123.0.dylib (*) <3c7c6207-ab84-32e0-b0ba-ea19adabacbb> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libmpg123.0.dylib
       0x113b51000 -        0x113b5cfff libopusfile.0.dylib (*) <247e5173-dc52-3626-80be-38e01e5279bc> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libopusfile.0.dylib
       0x113b38000 -        0x113b3ffff libogg.0.8.5.dylib (*) <fc6f6d2c-48b2-3c1e-a267-fab4be014899> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libogg.0.8.5.dylib
       0x11407d000 -        0x1140e8fff libopus.0.dylib (*) <de396a48-7b9d-30a1-9a7d-334ff52a53f0> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libopus.0.dylib
       0x113bb8000 -        0x113bbbfff libgthread-2.0.0.dylib (*) <05dc54cb-51e6-308c-a740-d0471edb88de> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libgthread-2.0.0.dylib
       0x1142ae000 -        0x114419fff libglib-2.0.0.dylib (*) <79e5be28-7cde-3487-9ac5-077074cc4b59> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libglib-2.0.0.dylib
       0x11419c000 -        0x114213fff libsndfile.1.0.34.dylib (*) <80f71c72-b85c-35a2-afc8-f1ec36649b79> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libsndfile.1.0.34.dylib
       0x113fef000 -        0x114026fff libvorbis.0.4.9.dylib (*) <225af95d-d834-3f10-a226-63d3e5488666> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libvorbis.0.4.9.dylib
       0x114506000 -        0x114581fff libvorbisenc.2.0.12.dylib (*) <036c7df4-d5c3-34f8-8ed2-6e94e4ff5466> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libvorbisenc.2.0.12.dylib
       0x113bc8000 -        0x113bcffff mixer.cpython-38-darwin.so (*) <cee9f73b-8ba2-379a-b40b-e5f96cf1a1a4> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/mixer.cpython-38-darwin.so
       0x113be0000 -        0x113be3fff scrap.cpython-38-darwin.so (*) <490f8eaf-9f18-3f17-a209-a1911fa43db3> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/pygame/scrap.cpython-38-darwin.so
       0x115caa000 -        0x115deefff com.apple.audio.units.Components (1.14) <d45baf6b-bdb1-3f52-9b15-c055dd9f46b0> /System/Library/Components/CoreAudio.component/Contents/MacOS/CoreAudio
       0x1172b6000 -        0x117c7bfff com.apple.audio.AudioDSPComponents (1.0) <1d34a6e7-3311-3552-bfc2-cb375e80a7fe> /System/Library/Components/AudioDSP.component/Contents/MacOS/AudioDSP
       0x114152000 -        0x11415dfff _sqlite3.cpython-38-darwin.so (*) <de8d22c3-93fb-3522-89d4-7b5df4fbbd5a> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/lib-dynload/_sqlite3.cpython-38-darwin.so
       0x115af2000 -        0x115bf9fff libsqlite3.0.dylib (*) <4c2dc9a4-551e-370d-a8ba-35d749eee550> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/libsqlite3.0.dylib
       0x1159ba000 -        0x1159fdfff _yaml.cpython-38-darwin.so (*) <e8f2f899-f8e7-3e97-b110-3d44d112a98f> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/yaml/_yaml.cpython-38-darwin.so
       0x1160e6000 -        0x116250fff libqcocoa.dylib (*) <c4257303-d1d5-356c-9ab8-2de480bd1008> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/platforms/libqcocoa.dylib
       0x115c2a000 -        0x115c88fff QtDBus (*) <4e77489b-7f46-3781-a8b5-dc5a24ef9c2e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtDBus
       0x115a6f000 -        0x115a98fff QtPrintSupport (*) <d9165c00-1902-3a63-ac8d-8554a72de298> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/QtPrintSupport
       0x11725d000 -        0x117280fff libqmacstyle.dylib (*) <0fcc2cd4-79f3-3a39-a04b-d1804113749f> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/styles/libqmacstyle.dylib
       0x115ac2000 -        0x115ac7fff libqsvg.dylib (*) <1fc1d480-89de-391c-bda4-46e0ede5480e> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqsvg.dylib
       0x115ad1000 -        0x115ad8fff libqgif.dylib (*) <24e9eb93-2c89-307b-a55f-af1b2fe3d0f1> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqgif.dylib
       0x1160cf000 -        0x1160d6fff libqicns.dylib (*) <dddab091-c000-3c01-b4b6-61003e4412f4> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqicns.dylib
       0x115ae2000 -        0x115ae7fff libqico.dylib (*) <fbffa067-f740-3e67-b39b-5ce626478c5d> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqico.dylib
       0x122313000 -        0x1223b3fff libqjpeg.dylib (*) <cd0e2998-0bda-38ca-97b3-5df4890e133d> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqjpeg.dylib
       0x117297000 -        0x11729cfff libqmacheif.dylib (*) <447ff0f4-fa10-356c-bf51-5dc6d4303433> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqmacheif.dylib
       0x1172a6000 -        0x1172abfff libqmacjp2.dylib (*) <87abdc9e-50f3-3d07-9c69-537dc83b06bd> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqmacjp2.dylib
       0x122267000 -        0x12226bfff libqtga.dylib (*) <f1b7fe14-b817-3c2c-b307-2bbbdec0e055> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqtga.dylib
       0x1223c1000 -        0x122430fff libqtiff.dylib (*) <91f4297c-c049-3c56-8a79-552cf5be4fb9> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqtiff.dylib
       0x122275000 -        0x122279fff libqwbmp.dylib (*) <c1c9027c-e3c9-3b6a-aa95-5791b605a112> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqwbmp.dylib
       0x1224ee000 -        0x12258efff libqwebp.dylib (*) <25401bd0-2246-3265-a81f-280634123590> /Users/USER/Downloads/*/Class Widgets.app/Contents/Frameworks/PyQt5/Qt5/plugins/imageformats/libqwebp.dylib
       0x115a58000 -        0x115a64fff libobjc-trampolines.dylib (*) <6cd1b595-3b5f-3166-9a4f-5abfb45b87eb> /usr/lib/libobjc-trampolines.dylib
    0x7ff806c72000 -     0x7ff806cadfff libsystem_kernel.dylib (*) <c214d771-f6a3-30be-b657-b4e0cb81c9df> /usr/lib/system/libsystem_kernel.dylib
    0x7ff806cae000 -     0x7ff806cb9fff libsystem_pthread.dylib (*) <2b452c39-67e1-3f73-87ca-5e07d5f1e90d> /usr/lib/system/libsystem_pthread.dylib
    0x7ff80691f000 -     0x7ff8069aac7f dyld (*) <f2913392-361a-304f-b30d-486be5639e2d> /usr/lib/dyld
               0x0 - 0xffffffffffffffff ??? (*) <00000000-0000-0000-0000-000000000000> ???
    0x7ff8120bb000 -     0x7ff8120defff com.apple.audio.caulk (1.0) <f63e19d9-7ba1-3630-95cc-64ebd540564c> /System/Library/PrivateFrameworks/caulk.framework/Versions/A/caulk
    0x7ff806d1f000 -     0x7ff8071bcfe2 com.apple.CoreFoundation (6.9) <404c409f-d28c-309d-ade3-f0ee6f1ca33d> /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
    0x7ff817658000 -     0x7ff81768cfff libAudioToolboxUtility.dylib (*) <6dcf7c3b-8372-3de6-b0aa-d1172a3f7d57> /usr/lib/libAudioToolboxUtility.dylib
    0x7ff8189ae000 -     0x7ff818b47ff5 com.apple.audio.toolbox.AudioToolbox (1.14) <208b183c-8587-3205-938b-94833ad84f61> /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
    0x7ff80945b000 -     0x7ff809ba5ff0 com.apple.audio.CoreAudio (5.0) <15f9185f-dd75-3d1e-98b0-7a8cb484ba9c> /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
    0x7ff806b54000 -     0x7ff806bdcff7 libsystem_c.dylib (*) <12e8dc9e-ee00-37e7-8830-dc84a6de23b1> /usr/lib/system/libsystem_c.dylib
    0x7ff806c5a000 -     0x7ff806c71fff libc++abi.dylib (*) <772cbc4b-017a-3016-815a-35bc9b8ad230> /usr/lib/libc++abi.dylib
    0x7ff8068dc000 -     0x7ff80691efcb libobjc.A.dylib (*) <d15ff8c9-a533-3094-8650-bc97d3c883b9> /usr/lib/libobjc.A.dylib
    0x7ff80d714000 -     0x7ff80d779ffa com.apple.HIServices (1.22) <f4d81a83-a4c8-370a-b62a-3ad58296c9f8> /System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/Versions/A/HIServices
    0x7ff807d76000 -     0x7ff808ba6ff3 com.apple.Foundation (6.9) <ff5888c8-5530-389a-b032-c6aa06e6d180> /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
    0x7ff80a6bb000 -     0x7ff80bbb5ff7 com.apple.AppKit (6.9) <e3f76bb8-4950-3c7a-8aa7-8516a93aeeb9> /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

External Modification Summary:
  Calls made by other processes targeting this process:
    task_for_pid: 0
    thread_create: 0
    thread_set_state: 0
  Calls made by this process:
    task_for_pid: 0
    thread_create: 0
    thread_set_state: 0
  Calls made by all processes on this machine:
    task_for_pid: 9
    thread_create: 0
    thread_set_state: 0

VM Region Summary:
ReadOnly portion of Libraries: Total=1.0G resident=0K(0%) swapped_out_or_unallocated=1.0G(100%)
Writable regions: Total=673.5M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=673.5M(100%)

                                VIRTUAL   REGION 
REGION TYPE                        SIZE    COUNT (non-coalesced) 
===========                     =======  ======= 
Activity Tracing                   256K        1 
ColorSync                          224K       26 
CoreServices                        88K        1 
Foundation                          16K        1 
Kernel Alloc Once                    8K        1 
MALLOC                           620.9M       70 
MALLOC guard page                   48K       12 
MALLOC_LARGE (reserved)            384K        2         reserved VM address space (unallocated)
STACK GUARD                       56.0M       12 
Stack                             13.6M       12 
VM_ALLOCATE                       37.5M      125 
VM_ALLOCATE (reserved)              32K        1         reserved VM address space (unallocated)
__CTF                               824        1 
__DATA                            26.5M      805 
__DATA_CONST                      71.4M      733 
__DATA_DIRTY                      1753K      243 
__FONT_DATA                        2352        1 
__LINKEDIT                       206.6M      140 
__OBJC_RO                         76.9M        1 
__OBJC_RW                         2375K        3 
__TEXT                           845.0M      828 
__TPRO_CONST                       272K        2 
mapped file                      214.9M       23 
owned unmapped memory               36K        1 
shared memory                     1380K       19 
===========                     =======  ======= 
TOTAL                              2.1G     3064 
TOTAL, minus reserved VM space     2.1G     3064 



-----------
Full Report
-----------

{"app_name":"Class Widgets","timestamp":"2025-04-11 16:51:58.00 +0800","app_version":"0.0.0","slice_uuid":"f0258b48-b4f2-3f50-8165-65c85abc9adc","build_version":"","platform":1,"bundleID":"Class Widgets","share_with_app_devs":0,"is_first_party":0,"bug_type":"309","os_version":"macOS 15.3.2 (24D81)","roots_installed":0,"name":"Class Widgets","incident_id":"8CBEE275-CBF5-4B9D-8808-7DC73D65D6D7"}
{
  "uptime" : 33000,
  "procRole" : "Background",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "MacBookPro15,4",
  "coalitionID" : 5311,
  "osVersion" : {
    "train" : "macOS 15.3.2",
    "build" : "24D81",
    "releaseType" : "User"
  },
  "captureTime" : "2025-04-11 16:51:29.0839 +0800",
  "codeSigningMonitor" : 0,
  "incident" : "8CBEE275-CBF5-4B9D-8808-7DC73D65D6D7",
  "pid" : 12744,
  "cpuType" : "X86-64",
  "roots_installed" : 0,
  "bug_type" : "309",
  "procLaunch" : "2025-04-11 16:51:25.7063 +0800",
  "procStartAbsTime" : 33545936844694,
  "procExitAbsTime" : 33549300497374,
  "procName" : "Class Widgets",
  "procPath" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/MacOS\/Class Widgets",
  "bundleInfo" : {"CFBundleShortVersionString":"0.0.0","CFBundleIdentifier":"Class Widgets"},
  "storeInfo" : {"deviceIdentifierForVendor":"1D94AF4A-51E4-5508-AD6E-67759A2BC2C4","thirdParty":true},
  "parentProc" : "zsh",
  "parentPid" : 12728,
  "coalitionName" : "com.apple.Terminal",
  "crashReporterKey" : "526C3592-2EAD-ADB2-7CE8-9CEF7D720D80",
  "lowPowerMode" : 1,
  "responsiblePid" : 10247,
  "responsibleProc" : "Terminal",
  "codeSigningID" : "Class Widgets",
  "codeSigningTeamID" : "",
  "codeSigningFlags" : 570425345,
  "codeSigningValidationCategory" : 10,
  "codeSigningTrustLevel" : 4294967295,
  "bootSessionUUID" : "0F02E7AD-AE29-45EA-85EA-19B5F4FE598D",
  "wakeTime" : 601,
  "bridgeVersion" : {"build":"22P3060","train":"9.3"},
  "sleepWakeUUID" : "25A2F530-C0BD-4608-A716-26148098E9B6",
  "sip" : "enabled",
  "exception" : {"codes":"0x0000000000000000, 0x0000000000000000","rawCodes":[0,0],"type":"EXC_CRASH","signal":"SIGABRT"},
  "termination" : {"flags":0,"code":6,"namespace":"SIGNAL","indicator":"Abort trap: 6","byProc":"Class Widgets","byPid":12744},
  "asi" : {"libsystem_c.dylib":["abort() called"]},
  "extMods" : {"caller":{"thread_create":0,"thread_set_state":0,"task_for_pid":0},"system":{"thread_create":0,"thread_set_state":0,"task_for_pid":9},"targeted":{"thread_create":0,"thread_set_state":0,"task_for_pid":0},"warnings":0},
  "lastExceptionBacktrace" : [{"imageOffset":967446,"symbol":"__exceptionPreprocess","symbolLocation":226,"imageIndex":144},{"imageOffset":84944,"symbol":"objc_exception_throw","symbolLocation":62,"imageIndex":150},{"imageOffset":1110708,"symbol":"-[NSException raise]","symbolLocation":9,"imageIndex":144},{"imageOffset":348454,"symbol":"-[NSWindow _initContent:styleMask:backing:defer:contentView:]","symbolLocation":1653,"imageIndex":153},{"imageOffset":1968145,"symbol":"-[NSPanel _initContent:styleMask:backing:defer:contentView:]","symbolLocation":50,"imageIndex":153},{"imageOffset":346793,"symbol":"-[NSWindow initWithContentRect:styleMask:backing:defer:]","symbolLocation":42,"imageIndex":153},{"imageOffset":1968074,"symbol":"-[NSPanel initWithContentRect:styleMask:backing:defer:]","symbolLocation":59,"imageIndex":153},{"imageOffset":3195738,"symbol":"-[NSWindow initWithContentRect:styleMask:backing:defer:screen:]","symbolLocation":50,"imageIndex":153},{"imageOffset":238452,"imageIndex":123},{"imageOffset":149880,"imageIndex":123},{"imageOffset":120985,"imageIndex":123},{"imageOffset":119559,"imageIndex":123},{"imageOffset":277554,"symbol":"QWindowPrivate::create(bool, unsigned long long)","symbolLocation":146,"imageIndex":43},{"imageOffset":238549,"symbol":"QWidgetPrivate::create()","symbolLocation":1061,"imageIndex":46},{"imageOffset":233685,"symbol":"QWidget::create(unsigned long long, bool, bool)","symbolLocation":325,"imageIndex":46},{"imageOffset":240977,"symbol":"QWidget::winId() const","symbolLocation":65,"imageIndex":46},{"imageOffset":2443081,"symbol":"meth_QWidget_winId(_object*, _object*)","symbolLocation":89,"imageIndex":47},{"imageOffset":199381,"symbol":"cfunction_call_varargs","symbolLocation":197,"imageIndex":1},{"imageOffset":196700,"symbol":"_PyObject_MakeTpCall","symbolLocation":188,"imageIndex":1},{"imageOffset":1486386,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":31426,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1480379,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":25419,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1480379,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":25419,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1474769,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":19809,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1480379,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":25419,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":195919,"symbol":"_PyObject_FastCallDict","symbolLocation":79,"imageIndex":1},{"imageOffset":754659,"symbol":"slot_tp_init","symbolLocation":179,"imageIndex":1},{"imageOffset":802329,"symbol":"type_call","symbolLocation":297,"imageIndex":1},{"imageOffset":196700,"symbol":"_PyObject_MakeTpCall","symbolLocation":188,"imageIndex":1},{"imageOffset":1482077,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":27117,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":1959920,"symbol":"_PyObject_Vectorcall.5458","symbolLocation":48,"imageIndex":1},{"imageOffset":1958640,"symbol":"_PyErr_PrintEx","symbolLocation":464,"imageIndex":1},{"imageOffset":1228042,"symbol":"pyqt5_err_print()","symbolLocation":122,"imageIndex":32},{"imageOffset":34979,"symbol":"sip_api_call_procedure_method","symbolLocation":243,"imageIndex":34},{"imageOffset":127164,"symbol":"sipQThread::run()","symbolLocation":92,"imageIndex":32},{"imageOffset":131315,"imageIndex":33},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}],
  "faultingThread" : 10,
  "threads" : [{"id":694835,"threadState":{"r13":{"value":105557411258624},"rax":{"value":260},"rflags":{"value":2097735},"cpu":{"value":0},"r14":{"value":140704363875072,"symbolLocation":0,"symbol":"_main_thread"},"rsi":{"value":105557411258624},"r8":{"value":0},"cr2":{"value":0},"rdx":{"value":19712},"r10":{"value":0},"r9":{"value":160},"r15":{"value":19712},"rbx":{"value":22},"trap":{"value":133},"err":{"value":33554737},"r11":{"value":2097734},"rip":{"value":140703242345130},"rbp":{"value":140701846324592},"rsp":{"value":140701846324440},"r12":{"value":4992000},"rcx":{"value":140701846324440},"flavor":"x86_THREAD_STATE","rdi":{"value":4516095752,"symbolLocation":1184,"symbol":"_PyRuntime"}},"queue":"com.apple.main-thread","frames":[{"imageOffset":15018,"symbol":"__psynch_cvwait","symbolLocation":10,"imageIndex":139},{"imageOffset":26536,"symbol":"_pthread_cond_wait","symbolLocation":1193,"imageIndex":140},{"imageOffset":1443743,"symbol":"take_gil","symbolLocation":591,"imageIndex":1},{"imageOffset":1950627,"symbol":"PyGILState_Ensure","symbolLocation":131,"imageIndex":1},{"imageOffset":51025,"symbol":"sip_api_is_py_method_12_8","symbolLocation":65,"imageIndex":34},{"imageOffset":302829,"symbol":"sipQFile::readData(char*, long long)","symbolLocation":61,"imageIndex":32},{"imageOffset":1253483,"symbol":"QIODevicePrivate::read(char*, long long, bool)","symbolLocation":571,"imageIndex":33},{"imageOffset":1255588,"symbol":"QIODevice::readAll()","symbolLocation":356,"imageIndex":33},{"imageOffset":1077574,"symbol":"meth_QIODevice_readAll(_object*, _object*)","symbolLocation":102,"imageIndex":32},{"imageOffset":199381,"symbol":"cfunction_call_varargs","symbolLocation":197,"imageIndex":1},{"imageOffset":196700,"symbol":"_PyObject_MakeTpCall","symbolLocation":188,"imageIndex":1},{"imageOffset":1486386,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":31426,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":1474870,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":19910,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":1476247,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":21287,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":1474870,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":19910,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":1474870,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":19910,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":1476247,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":21287,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1480379,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":25419,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":196034,"symbol":"_PyObject_FastCallDict","symbolLocation":194,"imageIndex":1},{"imageOffset":754659,"symbol":"slot_tp_init","symbolLocation":179,"imageIndex":1},{"imageOffset":802329,"symbol":"type_call","symbolLocation":297,"imageIndex":1},{"imageOffset":196700,"symbol":"_PyObject_MakeTpCall","symbolLocation":188,"imageIndex":1},{"imageOffset":1482036,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":27076,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":216398,"symbol":"method_vectorcall","symbolLocation":142,"imageIndex":1},{"imageOffset":1480379,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":25419,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":201370,"symbol":"_PyFunction_Vectorcall","symbolLocation":426,"imageIndex":1},{"imageOffset":195919,"symbol":"_PyObject_FastCallDict","symbolLocation":79,"imageIndex":1},{"imageOffset":754659,"symbol":"slot_tp_init","symbolLocation":179,"imageIndex":1},{"imageOffset":802329,"symbol":"type_call","symbolLocation":297,"imageIndex":1},{"imageOffset":196700,"symbol":"_PyObject_MakeTpCall","symbolLocation":188,"imageIndex":1},{"imageOffset":1482077,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":27117,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":1476247,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":21287,"imageIndex":1},{"imageOffset":201189,"symbol":"_PyFunction_Vectorcall","symbolLocation":245,"imageIndex":1},{"imageOffset":1474870,"symbol":"_PyEval_EvalFrameDefault","symbolLocation":19910,"imageIndex":1},{"imageOffset":1447169,"symbol":"_PyEval_EvalCodeWithName","symbolLocation":561,"imageIndex":1},{"imageOffset":1446595,"symbol":"PyEval_EvalCode","symbolLocation":51,"imageIndex":1},{"imageOffset":13812,"imageIndex":0},{"imageOffset":16405,"imageIndex":0},{"imageOffset":25293,"symbol":"start","symbolLocation":1805,"imageIndex":141}]},{"id":694847,"frames":[{"imageOffset":7116,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":140}],"threadState":{"r13":{"value":0},"rax":{"value":33554800},"rflags":{"value":512},"cpu":{"value":0},"r14":{"value":0},"rsi":{"value":4355},"r8":{"value":409603},"cr2":{"value":0},"rdx":{"value":123145566429184},"r10":{"value":0},"r9":{"value":18446744073709551615},"r15":{"value":0},"rbx":{"value":123145566953472},"trap":{"value":133},"err":{"value":33554800},"r11":{"value":582},"rip":{"value":140703242582988},"rbp":{"value":0},"rsp":{"value":123145566953472},"r12":{"value":0},"rcx":{"value":0},"flavor":"x86_THREAD_STATE","rdi":{"value":123145566953472}}},{"id":694848,"frames":[{"imageOffset":7116,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":140}],"threadState":{"r13":{"value":0},"rax":{"value":33554800},"rflags":{"value":512},"cpu":{"value":0},"r14":{"value":1},"rsi":{"value":5635},"r8":{"value":409604},"cr2":{"value":0},"rdx":{"value":123145566965760},"r10":{"value":0},"r9":{"value":18446744073709551615},"r15":{"value":123145567488896},"rbx":{"value":123145567490048},"trap":{"value":133},"err":{"value":33554800},"r11":{"value":582},"rip":{"value":140703242582988},"rbp":{"value":0},"rsp":{"value":123145567490048},"r12":{"value":1966080},"rcx":{"value":0},"flavor":"x86_THREAD_STATE","rdi":{"value":123145567490048}}},{"id":694859,"name":"caulk.messenger.shared:17","threadState":{"r13":{"value":0},"rax":{"value":14},"rflags":{"value":515},"cpu":{"value":0},"r14":{"value":105553173644128},"rsi":{"value":105553130758272},"r8":{"value":105553130758272},"cr2":{"value":0},"rdx":{"value":10},"r10":{"value":0},"r9":{"value":25},"r15":{"value":0},"rbx":{"value":105553173644033},"trap":{"value":133},"err":{"value":16777252},"r11":{"value":515},"rip":{"value":140703242333834},"rbp":{"value":123145568026480},"rsp":{"value":123145568026440},"r12":{"value":0},"rcx":{"value":123145568026440},"flavor":"x86_THREAD_STATE","rdi":{"value":9995}},"frames":[{"imageOffset":3722,"symbol":"semaphore_wait_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":7325,"symbol":"caulk::semaphore::timed_wait(double)","symbolLocation":151,"imageIndex":143},{"imageOffset":7112,"symbol":"caulk::concurrent::details::worker_thread::run()","symbolLocation":30,"imageIndex":143},{"imageOffset":6410,"symbol":"void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*)","symbolLocation":41,"imageIndex":143},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694860,"name":"caulk.messenger.shared:high","threadState":{"r13":{"value":0},"rax":{"value":14},"rflags":{"value":515},"cpu":{"value":0},"r14":{"value":105553173532144},"rsi":{"value":11267},"r8":{"value":4294967295},"cr2":{"value":0},"rdx":{"value":11267},"r10":{"value":18},"r9":{"value":0},"r15":{"value":0},"rbx":{"value":105553173531905},"trap":{"value":133},"err":{"value":16777252},"r11":{"value":515},"rip":{"value":140703242333834},"rbp":{"value":123145568563056},"rsp":{"value":123145568563016},"r12":{"value":0},"rcx":{"value":123145568563016},"flavor":"x86_THREAD_STATE","rdi":{"value":11011}},"frames":[{"imageOffset":3722,"symbol":"semaphore_wait_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":7325,"symbol":"caulk::semaphore::timed_wait(double)","symbolLocation":151,"imageIndex":143},{"imageOffset":7112,"symbol":"caulk::concurrent::details::worker_thread::run()","symbolLocation":30,"imageIndex":143},{"imageOffset":6410,"symbol":"void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*)","symbolLocation":41,"imageIndex":143},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694906,"name":"AudioQueue thread","threadState":{"r13":{"value":21592279046},"rax":{"value":268451845},"rflags":{"value":518},"cpu":{"value":0},"r14":{"value":2},"rsi":{"value":21592279046},"r8":{"value":59442896},"cr2":{"value":0},"rdx":{"value":8589934592},"r10":{"value":186929861623808},"r9":{"value":186929861623808},"r15":{"value":186929861623808},"rbx":{"value":123145569095648},"trap":{"value":133},"err":{"value":16777263},"r11":{"value":518},"rip":{"value":140703242333966},"rbp":{"value":123145569095488},"rsp":{"value":123145569095384},"r12":{"value":4294967295},"rcx":{"value":123145569095384},"flavor":"x86_THREAD_STATE","rdi":{"value":123145569095648}},"frames":[{"imageOffset":3854,"symbol":"mach_msg2_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":62970,"symbol":"mach_msg2_internal","symbolLocation":84,"imageIndex":139},{"imageOffset":32790,"symbol":"mach_msg_overwrite","symbolLocation":649,"imageIndex":139},{"imageOffset":4607,"symbol":"mach_msg","symbolLocation":19,"imageIndex":139},{"imageOffset":507362,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":143,"imageIndex":144},{"imageOffset":501775,"symbol":"__CFRunLoopRun","symbolLocation":1393,"imageIndex":144},{"imageOffset":498798,"symbol":"CFRunLoopRunSpecific","symbolLocation":550,"imageIndex":144},{"imageOffset":1234706,"symbol":"audioqueue_thread","symbolLocation":1090,"imageIndex":71},{"imageOffset":523372,"symbol":"SDL_RunThread","symbolLocation":44,"imageIndex":71},{"imageOffset":1128953,"symbol":"RunThread","symbolLocation":9,"imageIndex":71},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694907,"name":"caulk::deferred_logger","threadState":{"r13":{"value":0},"rax":{"value":14},"rflags":{"value":515},"cpu":{"value":0},"r14":{"value":105553171563000},"rsi":{"value":105553160005569},"r8":{"value":105553160005569},"cr2":{"value":0},"rdx":{"value":7},"r10":{"value":1},"r9":{"value":22},"r15":{"value":0},"rbx":{"value":105553171562753},"trap":{"value":133},"err":{"value":16777252},"r11":{"value":515},"rip":{"value":140703242333834},"rbp":{"value":123145569636208},"rsp":{"value":123145569636168},"r12":{"value":0},"rcx":{"value":123145569636168},"flavor":"x86_THREAD_STATE","rdi":{"value":62979}},"frames":[{"imageOffset":3722,"symbol":"semaphore_wait_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":7325,"symbol":"caulk::semaphore::timed_wait(double)","symbolLocation":151,"imageIndex":143},{"imageOffset":7112,"symbol":"caulk::concurrent::details::worker_thread::run()","symbolLocation":30,"imageIndex":143},{"imageOffset":6410,"symbol":"void* caulk::thread_proxy<std::__1::tuple<caulk::thread::attributes, void (caulk::concurrent::details::worker_thread::*)(), std::__1::tuple<caulk::concurrent::details::worker_thread*>>>(void*)","symbolLocation":41,"imageIndex":143},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694915,"name":"AQConverterThread","threadState":{"r13":{"value":168229574056448},"rax":{"value":260},"rflags":{"value":583},"cpu":{"value":0},"r14":{"value":123145570172928},"rsi":{"value":168229574056448},"r8":{"value":0},"cr2":{"value":0},"rdx":{"value":39168},"r10":{"value":0},"r9":{"value":160},"r15":{"value":39168},"rbx":{"value":22},"trap":{"value":133},"err":{"value":33554737},"r11":{"value":582},"rip":{"value":140703242345130},"rbp":{"value":123145570172624},"rsp":{"value":123145570172472},"r12":{"value":0},"rcx":{"value":123145570172472},"flavor":"x86_THREAD_STATE","rdi":{"value":140595955579496}},"frames":[{"imageOffset":15018,"symbol":"__psynch_cvwait","symbolLocation":10,"imageIndex":139},{"imageOffset":26536,"symbol":"_pthread_cond_wait","symbolLocation":1193,"imageIndex":140},{"imageOffset":187570,"symbol":"CADeprecated::CAGuard::Wait()","symbolLocation":68,"imageIndex":145},{"imageOffset":167284,"symbol":"AQConverterManager::AQConverterThread::ConverterThreadEntry(void*)","symbolLocation":578,"imageIndex":146},{"imageOffset":54423,"symbol":"CADeprecated::CAPThread::Entry(void*)","symbolLocation":77,"imageIndex":145},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694916,"name":"com.apple.audio.IOThread.client","threadState":{"r13":{"value":0},"rax":{"value":14},"rflags":{"value":514},"cpu":{"value":0},"r14":{"value":140595982435096},"rsi":{"value":47363},"r8":{"value":0},"cr2":{"value":0},"rdx":{"value":1099511628032},"r10":{"value":140595982434872},"r9":{"value":0},"r15":{"value":1},"rbx":{"value":140595982435104},"trap":{"value":133},"err":{"value":16777253},"r11":{"value":514},"rip":{"value":140703242333846},"rbp":{"value":123145570708736},"rsp":{"value":123145570708712},"r12":{"value":140595982434816},"rcx":{"value":123145570708712},"flavor":"x86_THREAD_STATE","rdi":{"value":47107}},"frames":[{"imageOffset":3734,"symbol":"semaphore_wait_signal_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":111381,"symbol":"caulk::mach::semaphore::wait_signal_or_error(caulk::mach::semaphore&)","symbolLocation":23,"imageIndex":143},{"imageOffset":1997797,"symbol":"HALC_ProxyIOContext::IOWorkLoop()","symbolLocation":5515,"imageIndex":147},{"imageOffset":1990236,"symbol":"invocation function for block in HALC_ProxyIOContext::HALC_ProxyIOContext(unsigned int, unsigned int)","symbolLocation":148,"imageIndex":147},{"imageOffset":3764203,"symbol":"HALC_IOThread::Entry(void*)","symbolLocation":73,"imageIndex":147},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694928,"frames":[{"imageOffset":7116,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":140}],"threadState":{"r13":{"value":0},"rax":{"value":33554800},"rflags":{"value":512},"cpu":{"value":0},"r14":{"value":0},"rsi":{"value":58375},"r8":{"value":409603},"cr2":{"value":0},"rdx":{"value":123145570721792},"r10":{"value":0},"r9":{"value":18446744073709551615},"r15":{"value":0},"rbx":{"value":123145571246080},"trap":{"value":133},"err":{"value":33554800},"r11":{"value":582},"rip":{"value":140703242582988},"rbp":{"value":0},"rsp":{"value":123145571246080},"r12":{"value":0},"rcx":{"value":0},"flavor":"x86_THREAD_STATE","rdi":{"value":123145571246080}}},{"triggered":true,"id":694949,"name":"SystemThemeListener","threadState":{"r13":{"value":206158430216},"rax":{"value":0},"rflags":{"value":582},"cpu":{"value":0},"r14":{"value":68615},"rsi":{"value":6},"r8":{"value":123145571781648},"cr2":{"value":0},"rdx":{"value":0},"r10":{"value":0},"r9":{"value":18446744073709551615},"r15":{"value":22},"rbx":{"value":6},"trap":{"value":133},"err":{"value":33554760},"r11":{"value":582},"rip":{"value":140703242361938,"matchesCrashFrame":1},"rbp":{"value":123145571782000},"rsp":{"value":123145571781960},"r12":{"value":140704365881856,"symbolLocation":0,"symbol":"__stderrp"},"rcx":{"value":123145571781960},"flavor":"x86_THREAD_STATE","rdi":{"value":68615}},"frames":[{"imageOffset":31826,"symbol":"__pthread_kill","symbolLocation":10,"imageIndex":139},{"imageOffset":24453,"symbol":"pthread_kill","symbolLocation":262,"imageIndex":140},{"imageOffset":527129,"symbol":"abort","symbolLocation":126,"imageIndex":148},{"imageOffset":69987,"symbol":"abort_message","symbolLocation":258,"imageIndex":149},{"imageOffset":8398,"symbol":"demangling_terminate_handler()","symbolLocation":266,"imageIndex":149},{"imageOffset":118113,"symbol":"_objc_terminate()","symbolLocation":96,"imageIndex":150},{"imageOffset":66875,"symbol":"std::__terminate(void (*)())","symbolLocation":6,"imageIndex":149},{"imageOffset":66806,"symbol":"std::terminate()","symbolLocation":54,"imageIndex":149},{"imageOffset":131701,"imageIndex":33},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]},{"id":694957,"name":"HIE: __ d000f42d2d95c51b 2025-04-11 16:51:29.059","threadState":{"r13":{"value":8589934595},"rax":{"value":0},"rflags":{"value":518},"cpu":{"value":0},"r14":{"value":44},"rsi":{"value":8589934595},"r8":{"value":15483357102080},"cr2":{"value":0},"rdx":{"value":103079220499},"r10":{"value":345259536093187},"r9":{"value":345259536023552},"r15":{"value":345259536023552},"rbx":{"value":123145572318476},"trap":{"value":133},"err":{"value":16777263},"r11":{"value":518},"rip":{"value":140703242333966},"rbp":{"value":123145572318432},"rsp":{"value":123145572318328},"r12":{"value":0},"rcx":{"value":123145572318328},"flavor":"x86_THREAD_STATE","rdi":{"value":123145572318476}},"frames":[{"imageOffset":3854,"symbol":"mach_msg2_trap","symbolLocation":10,"imageIndex":139},{"imageOffset":62970,"symbol":"mach_msg2_internal","symbolLocation":84,"imageIndex":139},{"imageOffset":161947,"symbol":"thread_suspend","symbolLocation":83,"imageIndex":139},{"imageOffset":251547,"symbol":"SOME_OTHER_THREAD_SWALLOWED_AT_LEAST_ONE_EXCEPTION","symbolLocation":16,"imageIndex":151},{"imageOffset":349315,"symbol":"__NSThread__start__","symbolLocation":1007,"imageIndex":152},{"imageOffset":25171,"symbol":"_pthread_start","symbolLocation":99,"imageIndex":140},{"imageOffset":7151,"symbol":"thread_start","symbolLocation":15,"imageIndex":140}]}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4502454272,
    "CFBundleShortVersionString" : "0.0.0",
    "CFBundleIdentifier" : "Class Widgets",
    "size" : 49152,
    "uuid" : "f0258b48-b4f2-3f50-8165-65c85abc9adc",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/MacOS\/Class Widgets",
    "name" : "Class Widgets"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4512583680,
    "size" : 3276800,
    "uuid" : "dfe181a3-5091-3fc5-b1e1-9df9ccbb33cf",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libpython3.8.dylib",
    "name" : "libpython3.8.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4508192768,
    "size" : 49152,
    "uuid" : "005712ba-00b8-3168-beae-4e75513dea8e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libintl.8.dylib",
    "name" : "libintl.8.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4509618176,
    "size" : 32768,
    "uuid" : "44fd2f1e-d7ea-3343-baa8-020bab9cfca0",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_struct.cpython-38-darwin.so",
    "name" : "_struct.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4509995008,
    "size" : 32768,
    "uuid" : "6ad16d6d-6bf4-368e-99bd-78e61235a1dd",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/zlib.cpython-38-darwin.so",
    "name" : "zlib.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4510543872,
    "size" : 81920,
    "uuid" : "b65813ac-4bbe-3115-962b-6730220afd9a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_ctypes.cpython-38-darwin.so",
    "name" : "_ctypes.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4510355456,
    "size" : 16384,
    "uuid" : "af41cfc3-36d4-341f-972b-5d2624ae68b7",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_heapq.cpython-38-darwin.so",
    "name" : "_heapq.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4510437376,
    "size" : 32768,
    "uuid" : "d6ed2447-56b7-373f-badd-d53998ac9b10",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/binascii.cpython-38-darwin.so",
    "name" : "binascii.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4512432128,
    "size" : 49152,
    "uuid" : "b91841bb-6be5-3290-8a55-211473581636",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/math.cpython-38-darwin.so",
    "name" : "math.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4512313344,
    "size" : 16384,
    "uuid" : "cdec3ef8-508b-34ac-bd49-4e7e0c656b15",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_bisect.cpython-38-darwin.so",
    "name" : "_bisect.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4517220352,
    "size" : 32768,
    "uuid" : "b0e1ac5c-a5e4-39c0-b686-9c4b3acb4705",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_sha512.cpython-38-darwin.so",
    "name" : "_sha512.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4517318656,
    "size" : 16384,
    "uuid" : "2fc78912-2b50-3f6d-be7f-77d1242c4b21",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_random.cpython-38-darwin.so",
    "name" : "_random.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4517806080,
    "size" : 65536,
    "uuid" : "7a61b276-9177-3f4b-a091-132ea1408005",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_socket.cpython-38-darwin.so",
    "name" : "_socket.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4517662720,
    "size" : 16384,
    "uuid" : "3557257a-0764-3705-88a4-436d4bc718cb",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/select.cpython-38-darwin.so",
    "name" : "select.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4518367232,
    "size" : 65536,
    "uuid" : "59013994-caf9-3bbb-bbc3-527e0ba965f4",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_datetime.cpython-38-darwin.so",
    "name" : "_datetime.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4518215680,
    "size" : 16384,
    "uuid" : "cfc88a86-37d4-3e53-98fe-1c53422997d5",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_opcode.cpython-38-darwin.so",
    "name" : "_opcode.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4519612416,
    "size" : 180224,
    "uuid" : "a92ce866-3fc9-30c5-82ae-af9320412037",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/pyexpat.cpython-38-darwin.so",
    "name" : "pyexpat.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4520169472,
    "size" : 16384,
    "uuid" : "393f45ff-1f3a-3f3b-ae5f-0e79406139c3",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_bz2.cpython-38-darwin.so",
    "name" : "_bz2.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4520251392,
    "size" : 32768,
    "uuid" : "c8b62ed4-8ded-3728-b8b8-5e59d6d9f270",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_lzma.cpython-38-darwin.so",
    "name" : "_lzma.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4520538112,
    "size" : 131072,
    "uuid" : "dbab8212-2071-3e7a-b416-ba92b59e8773",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/liblzma.5.dylib",
    "name" : "liblzma.5.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4520349696,
    "size" : 16384,
    "uuid" : "b063b470-ea6f-3249-b4f0-b36cf625e452",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/grp.cpython-38-darwin.so",
    "name" : "grp.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4520431616,
    "size" : 16384,
    "uuid" : "97836b3c-b43e-3b82-b0ce-d580f65cc986",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_posixsubprocess.cpython-38-darwin.so",
    "name" : "_posixsubprocess.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4522569728,
    "size" : 16384,
    "uuid" : "0d64a2c3-634b-35fc-9bde-1856503dfdc8",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_queue.cpython-38-darwin.so",
    "name" : "_queue.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4522913792,
    "size" : 16384,
    "uuid" : "7f05d31b-9421-3a98-bcd0-900125c37be6",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_hashlib.cpython-38-darwin.so",
    "name" : "_hashlib.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4523520000,
    "size" : 327680,
    "uuid" : "6f913138-95a2-33a3-92be-45a5d0b88c88",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libssl.1.1.dylib",
    "name" : "libssl.1.1.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4526493696,
    "size" : 1818624,
    "uuid" : "87e528a0-0329-33e5-a9b7-e37da4569b10",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libcrypto.1.1.dylib",
    "name" : "libcrypto.1.1.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4522995712,
    "size" : 32768,
    "uuid" : "844c484a-248e-395f-a1aa-b56f15a65743",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_blake2.cpython-38-darwin.so",
    "name" : "_blake2.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4523241472,
    "size" : 81920,
    "uuid" : "e8e3dba3-5a0f-3f16-8b5b-15d89fcd5f7a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_sha3.cpython-38-darwin.so",
    "name" : "_sha3.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4524527616,
    "size" : 98304,
    "uuid" : "f56952f5-932b-3cc0-b45e-53e79051bea2",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_ssl.cpython-38-darwin.so",
    "name" : "_ssl.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4523094016,
    "size" : 16384,
    "uuid" : "cfb75b47-766b-3539-827f-01be4f263888",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_scproxy.cpython-38-darwin.so",
    "name" : "_scproxy.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4530540544,
    "size" : 114688,
    "uuid" : "e7065d39-0c91-3be9-a626-19bad35eb838",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_pickle.cpython-38-darwin.so",
    "name" : "_pickle.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4523388928,
    "size" : 32768,
    "uuid" : "e361d37b-7692-3d93-97f3-66a6117dbf9e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/array.cpython-38-darwin.so",
    "name" : "array.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4534112256,
    "size" : 1605632,
    "uuid" : "50e61d65-8075-353a-a072-4648e60cb069",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/QtCore.abi3.so",
    "name" : "QtCore.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4543471616,
    "size" : 5386240,
    "uuid" : "44b06aca-cb6e-34bf-8360-c7b770c43e92",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtCore",
    "name" : "QtCore"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4531015680,
    "size" : 98304,
    "uuid" : "64d78214-7612-323f-8871-2d85aa6287e6",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/sip.cpython-38-darwin.so",
    "name" : "sip.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4524400640,
    "size" : 32768,
    "uuid" : "4b6d01cc-7915-3749-9b43-67f1a703923a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_json.cpython-38-darwin.so",
    "name" : "_json.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4526329856,
    "size" : 32768,
    "uuid" : "f0574b3a-be31-39b7-a45f-a11e86d88084",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_csv.cpython-38-darwin.so",
    "name" : "_csv.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4518297600,
    "size" : 16384,
    "uuid" : "143bfd0a-fbaa-3849-bbaa-9d3b2d44c38f",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/charset_normalizer\/md.cpython-38-darwin.so",
    "name" : "md.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4533542912,
    "size" : 147456,
    "uuid" : "16c06709-1b00-34a5-b632-e21f240da021",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/charset_normalizer\/md__mypyc.cpython-38-darwin.so",
    "name" : "md__mypyc.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4538372096,
    "size" : 1081344,
    "uuid" : "2f381e19-e395-39db-ab40-acd8049f7ed0",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/unicodedata.cpython-38-darwin.so",
    "name" : "unicodedata.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4533411840,
    "size" : 32768,
    "uuid" : "2404461f-f18a-361d-a0b7-68307a652d94",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_multibytecodec.cpython-38-darwin.so",
    "name" : "_multibytecodec.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4538138624,
    "size" : 49152,
    "uuid" : "7a61123a-447d-372d-980a-d8576d5bdb84",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_elementtree.cpython-38-darwin.so",
    "name" : "_elementtree.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4582658048,
    "size" : 1671168,
    "uuid" : "24c335fe-64ec-319b-848a-97ce19425aeb",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/QtGui.abi3.so",
    "name" : "QtGui.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592828416,
    "size" : 5718016,
    "uuid" : "f01340e7-d4fb-3710-8458-e407eac32f30",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtGui",
    "name" : "QtGui"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4540219392,
    "size" : 69632,
    "uuid" : "65e8ddee-e60c-3482-9ad8-bf60789d4eaf",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/QtSvg.abi3.so",
    "name" : "QtSvg.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4540735488,
    "size" : 221184,
    "uuid" : "e3ed66a5-0b14-3059-8305-7ca311d0e457",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtSvg",
    "name" : "QtSvg"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4599758848,
    "size" : 4448256,
    "uuid" : "59fc7134-f414-3077-b2e0-8c20ff66965a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtWidgets",
    "name" : "QtWidgets"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4605730816,
    "size" : 2961408,
    "uuid" : "8a63c017-cfa7-3b76-a5da-8068cfb5a1e2",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/QtWidgets.abi3.so",
    "name" : "QtWidgets.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4533305344,
    "size" : 16384,
    "uuid" : "54cc0bab-3625-3a4a-8667-6b7968c772e1",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_contextvars.cpython-38-darwin.so",
    "name" : "_contextvars.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4540059648,
    "size" : 32768,
    "uuid" : "9a4da124-9002-396b-9d1a-8688048aedda",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_asyncio.cpython-38-darwin.so",
    "name" : "_asyncio.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4543066112,
    "size" : 278528,
    "uuid" : "e5971410-a0f0-3c4d-82c6-d5394402df32",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_decimal.cpython-38-darwin.so",
    "name" : "_decimal.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4587159552,
    "size" : 835584,
    "uuid" : "451d815f-e5af-30e5-a4de-4550ab686df0",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/objc\/_objc.cpython-38-darwin.so",
    "name" : "_objc.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4538003456,
    "size" : 32768,
    "uuid" : "42765bd0-149f-3358-bf3d-4c06d3ade426",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/CoreFoundation\/_CoreFoundation.cpython-38-darwin.so",
    "name" : "_CoreFoundation.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4517744640,
    "size" : 4096,
    "uuid" : "abff7698-e14a-31f4-a188-3c6cc2edf6a5",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/CoreFoundation\/_inlines.cpython-38-darwin.so",
    "name" : "_inlines.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4542935040,
    "size" : 28672,
    "uuid" : "f82d9a83-de87-38c5-96d1-63c723ca8ee2",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Foundation\/_Foundation.cpython-38-darwin.so",
    "name" : "_Foundation.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4524306432,
    "size" : 8192,
    "uuid" : "fab8fecd-0bc6-3d85-b10c-03d647fc039a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Foundation\/_inlines.cpython-38-darwin.so",
    "name" : "_inlines.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592316416,
    "size" : 90112,
    "uuid" : "803739fc-3c74-320e-a588-a98ab65c7156",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/AppKit\/_AppKit.cpython-38-darwin.so",
    "name" : "_AppKit.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4523175936,
    "size" : 4096,
    "uuid" : "55261834-bc74-30a7-b611-8b5df7a35f60",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/AppKit\/_inlines.cpython-38-darwin.so",
    "name" : "_inlines.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4612210688,
    "size" : 167936,
    "uuid" : "f588dd9a-d393-311a-bc4e-a38d6f30dbb1",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/QtXml.abi3.so",
    "name" : "QtXml.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4612575232,
    "size" : 192512,
    "uuid" : "8fa6c55e-50da-3a52-b409-e5dcabcfb816",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtXml",
    "name" : "QtXml"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4538286080,
    "size" : 20480,
    "uuid" : "e534277b-c87c-3cb5-9714-d8e12a91c725",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreGraphics\/_callbacks.cpython-38-darwin.so",
    "name" : "_callbacks.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4524355584,
    "size" : 4096,
    "uuid" : "1c2999a7-38e4-3b5d-9f99-dc834606cf93",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreGraphics\/_doubleindirect.abi3.so",
    "name" : "_doubleindirect.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4540641280,
    "size" : 8192,
    "uuid" : "f600f753-93be-34bd-b159-82f09fe61264",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreGraphics\/_sortandmap.abi3.so",
    "name" : "_sortandmap.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4586975232,
    "size" : 8192,
    "uuid" : "a151f513-f76d-3eb3-95af-033e573513f2",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreGraphics\/_coregraphics.cpython-38-darwin.so",
    "name" : "_coregraphics.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4526428160,
    "size" : 4096,
    "uuid" : "7c85e945-be4d-3ad6-b898-d71cb7720706",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreGraphics\/_inlines.abi3.so",
    "name" : "_inlines.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4587024384,
    "size" : 8192,
    "uuid" : "14bdc2a8-ae57-37de-ab09-70475ec4d8ff",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/ImageKit\/_imagekit.abi3.so",
    "name" : "_imagekit.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4534067200,
    "size" : 4096,
    "uuid" : "e4caa010-46db-3512-8010-a0e79cf6eb36",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/CoreVideo\/_CVPixelBuffer.abi3.so",
    "name" : "_CVPixelBuffer.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592570368,
    "size" : 24576,
    "uuid" : "b708cf89-6fea-3b18-a9c1-5f176cecb585",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/QuartzCore\/_quartzcore.abi3.so",
    "name" : "_quartzcore.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4538093568,
    "size" : 4096,
    "uuid" : "cf1e6800-63a5-3932-a1cf-4629a43e6045",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/PDFKit\/_PDFKit.abi3.so",
    "name" : "_PDFKit.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4540690432,
    "size" : 4096,
    "uuid" : "03bbbd82-4960-38b7-8387-9f3ad4790fd7",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/Quartz\/QuickLookUI\/_QuickLookUI.abi3.so",
    "name" : "_QuickLookUI.abi3.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592062464,
    "size" : 32768,
    "uuid" : "4ee1de6a-42cb-3bcd-bb69-eb7e68944b72",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/base.cpython-38-darwin.so",
    "name" : "base.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619952128,
    "size" : 1507328,
    "uuid" : "4c09b3f9-7a3c-3ff6-ac1f-5e17fda7390c",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libSDL2-2.0.0.dylib",
    "name" : "libSDL2-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4617576448,
    "size" : 49152,
    "uuid" : "532b6781-d275-3ba8-bccd-ac11defa4aea",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/constants.cpython-38-darwin.so",
    "name" : "constants.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592144384,
    "size" : 32768,
    "uuid" : "d370b66d-e0dd-3f45-9bce-c7c3d8a24e8e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/rect.cpython-38-darwin.so",
    "name" : "rect.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4592242688,
    "size" : 16384,
    "uuid" : "5b4a9427-e3cc-39ec-9717-c08b8ee3dac7",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/rwobject.cpython-38-darwin.so",
    "name" : "rwobject.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4612120576,
    "size" : 16384,
    "uuid" : "71f4097e-4863-3866-85eb-ecdb5bcbed27",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/surflock.cpython-38-darwin.so",
    "name" : "surflock.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4617936896,
    "size" : 32768,
    "uuid" : "0b8dc62b-f0bf-3bf4-be17-0904391dac91",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/color.cpython-38-darwin.so",
    "name" : "color.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618018816,
    "size" : 16384,
    "uuid" : "55e3fd66-0171-3c1c-96db-f770e0adf9f3",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/bufferproxy.cpython-38-darwin.so",
    "name" : "bufferproxy.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618211328,
    "size" : 65536,
    "uuid" : "1f299e6a-28bd-38f6-aad5-1f6cb3d6d8b8",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/math.cpython-38-darwin.so",
    "name" : "math.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618084352,
    "size" : 32768,
    "uuid" : "4828a107-7a53-3872-831d-112d87323a07",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/display.cpython-38-darwin.so",
    "name" : "display.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618637312,
    "size" : 229376,
    "uuid" : "e1dfe43c-d4ac-343d-bb77-cd0f5bbaa883",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/surface.cpython-38-darwin.so",
    "name" : "surface.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618436608,
    "size" : 49152,
    "uuid" : "104d509f-5b06-37a3-9d2f-2ef0823e571f",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/draw.cpython-38-darwin.so",
    "name" : "draw.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618534912,
    "size" : 32768,
    "uuid" : "72929b1f-8b75-3ea4-ab06-82df24c4773d",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/event.cpython-38-darwin.so",
    "name" : "event.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618342400,
    "size" : 32768,
    "uuid" : "21c96b96-2918-3e8a-abcf-613640a4b212",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/image.cpython-38-darwin.so",
    "name" : "image.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618932224,
    "size" : 16384,
    "uuid" : "30c21190-e287-35dc-89f1-70fc8e7e9dca",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/imageext.cpython-38-darwin.so",
    "name" : "imageext.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619210752,
    "size" : 147456,
    "uuid" : "097cb12c-1e47-3414-a520-536d5cd6cbeb",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libSDL2_image-2.0.0.dylib",
    "name" : "libSDL2_image-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4622327808,
    "size" : 196608,
    "uuid" : "e881cc35-c895-3466-a3ee-39269498cfdf",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libpng16.16.dylib",
    "name" : "libpng16.16.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4623417344,
    "size" : 655360,
    "uuid" : "d926dcf5-263f-3399-998b-996067e0ea8b",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libjpeg.62.3.0.dylib",
    "name" : "libjpeg.62.3.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4624203776,
    "size" : 491520,
    "uuid" : "4e74b4c4-8261-3267-bd0f-a9cf2a864d58",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libtiff.5.8.0.dylib",
    "name" : "libtiff.5.8.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619423744,
    "size" : 114688,
    "uuid" : "1db292da-07c1-3f22-918d-fb52e8836a37",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libz.1.2.11.zlib-ng.dylib",
    "name" : "libz.1.2.11.zlib-ng.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4624777216,
    "size" : 524288,
    "uuid" : "edb0324e-35d8-3f86-acbe-abce96ed800e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libwebp.7.dylib",
    "name" : "libwebp.7.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4618997760,
    "size" : 16384,
    "uuid" : "50e4611c-bfba-3c0f-b8aa-7cbc0836780e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libsharpyuv.0.dylib",
    "name" : "libsharpyuv.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619063296,
    "size" : 16384,
    "uuid" : "e876a4d6-86cc-35dd-a55d-d50be9d1aad4",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/joystick.cpython-38-darwin.so",
    "name" : "joystick.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619128832,
    "size" : 16384,
    "uuid" : "6c0bac1c-9430-34bd-a6cc-0d800f55da2b",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/key.cpython-38-darwin.so",
    "name" : "key.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4619587584,
    "size" : 16384,
    "uuid" : "59a3b322-446d-38c3-af99-f3c599dd4c5d",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/mouse.cpython-38-darwin.so",
    "name" : "mouse.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4622639104,
    "size" : 16384,
    "uuid" : "27f8c6f0-0cf6-3ff7-88db-a8ad5b43aa0d",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/time.cpython-38-darwin.so",
    "name" : "time.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4622819328,
    "size" : 65536,
    "uuid" : "f2fa612b-be3f-37d4-afeb-f9e1377c741e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/mask.cpython-38-darwin.so",
    "name" : "mask.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4622934016,
    "size" : 49152,
    "uuid" : "4607718b-366d-3e2d-9c45-c0a29ba697fb",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/pixelcopy.cpython-38-darwin.so",
    "name" : "pixelcopy.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4623032320,
    "size" : 49152,
    "uuid" : "6939f3aa-b04e-352e-bf82-f1135ef2e1ca",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/pixelarray.cpython-38-darwin.so",
    "name" : "pixelarray.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4623130624,
    "size" : 65536,
    "uuid" : "41703246-49c0-39e3-b136-10fff5513d67",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/transform.cpython-38-darwin.so",
    "name" : "transform.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4622704640,
    "size" : 16384,
    "uuid" : "9d696773-adf5-3a82-84df-d9187d96d68f",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/font.cpython-38-darwin.so",
    "name" : "font.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4627771392,
    "size" : 1572864,
    "uuid" : "4a37c130-391c-3006-a9f7-036dbf861d1b",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libSDL2_ttf-2.0.0.dylib",
    "name" : "libSDL2_ttf-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4623245312,
    "size" : 16384,
    "uuid" : "c5d4cb43-4bff-3855-95bb-98d11e309842",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/mixer_music.cpython-38-darwin.so",
    "name" : "mixer_music.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4625760256,
    "size" : 147456,
    "uuid" : "603d86df-3794-3a09-8096-d14082d0bbb4",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libSDL2_mixer-2.0.0.dylib",
    "name" : "libSDL2_mixer-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4626501632,
    "size" : 376832,
    "uuid" : "e792305a-fe66-31cf-adc8-e2d74a0b2a46",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libfluidsynth.3.1.1.dylib",
    "name" : "libfluidsynth.3.1.1.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4623310848,
    "size" : 32768,
    "uuid" : "22f47dc1-9b68-3229-b52c-dffc0dc7fce8",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libvorbisfile.3.3.8.dylib",
    "name" : "libvorbisfile.3.3.8.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4627369984,
    "size" : 229376,
    "uuid" : "b8cbb2d1-babf-3c76-b7ef-6d60222523a6",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libFLAC.8.dylib",
    "name" : "libFLAC.8.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4630048768,
    "size" : 278528,
    "uuid" : "3c7c6207-ab84-32e0-b0ba-ea19adabacbb",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libmpg123.0.dylib",
    "name" : "libmpg123.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4625600512,
    "size" : 49152,
    "uuid" : "247e5173-dc52-3626-80be-38e01e5279bc",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libopusfile.0.dylib",
    "name" : "libopusfile.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4625498112,
    "size" : 32768,
    "uuid" : "fc6f6d2c-48b2-3c1e-a267-fab4be014899",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libogg.0.8.5.dylib",
    "name" : "libogg.0.8.5.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4631023616,
    "size" : 442368,
    "uuid" : "de396a48-7b9d-30a1-9a7d-334ff52a53f0",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libopus.0.dylib",
    "name" : "libopus.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4626022400,
    "size" : 16384,
    "uuid" : "05dc54cb-51e6-308c-a740-d0471edb88de",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libgthread-2.0.0.dylib",
    "name" : "libgthread-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4633321472,
    "size" : 1490944,
    "uuid" : "79e5be28-7cde-3487-9ac5-077074cc4b59",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libglib-2.0.0.dylib",
    "name" : "libglib-2.0.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4632199168,
    "size" : 491520,
    "uuid" : "80f71c72-b85c-35a2-afc8-f1ec36649b79",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libsndfile.1.0.34.dylib",
    "name" : "libsndfile.1.0.34.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4630441984,
    "size" : 229376,
    "uuid" : "225af95d-d834-3f10-a226-63d3e5488666",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libvorbis.0.4.9.dylib",
    "name" : "libvorbis.0.4.9.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4635779072,
    "size" : 507904,
    "uuid" : "036c7df4-d5c3-34f8-8ed2-6e94e4ff5466",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libvorbisenc.2.0.12.dylib",
    "name" : "libvorbisenc.2.0.12.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4626087936,
    "size" : 32768,
    "uuid" : "cee9f73b-8ba2-379a-b40b-e5f96cf1a1a4",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/mixer.cpython-38-darwin.so",
    "name" : "mixer.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4626186240,
    "size" : 16384,
    "uuid" : "490f8eaf-9f18-3f17-a209-a1911fa43db3",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/pygame\/scrap.cpython-38-darwin.so",
    "name" : "scrap.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4660568064,
    "CFBundleShortVersionString" : "1.14",
    "CFBundleIdentifier" : "com.apple.audio.units.Components",
    "size" : 1331200,
    "uuid" : "d45baf6b-bdb1-3f52-9b15-c055dd9f46b0",
    "path" : "\/System\/Library\/Components\/CoreAudio.component\/Contents\/MacOS\/CoreAudio",
    "name" : "CoreAudio",
    "CFBundleVersion" : "1.14"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4683685888,
    "CFBundleShortVersionString" : "1.0",
    "CFBundleIdentifier" : "com.apple.audio.AudioDSPComponents",
    "size" : 10248192,
    "uuid" : "1d34a6e7-3311-3552-bfc2-cb375e80a7fe",
    "path" : "\/System\/Library\/Components\/AudioDSP.component\/Contents\/MacOS\/AudioDSP",
    "name" : "AudioDSP",
    "CFBundleVersion" : "1"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4631896064,
    "size" : 49152,
    "uuid" : "de8d22c3-93fb-3522-89d4-7b5df4fbbd5a",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/lib-dynload\/_sqlite3.cpython-38-darwin.so",
    "name" : "_sqlite3.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4658765824,
    "size" : 1081344,
    "uuid" : "4c2dc9a4-551e-370d-a8ba-35d749eee550",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/libsqlite3.0.dylib",
    "name" : "libsqlite3.0.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4657487872,
    "size" : 278528,
    "uuid" : "e8f2f899-f8e7-3e97-b110-3d44d112a98f",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/yaml\/_yaml.cpython-38-darwin.so",
    "name" : "_yaml.cpython-38-darwin.so"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4665008128,
    "size" : 1486848,
    "uuid" : "c4257303-d1d5-356c-9ab8-2de480bd1008",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/platforms\/libqcocoa.dylib",
    "name" : "libqcocoa.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4660043776,
    "size" : 389120,
    "uuid" : "4e77489b-7f46-3781-a8b5-dc5a24ef9c2e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtDBus",
    "name" : "QtDBus"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4658229248,
    "size" : 172032,
    "uuid" : "d9165c00-1902-3a63-ac8d-8554a72de298",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/QtPrintSupport",
    "name" : "QtPrintSupport"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4683321344,
    "size" : 147456,
    "uuid" : "0fcc2cd4-79f3-3a39-a04b-d1804113749f",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/styles\/libqmacstyle.dylib",
    "name" : "libqmacstyle.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4658569216,
    "size" : 24576,
    "uuid" : "1fc1d480-89de-391c-bda4-46e0ede5480e",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqsvg.dylib",
    "name" : "libqsvg.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4658630656,
    "size" : 32768,
    "uuid" : "24e9eb93-2c89-307b-a55f-af1b2fe3d0f1",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqgif.dylib",
    "name" : "libqgif.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4664913920,
    "size" : 32768,
    "uuid" : "dddab091-c000-3c01-b4b6-61003e4412f4",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqicns.dylib",
    "name" : "libqicns.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4658700288,
    "size" : 24576,
    "uuid" : "fbffa067-f740-3e67-b39b-5ce626478c5d",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqico.dylib",
    "name" : "libqico.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4868616192,
    "size" : 659456,
    "uuid" : "cd0e2998-0bda-38ca-97b3-5df4890e133d",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqjpeg.dylib",
    "name" : "libqjpeg.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4683558912,
    "size" : 24576,
    "uuid" : "447ff0f4-fa10-356c-bf51-5dc6d4303433",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqmacheif.dylib",
    "name" : "libqmacheif.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4683620352,
    "size" : 24576,
    "uuid" : "87abdc9e-50f3-3d07-9c69-537dc83b06bd",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqmacjp2.dylib",
    "name" : "libqmacjp2.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4867911680,
    "size" : 20480,
    "uuid" : "f1b7fe14-b817-3c2c-b307-2bbbdec0e055",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqtga.dylib",
    "name" : "libqtga.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4869328896,
    "size" : 458752,
    "uuid" : "91f4297c-c049-3c56-8a79-552cf5be4fb9",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqtiff.dylib",
    "name" : "libqtiff.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4867969024,
    "size" : 20480,
    "uuid" : "c1c9027c-e3c9-3b6a-aa95-5791b605a112",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqwbmp.dylib",
    "name" : "libqwbmp.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 4870561792,
    "size" : 659456,
    "uuid" : "25401bd0-2246-3265-a81f-280634123590",
    "path" : "\/Users\/USER\/Downloads\/*\/Class Widgets.app\/Contents\/Frameworks\/PyQt5\/Qt5\/plugins\/imageformats\/libqwebp.dylib",
    "name" : "libqwebp.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64h",
    "base" : 4658135040,
    "size" : 53248,
    "uuid" : "6cd1b595-3b5f-3166-9a4f-5abfb45b87eb",
    "path" : "\/usr\/lib\/libobjc-trampolines.dylib",
    "name" : "libobjc-trampolines.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703242330112,
    "size" : 245760,
    "uuid" : "c214d771-f6a3-30be-b657-b4e0cb81c9df",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703242575872,
    "size" : 49152,
    "uuid" : "2b452c39-67e1-3f73-87ca-5e07d5f1e90d",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703238844416,
    "size" : 572544,
    "uuid" : "f2913392-361a-304f-b30d-486be5639e2d",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "size" : 0,
    "source" : "A",
    "base" : 0,
    "uuid" : "00000000-0000-0000-0000-000000000000"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703431372800,
    "CFBundleShortVersionString" : "1.0",
    "CFBundleIdentifier" : "com.apple.audio.caulk",
    "size" : 147456,
    "uuid" : "f63e19d9-7ba1-3630-95cc-64ebd540564c",
    "path" : "\/System\/Library\/PrivateFrameworks\/caulk.framework\/Versions\/A\/caulk",
    "name" : "caulk"
  },
  {
    "source" : "P",
    "arch" : "x86_64h",
    "base" : 140703243038720,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.CoreFoundation",
    "size" : 4841443,
    "uuid" : "404c409f-d28c-309d-ade3-f0ee6f1ca33d",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/Versions\/A\/CoreFoundation",
    "name" : "CoreFoundation",
    "CFBundleVersion" : "3302.1.400"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703521144832,
    "size" : 217088,
    "uuid" : "6dcf7c3b-8372-3de6-b0aa-d1172a3f7d57",
    "path" : "\/usr\/lib\/libAudioToolboxUtility.dylib",
    "name" : "libAudioToolboxUtility.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703541420032,
    "CFBundleShortVersionString" : "1.14",
    "CFBundleIdentifier" : "com.apple.audio.toolbox.AudioToolbox",
    "size" : 1679350,
    "uuid" : "208b183c-8587-3205-938b-94833ad84f61",
    "path" : "\/System\/Library\/Frameworks\/AudioToolbox.framework\/Versions\/A\/AudioToolbox",
    "name" : "AudioToolbox",
    "CFBundleVersion" : "1.14"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703284178944,
    "CFBundleShortVersionString" : "5.0",
    "CFBundleIdentifier" : "com.apple.audio.CoreAudio",
    "size" : 7647217,
    "uuid" : "15f9185f-dd75-3d1e-98b0-7a8cb484ba9c",
    "path" : "\/System\/Library\/Frameworks\/CoreAudio.framework\/Versions\/A\/CoreAudio",
    "name" : "CoreAudio",
    "CFBundleVersion" : "5.0"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703241158656,
    "size" : 561144,
    "uuid" : "12e8dc9e-ee00-37e7-8830-dc84a6de23b1",
    "path" : "\/usr\/lib\/system\/libsystem_c.dylib",
    "name" : "libsystem_c.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703242231808,
    "size" : 98304,
    "uuid" : "772cbc4b-017a-3016-815a-35bc9b8ad230",
    "path" : "\/usr\/lib\/libc++abi.dylib",
    "name" : "libc++abi.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64h",
    "base" : 140703238569984,
    "size" : 274380,
    "uuid" : "d15ff8c9-a533-3094-8650-bc97d3c883b9",
    "path" : "\/usr\/lib\/libobjc.A.dylib",
    "name" : "libobjc.A.dylib"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703354142720,
    "CFBundleShortVersionString" : "1.22",
    "CFBundleIdentifier" : "com.apple.HIServices",
    "size" : 417787,
    "uuid" : "f4d81a83-a4c8-370a-b62a-3ad58296c9f8",
    "path" : "\/System\/Library\/Frameworks\/ApplicationServices.framework\/Versions\/A\/Frameworks\/HIServices.framework\/Versions\/A\/HIServices",
    "name" : "HIServices"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703260172288,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.Foundation",
    "size" : 14880756,
    "uuid" : "ff5888c8-5530-389a-b032-c6aa06e6d180",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Versions\/C\/Foundation",
    "name" : "Foundation",
    "CFBundleVersion" : "3302.1.400"
  },
  {
    "source" : "P",
    "arch" : "x86_64",
    "base" : 140703303446528,
    "CFBundleShortVersionString" : "6.9",
    "CFBundleIdentifier" : "com.apple.AppKit",
    "size" : 21999608,
    "uuid" : "e3f76bb8-4950-3c7a-8aa7-8516a93aeeb9",
    "path" : "\/System\/Library\/Frameworks\/AppKit.framework\/Versions\/C\/AppKit",
    "name" : "AppKit",
    "CFBundleVersion" : "2575.40.6"
  }
],
  "sharedCache" : {
  "base" : 140703238094848,
  "size" : 25769803776,
  "uuid" : "516bea14-552c-3fc6-ab95-a99ee266aaf3"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=1.0G resident=0K(0%) swapped_out_or_unallocated=1.0G(100%)\nWritable regions: Total=673.5M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=673.5M(100%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nActivity Tracing                   256K        1 \nColorSync                          224K       26 \nCoreServices                        88K        1 \nFoundation                          16K        1 \nKernel Alloc Once                    8K        1 \nMALLOC                           620.9M       70 \nMALLOC guard page                   48K       12 \nMALLOC_LARGE (reserved)            384K        2         reserved VM address space (unallocated)\nSTACK GUARD                       56.0M       12 \nStack                             13.6M       12 \nVM_ALLOCATE                       37.5M      125 \nVM_ALLOCATE (reserved)              32K        1         reserved VM address space (unallocated)\n__CTF                               824        1 \n__DATA                            26.5M      805 \n__DATA_CONST                      71.4M      733 \n__DATA_DIRTY                      1753K      243 \n__FONT_DATA                        2352        1 \n__LINKEDIT                       206.6M      140 \n__OBJC_RO                         76.9M        1 \n__OBJC_RW                         2375K        3 \n__TEXT                           845.0M      828 \n__TPRO_CONST                       272K        2 \nmapped file                      214.9M       23 \nowned unmapped memory               36K        1 \nshared memory                     1380K       19 \n===========                     =======  ======= \nTOTAL                              2.1G     3064 \nTOTAL, minus reserved VM space     2.1G     3064 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "name" : "SystemThemeListener"
  }
},
  "logWritingSignature" : "6d9a189113ce1f3d93c219c7010034d8bc284441",
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "654439cdafbf5b61207873a9",
      "factorPackIds" : {

      },
      "deploymentId" : 240000004
    },
    {
      "rolloutId" : "67181b10c68c361a728c7cfa",
      "factorPackIds" : {

      },
      "deploymentId" : 240000004
    }
  ],
  "experiments" : [

  ]
}
}

Model: MacBookPro15,4, BootROM 2069.80.3.0.0 (iBridge: 22.16.13060.0.0,0), 4 processors, Quad-Core Intel Core i5, 1.4 GHz, 8 GB, SMC 
Graphics: Intel Iris Plus Graphics 645, Intel Iris Plus Graphics 645, Built-In
Display: Color LCD, 2560 x 1600 Retina, Main, MirrorOff, Online
Memory Module: BANK 0/ChannelA-DIMM0, 4 GB, LPDDR3, 2133 MHz, Samsung, K4E6E304EC-EGCG
Memory Module: BANK 2/ChannelB-DIMM0, 4 GB, LPDDR3, 2133 MHz, Samsung, K4E6E304EC-EGCG
AirPort: spairport_wireless_card_type_wifi (0x14E4, 0x870), wl0: Jul 26 2024 20:45:01 version 16.20.380.0.3.6.130 FWID 01-c866e60e
AirPort: 
Bluetooth: Version (null), 0 services, 0 devices, 0 incoming serial ports
Network Service: Wi-Fi, AirPort, en0
USB Device: USB31Bus
USB Device: T2Bus
USB Device: Touch Bar Backlight
USB Device: Touch Bar Display
USB Device: Apple Internal Keyboard / Trackpad
USB Device: Headset
USB Device: Ambient Light Sensor
USB Device: FaceTime HD Camera (Built-in)
USB Device: Apple T2 Controller
Thunderbolt Bus: MacBook Pro, Apple Inc., 63.5
```

终端日志：
```
Last login: Fri Apr 11 16:42:28 on ttys000
mac@macs-MacBook-Pro ~ % /Users/mac/Downloads/dist\ 2/Class\ Widgets.app/Contents/MacOS/Class\ Widgets ; exit;

📢 Tips: QFluentWidgets Pro is now released. Click https://qfluentwidgets.com/pages/pro to learn more about it.

2025-04-11 16:51:27.592 | INFO     | conf:check_config:319 - 配置文件不存在，已创建并写入默认配置。
pygame 2.6.1 (SDL 2.28.4, Python 3.8.10)
Hello from the pygame community. https://www.pygame.org/contribute.html
2025-04-11 16:51:28.248 | INFO     | __main__:<module>:89 - 未禁用日志输出
2025-04-11 16:51:28.250 | INFO     | __main__:<module>:1662 - 当前缩放系数：100.0%
2025-04-11 16:51:28.671 | INFO     | __main__:<module>:1667 - 共享内存：True 是否允许多开实例：0
2025-04-11 16:51:28.672 | INFO     | __main__:<module>:1688 - 操作系统：macOS，版本：Darwin Kernel Version 24.3.0/macOS 15.3.2
2025-04-11 16:51:28.832 | INFO     | __main__:init:1629 - 应用主题：default
2025-04-11 16:51:28.955 | ERROR    | __main__:global_exceptHook:107 - 全局异常捕获：<class 'FileNotFoundError'> [Errno 2] No such file or directory: PosixPath('/Users/mac/Downloads/dist 2/Class Widgets.app/Contents/Frameworks/darkdetect') <traceback object at 0x11609ae00>
2025-04-11 16:51:28.956 | ERROR    | __main__:global_exceptHook:108 - 详细堆栈信息：
Traceback (most recent call last):
  File "qfluentwidgets/common/theme_listener.py", line 17, in run
  File "darkdetect/_mac_detect.py", line 117, in listener
  File "subprocess.py", line 858, in __init__
  File "subprocess.py", line 1704, in _execute_child
FileNotFoundError: [Errno 2] No such file or directory: PosixPath('/Users/mac/Downloads/dist 2/Class Widgets.app/Contents/Frameworks/darkdetect')

*** Terminating app due to uncaught exception 'NSInternalInconsistencyException', reason: 'NSWindow should only be instantiated on the main thread!'
*** First throw call stack:
(
	0   CoreFoundation                      0x00007ff806e0b326 __exceptionPreprocess + 242
	1   libobjc.A.dylib                     0x00007ff8068f0bd0 objc_exception_throw + 62
	2   CoreFoundation                      0x00007ff806e2e2b4 -[NSException raise] + 9
	3   AppKit                              0x00007ff80a710126 -[NSWindow _initContent:styleMask:backing:defer:contentView:] + 1653
	4   AppKit                              0x00007ff80a89b811 -[NSPanel _initContent:styleMask:backing:defer:contentView:] + 50
	5   AppKit                              0x00007ff80a70faa9 -[NSWindow initWithContentRect:styleMask:backing:defer:] + 42
	6   AppKit                              0x00007ff80a89b7ca -[NSPanel initWithContentRect:styleMask:backing:defer:] + 59
	7   AppKit                              0x00007ff80a9c735a -[NSWindow initWithContentRect:styleMask:backing:defer:screen:] + 50
	8   libqcocoa.dylib                     0x0000000116120374 qt_plugin_instance + 201684
	9   libqcocoa.dylib                     0x000000011610a978 qt_plugin_instance + 113112
	10  libqcocoa.dylib                     0x0000000116103899 qt_plugin_instance + 84217
	11  libqcocoa.dylib                     0x0000000116103307 qt_plugin_instance + 82791
	12  QtGui                               0x0000000111c53c32 _ZN14QWindowPrivate6createEby + 146
	13  QtWidgets                           0x00000001122e63d5 _ZN14QWidgetPrivate6createEv + 1061
	14  QtWidgets                           0x00000001122e50d5 _ZN7QWidget6createEybb + 325
	15  QtWidgets                           0x00000001122e6d51 _ZNK7QWidget5winIdEv + 65
	16  QtWidgets.abi3.so                   0x0000000112ab2749 _ZL18meth_QWidget_winIdP7_objectS0_ + 89
	17  libpython3.8.dylib                  0x000000010cfb9ad5 cfunction_call_varargs + 197
	18  libpython3.8.dylib                  0x000000010cfb905c _PyObject_MakeTpCall + 188
	19  libpython3.8.dylib                  0x000000010d0f3e32 _PyEval_EvalFrameDefault + 31426
	20  libpython3.8.dylib                  0x000000010cfba1e5 _PyFunction_Vectorcall + 245
	21  libpython3.8.dylib                  0x000000010cfbdd4e method_vectorcall + 142
	22  libpython3.8.dylib                  0x000000010d0f26bb _PyEval_EvalFrameDefault + 25419
	23  libpython3.8.dylib                  0x000000010d0ea501 _PyEval_EvalCodeWithName + 561
	24  libpython3.8.dylib                  0x000000010cfba29a _PyFunction_Vectorcall + 426
	25  libpython3.8.dylib                  0x000000010cfbdd4e method_vectorcall + 142
	26  libpython3.8.dylib                  0x000000010d0f26bb _PyEval_EvalFrameDefault + 25419
	27  libpython3.8.dylib                  0x000000010d0ea501 _PyEval_EvalCodeWithName + 561
	28  libpython3.8.dylib                  0x000000010cfba29a _PyFunction_Vectorcall + 426
	29  libpython3.8.dylib                  0x000000010cfbdd4e method_vectorcall + 142
	30  libpython3.8.dylib                  0x000000010d0f10d1 _PyEval_EvalFrameDefault + 19809
	31  libpython3.8.dylib                  0x000000010d0ea501 _PyEval_EvalCodeWithName + 561
	32  libpython3.8.dylib                  0x000000010cfba29a _PyFunction_Vectorcall + 426
	33  libpython3.8.dylib                  0x000000010cfbdd4e method_vectorcall + 142
	34  libpython3.8.dylib                  0x000000010d0f26bb _PyEval_EvalFrameDefault + 25419
	35  libpython3.8.dylib                  0x000000010d0ea501 _PyEval_EvalCodeWithName + 561
	36  libpython3.8.dylib                  0x000000010cfba29a _PyFunction_Vectorcall + 426
	37  libpython3.8.dylib                  0x000000010cfb8d4f _PyObject_FastCallDict + 79
	38  libpython3.8.dylib                  0x000000010d0413e3 slot_tp_init + 179
	39  libpython3.8.dylib                  0x000000010d04ce19 type_call + 297
	40  libpython3.8.dylib                  0x000000010cfb905c _PyObject_MakeTpCall + 188
	41  libpython3.8.dylib                  0x000000010d0f2d5d _PyEval_EvalFrameDefault + 27117
	42  libpython3.8.dylib                  0x000000010cfba1e5 _PyFunction_Vectorcall + 245
	43  libpython3.8.dylib                  0x000000010d1677f0 _PyObject_Vectorcall.5458 + 48
	44  libpython3.8.dylib                  0x000000010d1672f0 _PyErr_PrintEx + 464
	45  QtCore.abi3.so                      0x000000010e53cd0a _Z15pyqt5_err_printv + 122
	46  sip.cpython-38-darwin.so            0x000000010e1258a3 sip_api_call_procedure_method + 243
	47  QtCore.abi3.so                      0x000000010e4300bc _ZN10sipQThread3runEv + 92
	48  QtCore                              0x000000010ed1e0f3 _ZN7QThread11qt_metacallEN11QMetaObject4CallEiPPv + 1171
	49  libsystem_pthread.dylib             0x00007ff806cb4253 _pthread_start + 99
	50  libsystem_pthread.dylib             0x00007ff806cafbef thread_start + 15
)
libc++abi: terminating due to uncaught exception of type NSException
zsh: abort      /Users/mac/Downloads/dist\ 2/Class\ Widgets.app/Contents/MacOS/Class\ Widgets

Saving session...
...copying shared history...
...saving history...truncating history files...
...completed.
Deleting expired sessions...none found.

[进程已完成]
```
