# lab4

partA:
0000000000600e20 d _DYNAMIC
0000000000600fe8 d _GLOBAL_OFFSET_TABLE_
00000000004006c5 t _GLOBAL__sub_I__Z7averagePdRd
00000000004007c8 R _IO_stdin_used
                 w _Jv_RegisterClasses
0000000000400685 t _Z41__static_initialization_and_destruction_0ii
0000000000400624 T _Z7averagePdRd
0000000000400652 T _Z7averageif
                 U _ZNSt8ios_base4InitC1Ev@@GLIBCXX_3.4
                 U _ZNSt8ios_base4InitD1Ev@@GLIBCXX_3.4
0000000000601040 b _ZStL8__ioinit
0000000000600e00 d __CTOR_END__
0000000000600df8 d __CTOR_LIST__
0000000000600e10 D __DTOR_END__
0000000000600e08 d __DTOR_LIST__
0000000000400948 r __FRAME_END__
0000000000600e18 d __JCR_END__
0000000000600e18 d __JCR_LIST__
0000000000601030 A __bss_start
                 U __cxa_atexit@@GLIBC_2.2.5
0000000000601020 D __data_start
0000000000400780 t __do_global_ctors_aux
0000000000400590 t __do_global_dtors_aux
0000000000601028 D __dso_handle
                 w __gmon_start__
0000000000600df8 t __init_array_end
0000000000600df0 t __init_array_start
0000000000400770 T __libc_csu_fini
00000000004006e0 T __libc_csu_init
                 U __libc_start_main@@GLIBC_2.2.5
0000000000601030 A _edata
0000000000601048 A _end
00000000004007b8 T _fini
00000000004004d8 T _init
0000000000400540 T _start
000000000040056c t call_gmon_start
0000000000601030 b completed.6531
0000000000601020 W data_start
0000000000601038 b dtor_idx.6533
0000000000400600 t frame_dummy
000000000040067a T main
nm指令是用來印出object的symbol的，在code中相同的稱的function都叫做average ，在編譯的時候會將他後面輸出的type編號區分為兩個，就是function overloading

partB:

1 8
4 8
4 8
8 8
第一列是各個變數站記憶體的空間大小，char型態占了1個byte，int型態占了4個byte>    ，float型態占了4個byte，double型態占了8byte。
第二列是存取變數指標所佔的紀體體空間大小，不管甚麼型態都是8byte
