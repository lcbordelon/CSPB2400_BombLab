
bomb:     file format elf64-x86-64


Disassembly of section .init:

0000000000001000 <_init>:
    1000:	f3 0f 1e fa          	endbr64 
    1004:	48 83 ec 08          	sub    $0x8,%rsp
    1008:	48 8b 05 d9 3f 00 00 	mov    0x3fd9(%rip),%rax        # 4fe8 <__gmon_start__@Base>
    100f:	48 85 c0             	test   %rax,%rax
    1012:	74 02                	je     1016 <_init+0x16>
    1014:	ff d0                	call   *%rax
    1016:	48 83 c4 08          	add    $0x8,%rsp
    101a:	c3                   	ret    

Disassembly of section .plt:

0000000000001020 <.plt>:
    1020:	ff 35 d2 3e 00 00    	push   0x3ed2(%rip)        # 4ef8 <_GLOBAL_OFFSET_TABLE_+0x8>
    1026:	f2 ff 25 d3 3e 00 00 	bnd jmp *0x3ed3(%rip)        # 4f00 <_GLOBAL_OFFSET_TABLE_+0x10>
    102d:	0f 1f 00             	nopl   (%rax)
    1030:	f3 0f 1e fa          	endbr64 
    1034:	68 00 00 00 00       	push   $0x0
    1039:	f2 e9 e1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    103f:	90                   	nop
    1040:	f3 0f 1e fa          	endbr64 
    1044:	68 01 00 00 00       	push   $0x1
    1049:	f2 e9 d1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    104f:	90                   	nop
    1050:	f3 0f 1e fa          	endbr64 
    1054:	68 02 00 00 00       	push   $0x2
    1059:	f2 e9 c1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    105f:	90                   	nop
    1060:	f3 0f 1e fa          	endbr64 
    1064:	68 03 00 00 00       	push   $0x3
    1069:	f2 e9 b1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    106f:	90                   	nop
    1070:	f3 0f 1e fa          	endbr64 
    1074:	68 04 00 00 00       	push   $0x4
    1079:	f2 e9 a1 ff ff ff    	bnd jmp 1020 <_init+0x20>
    107f:	90                   	nop
    1080:	f3 0f 1e fa          	endbr64 
    1084:	68 05 00 00 00       	push   $0x5
    1089:	f2 e9 91 ff ff ff    	bnd jmp 1020 <_init+0x20>
    108f:	90                   	nop
    1090:	f3 0f 1e fa          	endbr64 
    1094:	68 06 00 00 00       	push   $0x6
    1099:	f2 e9 81 ff ff ff    	bnd jmp 1020 <_init+0x20>
    109f:	90                   	nop
    10a0:	f3 0f 1e fa          	endbr64 
    10a4:	68 07 00 00 00       	push   $0x7
    10a9:	f2 e9 71 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10af:	90                   	nop
    10b0:	f3 0f 1e fa          	endbr64 
    10b4:	68 08 00 00 00       	push   $0x8
    10b9:	f2 e9 61 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10bf:	90                   	nop
    10c0:	f3 0f 1e fa          	endbr64 
    10c4:	68 09 00 00 00       	push   $0x9
    10c9:	f2 e9 51 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10cf:	90                   	nop
    10d0:	f3 0f 1e fa          	endbr64 
    10d4:	68 0a 00 00 00       	push   $0xa
    10d9:	f2 e9 41 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10df:	90                   	nop
    10e0:	f3 0f 1e fa          	endbr64 
    10e4:	68 0b 00 00 00       	push   $0xb
    10e9:	f2 e9 31 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10ef:	90                   	nop
    10f0:	f3 0f 1e fa          	endbr64 
    10f4:	68 0c 00 00 00       	push   $0xc
    10f9:	f2 e9 21 ff ff ff    	bnd jmp 1020 <_init+0x20>
    10ff:	90                   	nop
    1100:	f3 0f 1e fa          	endbr64 
    1104:	68 0d 00 00 00       	push   $0xd
    1109:	f2 e9 11 ff ff ff    	bnd jmp 1020 <_init+0x20>
    110f:	90                   	nop
    1110:	f3 0f 1e fa          	endbr64 
    1114:	68 0e 00 00 00       	push   $0xe
    1119:	f2 e9 01 ff ff ff    	bnd jmp 1020 <_init+0x20>
    111f:	90                   	nop
    1120:	f3 0f 1e fa          	endbr64 
    1124:	68 0f 00 00 00       	push   $0xf
    1129:	f2 e9 f1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    112f:	90                   	nop
    1130:	f3 0f 1e fa          	endbr64 
    1134:	68 10 00 00 00       	push   $0x10
    1139:	f2 e9 e1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    113f:	90                   	nop
    1140:	f3 0f 1e fa          	endbr64 
    1144:	68 11 00 00 00       	push   $0x11
    1149:	f2 e9 d1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    114f:	90                   	nop
    1150:	f3 0f 1e fa          	endbr64 
    1154:	68 12 00 00 00       	push   $0x12
    1159:	f2 e9 c1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    115f:	90                   	nop
    1160:	f3 0f 1e fa          	endbr64 
    1164:	68 13 00 00 00       	push   $0x13
    1169:	f2 e9 b1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    116f:	90                   	nop
    1170:	f3 0f 1e fa          	endbr64 
    1174:	68 14 00 00 00       	push   $0x14
    1179:	f2 e9 a1 fe ff ff    	bnd jmp 1020 <_init+0x20>
    117f:	90                   	nop
    1180:	f3 0f 1e fa          	endbr64 
    1184:	68 15 00 00 00       	push   $0x15
    1189:	f2 e9 91 fe ff ff    	bnd jmp 1020 <_init+0x20>
    118f:	90                   	nop
    1190:	f3 0f 1e fa          	endbr64 
    1194:	68 16 00 00 00       	push   $0x16
    1199:	f2 e9 81 fe ff ff    	bnd jmp 1020 <_init+0x20>
    119f:	90                   	nop
    11a0:	f3 0f 1e fa          	endbr64 
    11a4:	68 17 00 00 00       	push   $0x17
    11a9:	f2 e9 71 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11af:	90                   	nop
    11b0:	f3 0f 1e fa          	endbr64 
    11b4:	68 18 00 00 00       	push   $0x18
    11b9:	f2 e9 61 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11bf:	90                   	nop
    11c0:	f3 0f 1e fa          	endbr64 
    11c4:	68 19 00 00 00       	push   $0x19
    11c9:	f2 e9 51 fe ff ff    	bnd jmp 1020 <_init+0x20>
    11cf:	90                   	nop

Disassembly of section .plt.got:

00000000000011d0 <__cxa_finalize@plt>:
    11d0:	f3 0f 1e fa          	endbr64 
    11d4:	f2 ff 25 1d 3e 00 00 	bnd jmp *0x3e1d(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    11db:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .plt.sec:

00000000000011e0 <getenv@plt>:
    11e0:	f3 0f 1e fa          	endbr64 
    11e4:	f2 ff 25 1d 3d 00 00 	bnd jmp *0x3d1d(%rip)        # 4f08 <getenv@GLIBC_2.2.5>
    11eb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000011f0 <__errno_location@plt>:
    11f0:	f3 0f 1e fa          	endbr64 
    11f4:	f2 ff 25 15 3d 00 00 	bnd jmp *0x3d15(%rip)        # 4f10 <__errno_location@GLIBC_2.2.5>
    11fb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001200 <strcpy@plt>:
    1200:	f3 0f 1e fa          	endbr64 
    1204:	f2 ff 25 0d 3d 00 00 	bnd jmp *0x3d0d(%rip)        # 4f18 <strcpy@GLIBC_2.2.5>
    120b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001210 <puts@plt>:
    1210:	f3 0f 1e fa          	endbr64 
    1214:	f2 ff 25 05 3d 00 00 	bnd jmp *0x3d05(%rip)        # 4f20 <puts@GLIBC_2.2.5>
    121b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001220 <write@plt>:
    1220:	f3 0f 1e fa          	endbr64 
    1224:	f2 ff 25 fd 3c 00 00 	bnd jmp *0x3cfd(%rip)        # 4f28 <write@GLIBC_2.2.5>
    122b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001230 <strlen@plt>:
    1230:	f3 0f 1e fa          	endbr64 
    1234:	f2 ff 25 f5 3c 00 00 	bnd jmp *0x3cf5(%rip)        # 4f30 <strlen@GLIBC_2.2.5>
    123b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001240 <alarm@plt>:
    1240:	f3 0f 1e fa          	endbr64 
    1244:	f2 ff 25 ed 3c 00 00 	bnd jmp *0x3ced(%rip)        # 4f38 <alarm@GLIBC_2.2.5>
    124b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001250 <close@plt>:
    1250:	f3 0f 1e fa          	endbr64 
    1254:	f2 ff 25 e5 3c 00 00 	bnd jmp *0x3ce5(%rip)        # 4f40 <close@GLIBC_2.2.5>
    125b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001260 <read@plt>:
    1260:	f3 0f 1e fa          	endbr64 
    1264:	f2 ff 25 dd 3c 00 00 	bnd jmp *0x3cdd(%rip)        # 4f48 <read@GLIBC_2.2.5>
    126b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001270 <fgets@plt>:
    1270:	f3 0f 1e fa          	endbr64 
    1274:	f2 ff 25 d5 3c 00 00 	bnd jmp *0x3cd5(%rip)        # 4f50 <fgets@GLIBC_2.2.5>
    127b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001280 <strcmp@plt>:
    1280:	f3 0f 1e fa          	endbr64 
    1284:	f2 ff 25 cd 3c 00 00 	bnd jmp *0x3ccd(%rip)        # 4f58 <strcmp@GLIBC_2.2.5>
    128b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001290 <signal@plt>:
    1290:	f3 0f 1e fa          	endbr64 
    1294:	f2 ff 25 c5 3c 00 00 	bnd jmp *0x3cc5(%rip)        # 4f60 <signal@GLIBC_2.2.5>
    129b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012a0 <gethostbyname@plt>:
    12a0:	f3 0f 1e fa          	endbr64 
    12a4:	f2 ff 25 bd 3c 00 00 	bnd jmp *0x3cbd(%rip)        # 4f68 <gethostbyname@GLIBC_2.2.5>
    12ab:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012b0 <__memmove_chk@plt>:
    12b0:	f3 0f 1e fa          	endbr64 
    12b4:	f2 ff 25 b5 3c 00 00 	bnd jmp *0x3cb5(%rip)        # 4f70 <__memmove_chk@GLIBC_2.3.4>
    12bb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012c0 <strtol@plt>:
    12c0:	f3 0f 1e fa          	endbr64 
    12c4:	f2 ff 25 ad 3c 00 00 	bnd jmp *0x3cad(%rip)        # 4f78 <strtol@GLIBC_2.2.5>
    12cb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012d0 <fflush@plt>:
    12d0:	f3 0f 1e fa          	endbr64 
    12d4:	f2 ff 25 a5 3c 00 00 	bnd jmp *0x3ca5(%rip)        # 4f80 <fflush@GLIBC_2.2.5>
    12db:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012e0 <__isoc99_sscanf@plt>:
    12e0:	f3 0f 1e fa          	endbr64 
    12e4:	f2 ff 25 9d 3c 00 00 	bnd jmp *0x3c9d(%rip)        # 4f88 <__isoc99_sscanf@GLIBC_2.7>
    12eb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

00000000000012f0 <__printf_chk@plt>:
    12f0:	f3 0f 1e fa          	endbr64 
    12f4:	f2 ff 25 95 3c 00 00 	bnd jmp *0x3c95(%rip)        # 4f90 <__printf_chk@GLIBC_2.3.4>
    12fb:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001300 <fopen@plt>:
    1300:	f3 0f 1e fa          	endbr64 
    1304:	f2 ff 25 8d 3c 00 00 	bnd jmp *0x3c8d(%rip)        # 4f98 <fopen@GLIBC_2.2.5>
    130b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001310 <exit@plt>:
    1310:	f3 0f 1e fa          	endbr64 
    1314:	f2 ff 25 85 3c 00 00 	bnd jmp *0x3c85(%rip)        # 4fa0 <exit@GLIBC_2.2.5>
    131b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001320 <connect@plt>:
    1320:	f3 0f 1e fa          	endbr64 
    1324:	f2 ff 25 7d 3c 00 00 	bnd jmp *0x3c7d(%rip)        # 4fa8 <connect@GLIBC_2.2.5>
    132b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001330 <__fprintf_chk@plt>:
    1330:	f3 0f 1e fa          	endbr64 
    1334:	f2 ff 25 75 3c 00 00 	bnd jmp *0x3c75(%rip)        # 4fb0 <__fprintf_chk@GLIBC_2.3.4>
    133b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001340 <sleep@plt>:
    1340:	f3 0f 1e fa          	endbr64 
    1344:	f2 ff 25 6d 3c 00 00 	bnd jmp *0x3c6d(%rip)        # 4fb8 <sleep@GLIBC_2.2.5>
    134b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001350 <__ctype_b_loc@plt>:
    1350:	f3 0f 1e fa          	endbr64 
    1354:	f2 ff 25 65 3c 00 00 	bnd jmp *0x3c65(%rip)        # 4fc0 <__ctype_b_loc@GLIBC_2.3>
    135b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001360 <__sprintf_chk@plt>:
    1360:	f3 0f 1e fa          	endbr64 
    1364:	f2 ff 25 5d 3c 00 00 	bnd jmp *0x3c5d(%rip)        # 4fc8 <__sprintf_chk@GLIBC_2.3.4>
    136b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

0000000000001370 <socket@plt>:
    1370:	f3 0f 1e fa          	endbr64 
    1374:	f2 ff 25 55 3c 00 00 	bnd jmp *0x3c55(%rip)        # 4fd0 <socket@GLIBC_2.2.5>
    137b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .text:

0000000000001380 <_start>:
    1380:	f3 0f 1e fa          	endbr64 
    1384:	31 ed                	xor    %ebp,%ebp
    1386:	49 89 d1             	mov    %rdx,%r9
    1389:	5e                   	pop    %rsi
    138a:	48 89 e2             	mov    %rsp,%rdx
    138d:	48 83 e4 f0          	and    $0xfffffffffffffff0,%rsp
    1391:	50                   	push   %rax
    1392:	54                   	push   %rsp
    1393:	45 31 c0             	xor    %r8d,%r8d
    1396:	31 c9                	xor    %ecx,%ecx
    1398:	48 8d 3d ca 00 00 00 	lea    0xca(%rip),%rdi        # 1469 <main>
    139f:	ff 15 33 3c 00 00    	call   *0x3c33(%rip)        # 4fd8 <__libc_start_main@GLIBC_2.34>
    13a5:	f4                   	hlt    
    13a6:	66 2e 0f 1f 84 00 00 	cs nopw 0x0(%rax,%rax,1)
    13ad:	00 00 00 

00000000000013b0 <deregister_tm_clones>:
    13b0:	48 8d 3d c9 46 00 00 	lea    0x46c9(%rip),%rdi        # 5a80 <stdout@GLIBC_2.2.5>
    13b7:	48 8d 05 c2 46 00 00 	lea    0x46c2(%rip),%rax        # 5a80 <stdout@GLIBC_2.2.5>
    13be:	48 39 f8             	cmp    %rdi,%rax
    13c1:	74 15                	je     13d8 <deregister_tm_clones+0x28>
    13c3:	48 8b 05 16 3c 00 00 	mov    0x3c16(%rip),%rax        # 4fe0 <_ITM_deregisterTMCloneTable@Base>
    13ca:	48 85 c0             	test   %rax,%rax
    13cd:	74 09                	je     13d8 <deregister_tm_clones+0x28>
    13cf:	ff e0                	jmp    *%rax
    13d1:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    13d8:	c3                   	ret    
    13d9:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

00000000000013e0 <register_tm_clones>:
    13e0:	48 8d 3d 99 46 00 00 	lea    0x4699(%rip),%rdi        # 5a80 <stdout@GLIBC_2.2.5>
    13e7:	48 8d 35 92 46 00 00 	lea    0x4692(%rip),%rsi        # 5a80 <stdout@GLIBC_2.2.5>
    13ee:	48 29 fe             	sub    %rdi,%rsi
    13f1:	48 89 f0             	mov    %rsi,%rax
    13f4:	48 c1 ee 3f          	shr    $0x3f,%rsi
    13f8:	48 c1 f8 03          	sar    $0x3,%rax
    13fc:	48 01 c6             	add    %rax,%rsi
    13ff:	48 d1 fe             	sar    %rsi
    1402:	74 14                	je     1418 <register_tm_clones+0x38>
    1404:	48 8b 05 e5 3b 00 00 	mov    0x3be5(%rip),%rax        # 4ff0 <_ITM_registerTMCloneTable@Base>
    140b:	48 85 c0             	test   %rax,%rax
    140e:	74 08                	je     1418 <register_tm_clones+0x38>
    1410:	ff e0                	jmp    *%rax
    1412:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)
    1418:	c3                   	ret    
    1419:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001420 <__do_global_dtors_aux>:
    1420:	f3 0f 1e fa          	endbr64 
    1424:	80 3d 7d 46 00 00 00 	cmpb   $0x0,0x467d(%rip)        # 5aa8 <completed.0>
    142b:	75 2b                	jne    1458 <__do_global_dtors_aux+0x38>
    142d:	55                   	push   %rbp
    142e:	48 83 3d c2 3b 00 00 	cmpq   $0x0,0x3bc2(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    1435:	00 
    1436:	48 89 e5             	mov    %rsp,%rbp
    1439:	74 0c                	je     1447 <__do_global_dtors_aux+0x27>
    143b:	48 8b 3d c6 3b 00 00 	mov    0x3bc6(%rip),%rdi        # 5008 <__dso_handle>
    1442:	e8 89 fd ff ff       	call   11d0 <__cxa_finalize@plt>
    1447:	e8 64 ff ff ff       	call   13b0 <deregister_tm_clones>
    144c:	c6 05 55 46 00 00 01 	movb   $0x1,0x4655(%rip)        # 5aa8 <completed.0>
    1453:	5d                   	pop    %rbp
    1454:	c3                   	ret    
    1455:	0f 1f 00             	nopl   (%rax)
    1458:	c3                   	ret    
    1459:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001460 <frame_dummy>:
    1460:	f3 0f 1e fa          	endbr64 
    1464:	e9 77 ff ff ff       	jmp    13e0 <register_tm_clones>

0000000000001469 <main>:
    1469:	f3 0f 1e fa          	endbr64 
    146d:	53                   	push   %rbx
    146e:	83 ff 01             	cmp    $0x1,%edi
    1471:	0f 84 f8 00 00 00    	je     156f <main+0x106>
    1477:	48 89 f3             	mov    %rsi,%rbx
    147a:	83 ff 02             	cmp    $0x2,%edi
    147d:	0f 85 21 01 00 00    	jne    15a4 <main+0x13b>
    1483:	48 8b 7e 08          	mov    0x8(%rsi),%rdi
    1487:	48 8d 35 76 1b 00 00 	lea    0x1b76(%rip),%rsi        # 3004 <_IO_stdin_used+0x4>
    148e:	e8 6d fe ff ff       	call   1300 <fopen@plt>
    1493:	48 89 05 16 46 00 00 	mov    %rax,0x4616(%rip)        # 5ab0 <infile>
    149a:	48 85 c0             	test   %rax,%rax
    149d:	0f 84 df 00 00 00    	je     1582 <main+0x119>
    14a3:	e8 d6 05 00 00       	call   1a7e <initialize_bomb>
    14a8:	48 8d 3d d9 1b 00 00 	lea    0x1bd9(%rip),%rdi        # 3088 <_IO_stdin_used+0x88>
    14af:	e8 5c fd ff ff       	call   1210 <puts@plt>
    14b4:	48 8d 3d 0d 1c 00 00 	lea    0x1c0d(%rip),%rdi        # 30c8 <_IO_stdin_used+0xc8>
    14bb:	e8 50 fd ff ff       	call   1210 <puts@plt>
    14c0:	e8 cc 07 00 00       	call   1c91 <read_line>
    14c5:	48 89 c7             	mov    %rax,%rdi
    14c8:	e8 fa 00 00 00       	call   15c7 <phase_1>
    14cd:	e8 fd 08 00 00       	call   1dcf <phase_defused>
    14d2:	48 8d 3d 1f 1c 00 00 	lea    0x1c1f(%rip),%rdi        # 30f8 <_IO_stdin_used+0xf8>
    14d9:	e8 32 fd ff ff       	call   1210 <puts@plt>
    14de:	e8 ae 07 00 00       	call   1c91 <read_line>
    14e3:	48 89 c7             	mov    %rax,%rdi
    14e6:	e8 00 01 00 00       	call   15eb <phase_2>
    14eb:	e8 df 08 00 00       	call   1dcf <phase_defused>
    14f0:	48 8d 3d 46 1b 00 00 	lea    0x1b46(%rip),%rdi        # 303d <_IO_stdin_used+0x3d>
    14f7:	e8 14 fd ff ff       	call   1210 <puts@plt>
    14fc:	e8 90 07 00 00       	call   1c91 <read_line>
    1501:	48 89 c7             	mov    %rax,%rdi
    1504:	e8 31 01 00 00       	call   163a <phase_3>
    1509:	e8 c1 08 00 00       	call   1dcf <phase_defused>
    150e:	48 8d 3d 46 1b 00 00 	lea    0x1b46(%rip),%rdi        # 305b <_IO_stdin_used+0x5b>
    1515:	e8 f6 fc ff ff       	call   1210 <puts@plt>
    151a:	e8 72 07 00 00       	call   1c91 <read_line>
    151f:	48 89 c7             	mov    %rax,%rdi
    1522:	e8 ec 01 00 00       	call   1713 <phase_4>
    1527:	e8 a3 08 00 00       	call   1dcf <phase_defused>
    152c:	48 8d 3d f5 1b 00 00 	lea    0x1bf5(%rip),%rdi        # 3128 <_IO_stdin_used+0x128>
    1533:	e8 d8 fc ff ff       	call   1210 <puts@plt>
    1538:	e8 54 07 00 00       	call   1c91 <read_line>
    153d:	48 89 c7             	mov    %rax,%rdi
    1540:	e8 2b 02 00 00       	call   1770 <phase_5>
    1545:	e8 85 08 00 00       	call   1dcf <phase_defused>
    154a:	48 8d 3d 19 1b 00 00 	lea    0x1b19(%rip),%rdi        # 306a <_IO_stdin_used+0x6a>
    1551:	e8 ba fc ff ff       	call   1210 <puts@plt>
    1556:	e8 36 07 00 00       	call   1c91 <read_line>
    155b:	48 89 c7             	mov    %rax,%rdi
    155e:	e8 59 02 00 00       	call   17bc <phase_6>
    1563:	e8 67 08 00 00       	call   1dcf <phase_defused>
    1568:	b8 00 00 00 00       	mov    $0x0,%eax
    156d:	5b                   	pop    %rbx
    156e:	c3                   	ret    
    156f:	48 8b 05 1a 45 00 00 	mov    0x451a(%rip),%rax        # 5a90 <stdin@GLIBC_2.2.5>
    1576:	48 89 05 33 45 00 00 	mov    %rax,0x4533(%rip)        # 5ab0 <infile>
    157d:	e9 21 ff ff ff       	jmp    14a3 <main+0x3a>
    1582:	48 8b 4b 08          	mov    0x8(%rbx),%rcx
    1586:	48 8b 13             	mov    (%rbx),%rdx
    1589:	48 8d 35 76 1a 00 00 	lea    0x1a76(%rip),%rsi        # 3006 <_IO_stdin_used+0x6>
    1590:	bf 01 00 00 00       	mov    $0x1,%edi
    1595:	e8 56 fd ff ff       	call   12f0 <__printf_chk@plt>
    159a:	bf 08 00 00 00       	mov    $0x8,%edi
    159f:	e8 6c fd ff ff       	call   1310 <exit@plt>
    15a4:	48 8b 16             	mov    (%rsi),%rdx
    15a7:	48 8d 35 75 1a 00 00 	lea    0x1a75(%rip),%rsi        # 3023 <_IO_stdin_used+0x23>
    15ae:	bf 01 00 00 00       	mov    $0x1,%edi
    15b3:	b8 00 00 00 00       	mov    $0x0,%eax
    15b8:	e8 33 fd ff ff       	call   12f0 <__printf_chk@plt>
    15bd:	bf 08 00 00 00       	mov    $0x8,%edi
    15c2:	e8 49 fd ff ff       	call   1310 <exit@plt>

00000000000015c7 <phase_1>:
    15c7:	f3 0f 1e fa          	endbr64 
    15cb:	48 83 ec 08          	sub    $0x8,%rsp
    15cf:	48 8d 35 7a 1b 00 00 	lea    0x1b7a(%rip),%rsi        # 3150 <_IO_stdin_used+0x150>
    15d6:	e8 31 04 00 00       	call   1a0c <strings_not_equal>
    15db:	85 c0                	test   %eax,%eax
    15dd:	75 05                	jne    15e4 <phase_1+0x1d>
    15df:	48 83 c4 08          	add    $0x8,%rsp
    15e3:	c3                   	ret    
    15e4:	e8 21 06 00 00       	call   1c0a <explode_bomb>
    15e9:	eb f4                	jmp    15df <phase_1+0x18>

00000000000015eb <phase_2>:
    15eb:	f3 0f 1e fa          	endbr64 
    15ef:	55                   	push   %rbp
    15f0:	53                   	push   %rbx
    15f1:	48 83 ec 28          	sub    $0x28,%rsp
    15f5:	48 89 e6             	mov    %rsp,%rsi
    15f8:	e8 4f 06 00 00       	call   1c4c <read_six_numbers>
    15fd:	83 3c 24 00          	cmpl   $0x0,(%rsp)
    1601:	75 07                	jne    160a <phase_2+0x1f>
    1603:	83 7c 24 04 01       	cmpl   $0x1,0x4(%rsp)
    1608:	74 05                	je     160f <phase_2+0x24>
    160a:	e8 fb 05 00 00       	call   1c0a <explode_bomb>
    160f:	48 89 e3             	mov    %rsp,%rbx
    1612:	48 8d 6c 24 10       	lea    0x10(%rsp),%rbp
    1617:	eb 09                	jmp    1622 <phase_2+0x37>
    1619:	48 83 c3 04          	add    $0x4,%rbx
    161d:	48 39 eb             	cmp    %rbp,%rbx
    1620:	74 11                	je     1633 <phase_2+0x48>
    1622:	8b 43 04             	mov    0x4(%rbx),%eax
    1625:	03 03                	add    (%rbx),%eax
    1627:	39 43 08             	cmp    %eax,0x8(%rbx)
    162a:	74 ed                	je     1619 <phase_2+0x2e>
    162c:	e8 d9 05 00 00       	call   1c0a <explode_bomb>
    1631:	eb e6                	jmp    1619 <phase_2+0x2e>
    1633:	48 83 c4 28          	add    $0x28,%rsp
    1637:	5b                   	pop    %rbx
    1638:	5d                   	pop    %rbp
    1639:	c3                   	ret    

000000000000163a <phase_3>:
    163a:	f3 0f 1e fa          	endbr64 
    163e:	48 83 ec 18          	sub    $0x18,%rsp
    1642:	48 8d 4c 24 08       	lea    0x8(%rsp),%rcx
    1647:	48 8d 54 24 0c       	lea    0xc(%rsp),%rdx
    164c:	48 8d 35 68 1d 00 00 	lea    0x1d68(%rip),%rsi        # 33bb <array.0+0x1db>
    1653:	b8 00 00 00 00       	mov    $0x0,%eax
    1658:	e8 83 fc ff ff       	call   12e0 <__isoc99_sscanf@plt>
    165d:	83 f8 01             	cmp    $0x1,%eax
    1660:	7e 1c                	jle    167e <phase_3+0x44>
    1662:	83 7c 24 0c 07       	cmpl   $0x7,0xc(%rsp)
    1667:	77 56                	ja     16bf <phase_3+0x85>
    1669:	8b 44 24 0c          	mov    0xc(%rsp),%eax
    166d:	48 8d 15 4c 1b 00 00 	lea    0x1b4c(%rip),%rdx        # 31c0 <_IO_stdin_used+0x1c0>
    1674:	48 63 04 82          	movslq (%rdx,%rax,4),%rax
    1678:	48 01 d0             	add    %rdx,%rax
    167b:	3e ff e0             	notrack jmp *%rax
    167e:	e8 87 05 00 00       	call   1c0a <explode_bomb>
    1683:	eb dd                	jmp    1662 <phase_3+0x28>
    1685:	b8 30 02 00 00       	mov    $0x230,%eax
    168a:	39 44 24 08          	cmp    %eax,0x8(%rsp)
    168e:	75 42                	jne    16d2 <phase_3+0x98>
    1690:	48 83 c4 18          	add    $0x18,%rsp
    1694:	c3                   	ret    
    1695:	b8 4e 00 00 00       	mov    $0x4e,%eax
    169a:	eb ee                	jmp    168a <phase_3+0x50>
    169c:	b8 16 02 00 00       	mov    $0x216,%eax
    16a1:	eb e7                	jmp    168a <phase_3+0x50>
    16a3:	b8 fd 02 00 00       	mov    $0x2fd,%eax
    16a8:	eb e0                	jmp    168a <phase_3+0x50>
    16aa:	b8 11 02 00 00       	mov    $0x211,%eax
    16af:	eb d9                	jmp    168a <phase_3+0x50>
    16b1:	b8 ed 01 00 00       	mov    $0x1ed,%eax
    16b6:	eb d2                	jmp    168a <phase_3+0x50>
    16b8:	b8 e7 00 00 00       	mov    $0xe7,%eax
    16bd:	eb cb                	jmp    168a <phase_3+0x50>
    16bf:	e8 46 05 00 00       	call   1c0a <explode_bomb>
    16c4:	b8 00 00 00 00       	mov    $0x0,%eax
    16c9:	eb bf                	jmp    168a <phase_3+0x50>
    16cb:	b8 ab 00 00 00       	mov    $0xab,%eax
    16d0:	eb b8                	jmp    168a <phase_3+0x50>
    16d2:	e8 33 05 00 00       	call   1c0a <explode_bomb>
    16d7:	eb b7                	jmp    1690 <phase_3+0x56>

00000000000016d9 <func4>:
    16d9:	f3 0f 1e fa          	endbr64 
    16dd:	48 83 ec 08          	sub    $0x8,%rsp
    16e1:	89 d1                	mov    %edx,%ecx
    16e3:	29 f1                	sub    %esi,%ecx
    16e5:	d1 e9                	shr    %ecx
    16e7:	01 f1                	add    %esi,%ecx
    16e9:	39 f9                	cmp    %edi,%ecx
    16eb:	77 0c                	ja     16f9 <func4+0x20>
    16ed:	b8 00 00 00 00       	mov    $0x0,%eax
    16f2:	72 11                	jb     1705 <func4+0x2c>
    16f4:	48 83 c4 08          	add    $0x8,%rsp
    16f8:	c3                   	ret    
    16f9:	8d 51 ff             	lea    -0x1(%rcx),%edx
    16fc:	e8 d8 ff ff ff       	call   16d9 <func4>
    1701:	01 c0                	add    %eax,%eax
    1703:	eb ef                	jmp    16f4 <func4+0x1b>
    1705:	8d 71 01             	lea    0x1(%rcx),%esi
    1708:	e8 cc ff ff ff       	call   16d9 <func4>
    170d:	8d 44 00 01          	lea    0x1(%rax,%rax,1),%eax
    1711:	eb e1                	jmp    16f4 <func4+0x1b>

0000000000001713 <phase_4>:
    1713:	f3 0f 1e fa          	endbr64 
    1717:	48 83 ec 18          	sub    $0x18,%rsp
    171b:	48 8d 4c 24 08       	lea    0x8(%rsp),%rcx
    1720:	48 8d 54 24 0c       	lea    0xc(%rsp),%rdx
    1725:	48 8d 35 8f 1c 00 00 	lea    0x1c8f(%rip),%rsi        # 33bb <array.0+0x1db>
    172c:	b8 00 00 00 00       	mov    $0x0,%eax
    1731:	e8 aa fb ff ff       	call   12e0 <__isoc99_sscanf@plt>
    1736:	83 f8 02             	cmp    $0x2,%eax
    1739:	75 07                	jne    1742 <phase_4+0x2f>
    173b:	83 7c 24 0c 0e       	cmpl   $0xe,0xc(%rsp)
    1740:	76 05                	jbe    1747 <phase_4+0x34>
    1742:	e8 c3 04 00 00       	call   1c0a <explode_bomb>
    1747:	ba 0e 00 00 00       	mov    $0xe,%edx
    174c:	be 00 00 00 00       	mov    $0x0,%esi
    1751:	8b 7c 24 0c          	mov    0xc(%rsp),%edi
    1755:	e8 7f ff ff ff       	call   16d9 <func4>
    175a:	83 f8 04             	cmp    $0x4,%eax
    175d:	75 07                	jne    1766 <phase_4+0x53>
    175f:	83 7c 24 08 04       	cmpl   $0x4,0x8(%rsp)
    1764:	74 05                	je     176b <phase_4+0x58>
    1766:	e8 9f 04 00 00       	call   1c0a <explode_bomb>
    176b:	48 83 c4 18          	add    $0x18,%rsp
    176f:	c3                   	ret    

0000000000001770 <phase_5>:
    1770:	f3 0f 1e fa          	endbr64 
    1774:	53                   	push   %rbx
    1775:	48 89 fb             	mov    %rdi,%rbx
    1778:	e8 6e 02 00 00       	call   19eb <string_length>
    177d:	83 f8 06             	cmp    $0x6,%eax
    1780:	75 2c                	jne    17ae <phase_5+0x3e>
    1782:	48 89 d8             	mov    %rbx,%rax
    1785:	48 8d 7b 06          	lea    0x6(%rbx),%rdi
    1789:	b9 00 00 00 00       	mov    $0x0,%ecx
    178e:	48 8d 35 4b 1a 00 00 	lea    0x1a4b(%rip),%rsi        # 31e0 <array.0>
    1795:	0f b6 10             	movzbl (%rax),%edx
    1798:	83 e2 0f             	and    $0xf,%edx
    179b:	03 0c 96             	add    (%rsi,%rdx,4),%ecx
    179e:	48 83 c0 01          	add    $0x1,%rax
    17a2:	48 39 f8             	cmp    %rdi,%rax
    17a5:	75 ee                	jne    1795 <phase_5+0x25>
    17a7:	83 f9 24             	cmp    $0x24,%ecx
    17aa:	75 09                	jne    17b5 <phase_5+0x45>
    17ac:	5b                   	pop    %rbx
    17ad:	c3                   	ret    
    17ae:	e8 57 04 00 00       	call   1c0a <explode_bomb>
    17b3:	eb cd                	jmp    1782 <phase_5+0x12>
    17b5:	e8 50 04 00 00       	call   1c0a <explode_bomb>
    17ba:	eb f0                	jmp    17ac <phase_5+0x3c>

00000000000017bc <phase_6>:
    17bc:	f3 0f 1e fa          	endbr64 
    17c0:	41 56                	push   %r14
    17c2:	41 55                	push   %r13
    17c4:	41 54                	push   %r12
    17c6:	55                   	push   %rbp
    17c7:	53                   	push   %rbx
    17c8:	48 83 ec 50          	sub    $0x50,%rsp
    17cc:	4c 8d 6c 24 30       	lea    0x30(%rsp),%r13
    17d1:	4c 89 ee             	mov    %r13,%rsi
    17d4:	e8 73 04 00 00       	call   1c4c <read_six_numbers>
    17d9:	41 be 01 00 00 00    	mov    $0x1,%r14d
    17df:	4d 89 ec             	mov    %r13,%r12
    17e2:	eb 28                	jmp    180c <phase_6+0x50>
    17e4:	e8 21 04 00 00       	call   1c0a <explode_bomb>
    17e9:	eb 30                	jmp    181b <phase_6+0x5f>
    17eb:	48 83 c3 01          	add    $0x1,%rbx
    17ef:	83 fb 05             	cmp    $0x5,%ebx
    17f2:	7f 10                	jg     1804 <phase_6+0x48>
    17f4:	41 8b 04 9c          	mov    (%r12,%rbx,4),%eax
    17f8:	39 45 00             	cmp    %eax,0x0(%rbp)
    17fb:	75 ee                	jne    17eb <phase_6+0x2f>
    17fd:	e8 08 04 00 00       	call   1c0a <explode_bomb>
    1802:	eb e7                	jmp    17eb <phase_6+0x2f>
    1804:	49 83 c6 01          	add    $0x1,%r14
    1808:	49 83 c5 04          	add    $0x4,%r13
    180c:	4c 89 ed             	mov    %r13,%rbp
    180f:	41 8b 45 00          	mov    0x0(%r13),%eax
    1813:	83 e8 01             	sub    $0x1,%eax
    1816:	83 f8 05             	cmp    $0x5,%eax
    1819:	77 c9                	ja     17e4 <phase_6+0x28>
    181b:	41 83 fe 05          	cmp    $0x5,%r14d
    181f:	7f 05                	jg     1826 <phase_6+0x6a>
    1821:	4c 89 f3             	mov    %r14,%rbx
    1824:	eb ce                	jmp    17f4 <phase_6+0x38>
    1826:	be 00 00 00 00       	mov    $0x0,%esi
    182b:	8b 4c b4 30          	mov    0x30(%rsp,%rsi,4),%ecx
    182f:	b8 01 00 00 00       	mov    $0x1,%eax
    1834:	48 8d 15 f5 3d 00 00 	lea    0x3df5(%rip),%rdx        # 5630 <node1>
    183b:	83 f9 01             	cmp    $0x1,%ecx
    183e:	7e 0b                	jle    184b <phase_6+0x8f>
    1840:	48 8b 52 08          	mov    0x8(%rdx),%rdx
    1844:	83 c0 01             	add    $0x1,%eax
    1847:	39 c8                	cmp    %ecx,%eax
    1849:	75 f5                	jne    1840 <phase_6+0x84>
    184b:	48 89 14 f4          	mov    %rdx,(%rsp,%rsi,8)
    184f:	48 83 c6 01          	add    $0x1,%rsi
    1853:	48 83 fe 06          	cmp    $0x6,%rsi
    1857:	75 d2                	jne    182b <phase_6+0x6f>
    1859:	48 8b 1c 24          	mov    (%rsp),%rbx
    185d:	48 8b 44 24 08       	mov    0x8(%rsp),%rax
    1862:	48 89 43 08          	mov    %rax,0x8(%rbx)
    1866:	48 8b 54 24 10       	mov    0x10(%rsp),%rdx
    186b:	48 89 50 08          	mov    %rdx,0x8(%rax)
    186f:	48 8b 44 24 18       	mov    0x18(%rsp),%rax
    1874:	48 89 42 08          	mov    %rax,0x8(%rdx)
    1878:	48 8b 54 24 20       	mov    0x20(%rsp),%rdx
    187d:	48 89 50 08          	mov    %rdx,0x8(%rax)
    1881:	48 8b 44 24 28       	mov    0x28(%rsp),%rax
    1886:	48 89 42 08          	mov    %rax,0x8(%rdx)
    188a:	48 c7 40 08 00 00 00 	movq   $0x0,0x8(%rax)
    1891:	00 
    1892:	bd 05 00 00 00       	mov    $0x5,%ebp
    1897:	eb 09                	jmp    18a2 <phase_6+0xe6>
    1899:	48 8b 5b 08          	mov    0x8(%rbx),%rbx
    189d:	83 ed 01             	sub    $0x1,%ebp
    18a0:	74 11                	je     18b3 <phase_6+0xf7>
    18a2:	48 8b 43 08          	mov    0x8(%rbx),%rax
    18a6:	8b 00                	mov    (%rax),%eax
    18a8:	39 03                	cmp    %eax,(%rbx)
    18aa:	7e ed                	jle    1899 <phase_6+0xdd>
    18ac:	e8 59 03 00 00       	call   1c0a <explode_bomb>
    18b1:	eb e6                	jmp    1899 <phase_6+0xdd>
    18b3:	48 83 c4 50          	add    $0x50,%rsp
    18b7:	5b                   	pop    %rbx
    18b8:	5d                   	pop    %rbp
    18b9:	41 5c                	pop    %r12
    18bb:	41 5d                	pop    %r13
    18bd:	41 5e                	pop    %r14
    18bf:	c3                   	ret    

00000000000018c0 <fun7>:
    18c0:	f3 0f 1e fa          	endbr64 
    18c4:	48 85 ff             	test   %rdi,%rdi
    18c7:	74 32                	je     18fb <fun7+0x3b>
    18c9:	48 83 ec 08          	sub    $0x8,%rsp
    18cd:	8b 17                	mov    (%rdi),%edx
    18cf:	39 f2                	cmp    %esi,%edx
    18d1:	7f 0c                	jg     18df <fun7+0x1f>
    18d3:	b8 00 00 00 00       	mov    $0x0,%eax
    18d8:	75 12                	jne    18ec <fun7+0x2c>
    18da:	48 83 c4 08          	add    $0x8,%rsp
    18de:	c3                   	ret    
    18df:	48 8b 7f 08          	mov    0x8(%rdi),%rdi
    18e3:	e8 d8 ff ff ff       	call   18c0 <fun7>
    18e8:	01 c0                	add    %eax,%eax
    18ea:	eb ee                	jmp    18da <fun7+0x1a>
    18ec:	48 8b 7f 10          	mov    0x10(%rdi),%rdi
    18f0:	e8 cb ff ff ff       	call   18c0 <fun7>
    18f5:	8d 44 00 01          	lea    0x1(%rax,%rax,1),%eax
    18f9:	eb df                	jmp    18da <fun7+0x1a>
    18fb:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    1900:	c3                   	ret    

0000000000001901 <secret_phase>:
    1901:	f3 0f 1e fa          	endbr64 
    1905:	53                   	push   %rbx
    1906:	e8 86 03 00 00       	call   1c91 <read_line>
    190b:	48 89 c7             	mov    %rax,%rdi
    190e:	ba 0a 00 00 00       	mov    $0xa,%edx
    1913:	be 00 00 00 00       	mov    $0x0,%esi
    1918:	e8 a3 f9 ff ff       	call   12c0 <strtol@plt>
    191d:	89 c3                	mov    %eax,%ebx
    191f:	83 e8 01             	sub    $0x1,%eax
    1922:	3d e8 03 00 00       	cmp    $0x3e8,%eax
    1927:	77 25                	ja     194e <secret_phase+0x4d>
    1929:	89 de                	mov    %ebx,%esi
    192b:	48 8d 3d 1e 3c 00 00 	lea    0x3c1e(%rip),%rdi        # 5550 <n1>
    1932:	e8 89 ff ff ff       	call   18c0 <fun7>
    1937:	85 c0                	test   %eax,%eax
    1939:	75 1a                	jne    1955 <secret_phase+0x54>
    193b:	48 8d 3d 46 18 00 00 	lea    0x1846(%rip),%rdi        # 3188 <_IO_stdin_used+0x188>
    1942:	e8 c9 f8 ff ff       	call   1210 <puts@plt>
    1947:	e8 83 04 00 00       	call   1dcf <phase_defused>
    194c:	5b                   	pop    %rbx
    194d:	c3                   	ret    
    194e:	e8 b7 02 00 00       	call   1c0a <explode_bomb>
    1953:	eb d4                	jmp    1929 <secret_phase+0x28>
    1955:	e8 b0 02 00 00       	call   1c0a <explode_bomb>
    195a:	eb df                	jmp    193b <secret_phase+0x3a>

000000000000195c <sig_handler>:
    195c:	f3 0f 1e fa          	endbr64 
    1960:	50                   	push   %rax
    1961:	58                   	pop    %rax
    1962:	48 83 ec 08          	sub    $0x8,%rsp
    1966:	48 8d 3d b3 18 00 00 	lea    0x18b3(%rip),%rdi        # 3220 <array.0+0x40>
    196d:	e8 9e f8 ff ff       	call   1210 <puts@plt>
    1972:	bf 03 00 00 00       	mov    $0x3,%edi
    1977:	e8 c4 f9 ff ff       	call   1340 <sleep@plt>
    197c:	48 8d 35 ce 19 00 00 	lea    0x19ce(%rip),%rsi        # 3351 <array.0+0x171>
    1983:	bf 01 00 00 00       	mov    $0x1,%edi
    1988:	b8 00 00 00 00       	mov    $0x0,%eax
    198d:	e8 5e f9 ff ff       	call   12f0 <__printf_chk@plt>
    1992:	48 8b 3d e7 40 00 00 	mov    0x40e7(%rip),%rdi        # 5a80 <stdout@GLIBC_2.2.5>
    1999:	e8 32 f9 ff ff       	call   12d0 <fflush@plt>
    199e:	bf 01 00 00 00       	mov    $0x1,%edi
    19a3:	e8 98 f9 ff ff       	call   1340 <sleep@plt>
    19a8:	48 8d 3d aa 19 00 00 	lea    0x19aa(%rip),%rdi        # 3359 <array.0+0x179>
    19af:	e8 5c f8 ff ff       	call   1210 <puts@plt>
    19b4:	bf 10 00 00 00       	mov    $0x10,%edi
    19b9:	e8 52 f9 ff ff       	call   1310 <exit@plt>

00000000000019be <invalid_phase>:
    19be:	f3 0f 1e fa          	endbr64 
    19c2:	50                   	push   %rax
    19c3:	58                   	pop    %rax
    19c4:	48 83 ec 08          	sub    $0x8,%rsp
    19c8:	48 89 fa             	mov    %rdi,%rdx
    19cb:	48 8d 35 8f 19 00 00 	lea    0x198f(%rip),%rsi        # 3361 <array.0+0x181>
    19d2:	bf 01 00 00 00       	mov    $0x1,%edi
    19d7:	b8 00 00 00 00       	mov    $0x0,%eax
    19dc:	e8 0f f9 ff ff       	call   12f0 <__printf_chk@plt>
    19e1:	bf 08 00 00 00       	mov    $0x8,%edi
    19e6:	e8 25 f9 ff ff       	call   1310 <exit@plt>

00000000000019eb <string_length>:
    19eb:	f3 0f 1e fa          	endbr64 
    19ef:	80 3f 00             	cmpb   $0x0,(%rdi)
    19f2:	74 12                	je     1a06 <string_length+0x1b>
    19f4:	b8 00 00 00 00       	mov    $0x0,%eax
    19f9:	48 83 c7 01          	add    $0x1,%rdi
    19fd:	83 c0 01             	add    $0x1,%eax
    1a00:	80 3f 00             	cmpb   $0x0,(%rdi)
    1a03:	75 f4                	jne    19f9 <string_length+0xe>
    1a05:	c3                   	ret    
    1a06:	b8 00 00 00 00       	mov    $0x0,%eax
    1a0b:	c3                   	ret    

0000000000001a0c <strings_not_equal>:
    1a0c:	f3 0f 1e fa          	endbr64 
    1a10:	41 54                	push   %r12
    1a12:	55                   	push   %rbp
    1a13:	53                   	push   %rbx
    1a14:	48 89 fb             	mov    %rdi,%rbx
    1a17:	48 89 f5             	mov    %rsi,%rbp
    1a1a:	e8 cc ff ff ff       	call   19eb <string_length>
    1a1f:	41 89 c4             	mov    %eax,%r12d
    1a22:	48 89 ef             	mov    %rbp,%rdi
    1a25:	e8 c1 ff ff ff       	call   19eb <string_length>
    1a2a:	89 c2                	mov    %eax,%edx
    1a2c:	b8 01 00 00 00       	mov    $0x1,%eax
    1a31:	41 39 d4             	cmp    %edx,%r12d
    1a34:	75 31                	jne    1a67 <strings_not_equal+0x5b>
    1a36:	0f b6 13             	movzbl (%rbx),%edx
    1a39:	84 d2                	test   %dl,%dl
    1a3b:	74 1e                	je     1a5b <strings_not_equal+0x4f>
    1a3d:	b8 00 00 00 00       	mov    $0x0,%eax
    1a42:	38 54 05 00          	cmp    %dl,0x0(%rbp,%rax,1)
    1a46:	75 1a                	jne    1a62 <strings_not_equal+0x56>
    1a48:	48 83 c0 01          	add    $0x1,%rax
    1a4c:	0f b6 14 03          	movzbl (%rbx,%rax,1),%edx
    1a50:	84 d2                	test   %dl,%dl
    1a52:	75 ee                	jne    1a42 <strings_not_equal+0x36>
    1a54:	b8 00 00 00 00       	mov    $0x0,%eax
    1a59:	eb 0c                	jmp    1a67 <strings_not_equal+0x5b>
    1a5b:	b8 00 00 00 00       	mov    $0x0,%eax
    1a60:	eb 05                	jmp    1a67 <strings_not_equal+0x5b>
    1a62:	b8 01 00 00 00       	mov    $0x1,%eax
    1a67:	5b                   	pop    %rbx
    1a68:	5d                   	pop    %rbp
    1a69:	41 5c                	pop    %r12
    1a6b:	c3                   	ret    

0000000000001a6c <strings_are_equal>:
    1a6c:	f3 0f 1e fa          	endbr64 
    1a70:	e8 97 ff ff ff       	call   1a0c <strings_not_equal>
    1a75:	85 c0                	test   %eax,%eax
    1a77:	0f 94 c0             	sete   %al
    1a7a:	0f b6 c0             	movzbl %al,%eax
    1a7d:	c3                   	ret    

0000000000001a7e <initialize_bomb>:
    1a7e:	f3 0f 1e fa          	endbr64 
    1a82:	48 83 ec 08          	sub    $0x8,%rsp
    1a86:	48 8d 35 cf fe ff ff 	lea    -0x131(%rip),%rsi        # 195c <sig_handler>
    1a8d:	bf 02 00 00 00       	mov    $0x2,%edi
    1a92:	e8 f9 f7 ff ff       	call   1290 <signal@plt>
    1a97:	48 83 c4 08          	add    $0x8,%rsp
    1a9b:	c3                   	ret    

0000000000001a9c <initialize_bomb_solve>:
    1a9c:	f3 0f 1e fa          	endbr64 
    1aa0:	c3                   	ret    

0000000000001aa1 <blank_line>:
    1aa1:	f3 0f 1e fa          	endbr64 
    1aa5:	55                   	push   %rbp
    1aa6:	53                   	push   %rbx
    1aa7:	48 83 ec 08          	sub    $0x8,%rsp
    1aab:	48 89 fd             	mov    %rdi,%rbp
    1aae:	0f b6 5d 00          	movzbl 0x0(%rbp),%ebx
    1ab2:	84 db                	test   %bl,%bl
    1ab4:	74 1e                	je     1ad4 <blank_line+0x33>
    1ab6:	e8 95 f8 ff ff       	call   1350 <__ctype_b_loc@plt>
    1abb:	48 83 c5 01          	add    $0x1,%rbp
    1abf:	48 0f be db          	movsbq %bl,%rbx
    1ac3:	48 8b 00             	mov    (%rax),%rax
    1ac6:	f6 44 58 01 20       	testb  $0x20,0x1(%rax,%rbx,2)
    1acb:	75 e1                	jne    1aae <blank_line+0xd>
    1acd:	b8 00 00 00 00       	mov    $0x0,%eax
    1ad2:	eb 05                	jmp    1ad9 <blank_line+0x38>
    1ad4:	b8 01 00 00 00       	mov    $0x1,%eax
    1ad9:	48 83 c4 08          	add    $0x8,%rsp
    1add:	5b                   	pop    %rbx
    1ade:	5d                   	pop    %rbp
    1adf:	c3                   	ret    

0000000000001ae0 <skip>:
    1ae0:	f3 0f 1e fa          	endbr64 
    1ae4:	55                   	push   %rbp
    1ae5:	53                   	push   %rbx
    1ae6:	48 83 ec 08          	sub    $0x8,%rsp
    1aea:	48 8d 2d 4f 40 00 00 	lea    0x404f(%rip),%rbp        # 5b40 <input_strings>
    1af1:	48 63 15 40 40 00 00 	movslq 0x4040(%rip),%rdx        # 5b38 <num_input_strings>
    1af8:	48 89 d0             	mov    %rdx,%rax
    1afb:	48 c1 e0 04          	shl    $0x4,%rax
    1aff:	48 29 d0             	sub    %rdx,%rax
    1b02:	48 8d 7c c5 00       	lea    0x0(%rbp,%rax,8),%rdi
    1b07:	48 8b 15 a2 3f 00 00 	mov    0x3fa2(%rip),%rdx        # 5ab0 <infile>
    1b0e:	be 78 00 00 00       	mov    $0x78,%esi
    1b13:	e8 58 f7 ff ff       	call   1270 <fgets@plt>
    1b18:	48 89 c3             	mov    %rax,%rbx
    1b1b:	48 85 c0             	test   %rax,%rax
    1b1e:	74 0c                	je     1b2c <skip+0x4c>
    1b20:	48 89 c7             	mov    %rax,%rdi
    1b23:	e8 79 ff ff ff       	call   1aa1 <blank_line>
    1b28:	85 c0                	test   %eax,%eax
    1b2a:	75 c5                	jne    1af1 <skip+0x11>
    1b2c:	48 89 d8             	mov    %rbx,%rax
    1b2f:	48 83 c4 08          	add    $0x8,%rsp
    1b33:	5b                   	pop    %rbx
    1b34:	5d                   	pop    %rbp
    1b35:	c3                   	ret    

0000000000001b36 <send_msg>:
    1b36:	f3 0f 1e fa          	endbr64 
    1b3a:	53                   	push   %rbx
    1b3b:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1b42:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1b47:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1b4e:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1b53:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1b5a:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1b5f:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1b66:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1b6b:	8b 0d c7 3f 00 00    	mov    0x3fc7(%rip),%ecx        # 5b38 <num_input_strings>
    1b71:	8d 41 ff             	lea    -0x1(%rcx),%eax
    1b74:	48 98                	cltq   
    1b76:	48 89 c2             	mov    %rax,%rdx
    1b79:	48 c1 e2 04          	shl    $0x4,%rdx
    1b7d:	48 29 c2             	sub    %rax,%rdx
    1b80:	48 8d 05 b9 3f 00 00 	lea    0x3fb9(%rip),%rax        # 5b40 <input_strings>
    1b87:	48 8d 04 d0          	lea    (%rax,%rdx,8),%rax
    1b8b:	85 ff                	test   %edi,%edi
    1b8d:	4c 8d 0d de 17 00 00 	lea    0x17de(%rip),%r9        # 3372 <array.0+0x192>
    1b94:	48 8d 15 df 17 00 00 	lea    0x17df(%rip),%rdx        # 337a <array.0+0x19a>
    1b9b:	4c 0f 44 ca          	cmove  %rdx,%r9
    1b9f:	48 8d 9c 24 00 20 00 	lea    0x2000(%rsp),%rbx
    1ba6:	00 
    1ba7:	50                   	push   %rax
    1ba8:	51                   	push   %rcx
    1ba9:	44 8b 05 90 39 00 00 	mov    0x3990(%rip),%r8d        # 5540 <bomb_id>
    1bb0:	48 8d 0d cc 17 00 00 	lea    0x17cc(%rip),%rcx        # 3383 <array.0+0x1a3>
    1bb7:	ba 00 20 00 00       	mov    $0x2000,%edx
    1bbc:	be 01 00 00 00       	mov    $0x1,%esi
    1bc1:	48 89 df             	mov    %rbx,%rdi
    1bc4:	b8 00 00 00 00       	mov    $0x0,%eax
    1bc9:	e8 92 f7 ff ff       	call   1360 <__sprintf_chk@plt>
    1bce:	48 8d 4c 24 10       	lea    0x10(%rsp),%rcx
    1bd3:	ba 00 00 00 00       	mov    $0x0,%edx
    1bd8:	48 89 de             	mov    %rbx,%rsi
    1bdb:	48 8d 3d 5e 35 00 00 	lea    0x355e(%rip),%rdi        # 5140 <userid>
    1be2:	e8 67 0d 00 00       	call   294e <driver_post>
    1be7:	48 83 c4 10          	add    $0x10,%rsp
    1beb:	85 c0                	test   %eax,%eax
    1bed:	78 09                	js     1bf8 <send_msg+0xc2>
    1bef:	48 81 c4 00 40 00 00 	add    $0x4000,%rsp
    1bf6:	5b                   	pop    %rbx
    1bf7:	c3                   	ret    
    1bf8:	48 89 e7             	mov    %rsp,%rdi
    1bfb:	e8 10 f6 ff ff       	call   1210 <puts@plt>
    1c00:	bf 00 00 00 00       	mov    $0x0,%edi
    1c05:	e8 06 f7 ff ff       	call   1310 <exit@plt>

0000000000001c0a <explode_bomb>:
    1c0a:	f3 0f 1e fa          	endbr64 
    1c0e:	50                   	push   %rax
    1c0f:	58                   	pop    %rax
    1c10:	48 83 ec 08          	sub    $0x8,%rsp
    1c14:	48 8d 3d 74 17 00 00 	lea    0x1774(%rip),%rdi        # 338f <array.0+0x1af>
    1c1b:	e8 f0 f5 ff ff       	call   1210 <puts@plt>
    1c20:	48 8d 3d 71 17 00 00 	lea    0x1771(%rip),%rdi        # 3398 <array.0+0x1b8>
    1c27:	e8 e4 f5 ff ff       	call   1210 <puts@plt>
    1c2c:	bf 00 00 00 00       	mov    $0x0,%edi
    1c31:	e8 00 ff ff ff       	call   1b36 <send_msg>
    1c36:	48 8d 3d 1b 16 00 00 	lea    0x161b(%rip),%rdi        # 3258 <array.0+0x78>
    1c3d:	e8 ce f5 ff ff       	call   1210 <puts@plt>
    1c42:	bf 08 00 00 00       	mov    $0x8,%edi
    1c47:	e8 c4 f6 ff ff       	call   1310 <exit@plt>

0000000000001c4c <read_six_numbers>:
    1c4c:	f3 0f 1e fa          	endbr64 
    1c50:	48 83 ec 08          	sub    $0x8,%rsp
    1c54:	48 89 f2             	mov    %rsi,%rdx
    1c57:	48 8d 4e 04          	lea    0x4(%rsi),%rcx
    1c5b:	48 8d 46 14          	lea    0x14(%rsi),%rax
    1c5f:	50                   	push   %rax
    1c60:	48 8d 46 10          	lea    0x10(%rsi),%rax
    1c64:	50                   	push   %rax
    1c65:	4c 8d 4e 0c          	lea    0xc(%rsi),%r9
    1c69:	4c 8d 46 08          	lea    0x8(%rsi),%r8
    1c6d:	48 8d 35 3b 17 00 00 	lea    0x173b(%rip),%rsi        # 33af <array.0+0x1cf>
    1c74:	b8 00 00 00 00       	mov    $0x0,%eax
    1c79:	e8 62 f6 ff ff       	call   12e0 <__isoc99_sscanf@plt>
    1c7e:	48 83 c4 10          	add    $0x10,%rsp
    1c82:	83 f8 05             	cmp    $0x5,%eax
    1c85:	7e 05                	jle    1c8c <read_six_numbers+0x40>
    1c87:	48 83 c4 08          	add    $0x8,%rsp
    1c8b:	c3                   	ret    
    1c8c:	e8 79 ff ff ff       	call   1c0a <explode_bomb>

0000000000001c91 <read_line>:
    1c91:	f3 0f 1e fa          	endbr64 
    1c95:	55                   	push   %rbp
    1c96:	53                   	push   %rbx
    1c97:	48 83 ec 08          	sub    $0x8,%rsp
    1c9b:	b8 00 00 00 00       	mov    $0x0,%eax
    1ca0:	e8 3b fe ff ff       	call   1ae0 <skip>
    1ca5:	48 85 c0             	test   %rax,%rax
    1ca8:	74 63                	je     1d0d <read_line+0x7c>
    1caa:	8b 1d 88 3e 00 00    	mov    0x3e88(%rip),%ebx        # 5b38 <num_input_strings>
    1cb0:	48 63 d3             	movslq %ebx,%rdx
    1cb3:	48 89 d0             	mov    %rdx,%rax
    1cb6:	48 c1 e0 04          	shl    $0x4,%rax
    1cba:	48 29 d0             	sub    %rdx,%rax
    1cbd:	48 8d 15 7c 3e 00 00 	lea    0x3e7c(%rip),%rdx        # 5b40 <input_strings>
    1cc4:	48 8d 2c c2          	lea    (%rdx,%rax,8),%rbp
    1cc8:	48 89 ef             	mov    %rbp,%rdi
    1ccb:	e8 60 f5 ff ff       	call   1230 <strlen@plt>
    1cd0:	83 f8 76             	cmp    $0x76,%eax
    1cd3:	0f 8f ac 00 00 00    	jg     1d85 <read_line+0xf4>
    1cd9:	83 e8 01             	sub    $0x1,%eax
    1cdc:	48 98                	cltq   
    1cde:	48 63 cb             	movslq %ebx,%rcx
    1ce1:	48 89 ca             	mov    %rcx,%rdx
    1ce4:	48 c1 e2 04          	shl    $0x4,%rdx
    1ce8:	48 29 ca             	sub    %rcx,%rdx
    1ceb:	48 8d 0d 4e 3e 00 00 	lea    0x3e4e(%rip),%rcx        # 5b40 <input_strings>
    1cf2:	48 8d 14 d1          	lea    (%rcx,%rdx,8),%rdx
    1cf6:	c6 04 02 00          	movb   $0x0,(%rdx,%rax,1)
    1cfa:	83 c3 01             	add    $0x1,%ebx
    1cfd:	89 1d 35 3e 00 00    	mov    %ebx,0x3e35(%rip)        # 5b38 <num_input_strings>
    1d03:	48 89 e8             	mov    %rbp,%rax
    1d06:	48 83 c4 08          	add    $0x8,%rsp
    1d0a:	5b                   	pop    %rbx
    1d0b:	5d                   	pop    %rbp
    1d0c:	c3                   	ret    
    1d0d:	48 8b 05 7c 3d 00 00 	mov    0x3d7c(%rip),%rax        # 5a90 <stdin@GLIBC_2.2.5>
    1d14:	48 39 05 95 3d 00 00 	cmp    %rax,0x3d95(%rip)        # 5ab0 <infile>
    1d1b:	74 1b                	je     1d38 <read_line+0xa7>
    1d1d:	48 8d 3d bb 16 00 00 	lea    0x16bb(%rip),%rdi        # 33df <array.0+0x1ff>
    1d24:	e8 b7 f4 ff ff       	call   11e0 <getenv@plt>
    1d29:	48 85 c0             	test   %rax,%rax
    1d2c:	74 20                	je     1d4e <read_line+0xbd>
    1d2e:	bf 00 00 00 00       	mov    $0x0,%edi
    1d33:	e8 d8 f5 ff ff       	call   1310 <exit@plt>
    1d38:	48 8d 3d 82 16 00 00 	lea    0x1682(%rip),%rdi        # 33c1 <array.0+0x1e1>
    1d3f:	e8 cc f4 ff ff       	call   1210 <puts@plt>
    1d44:	bf 08 00 00 00       	mov    $0x8,%edi
    1d49:	e8 c2 f5 ff ff       	call   1310 <exit@plt>
    1d4e:	48 8b 05 3b 3d 00 00 	mov    0x3d3b(%rip),%rax        # 5a90 <stdin@GLIBC_2.2.5>
    1d55:	48 89 05 54 3d 00 00 	mov    %rax,0x3d54(%rip)        # 5ab0 <infile>
    1d5c:	b8 00 00 00 00       	mov    $0x0,%eax
    1d61:	e8 7a fd ff ff       	call   1ae0 <skip>
    1d66:	48 85 c0             	test   %rax,%rax
    1d69:	0f 85 3b ff ff ff    	jne    1caa <read_line+0x19>
    1d6f:	48 8d 3d 4b 16 00 00 	lea    0x164b(%rip),%rdi        # 33c1 <array.0+0x1e1>
    1d76:	e8 95 f4 ff ff       	call   1210 <puts@plt>
    1d7b:	bf 00 00 00 00       	mov    $0x0,%edi
    1d80:	e8 8b f5 ff ff       	call   1310 <exit@plt>
    1d85:	48 8d 3d 5e 16 00 00 	lea    0x165e(%rip),%rdi        # 33ea <array.0+0x20a>
    1d8c:	e8 7f f4 ff ff       	call   1210 <puts@plt>
    1d91:	8b 05 a1 3d 00 00    	mov    0x3da1(%rip),%eax        # 5b38 <num_input_strings>
    1d97:	8d 50 01             	lea    0x1(%rax),%edx
    1d9a:	89 15 98 3d 00 00    	mov    %edx,0x3d98(%rip)        # 5b38 <num_input_strings>
    1da0:	48 98                	cltq   
    1da2:	48 6b c0 78          	imul   $0x78,%rax,%rax
    1da6:	48 8d 15 93 3d 00 00 	lea    0x3d93(%rip),%rdx        # 5b40 <input_strings>
    1dad:	48 be 2a 2a 2a 74 72 	movabs $0x636e7572742a2a2a,%rsi
    1db4:	75 6e 63 
    1db7:	48 bf 61 74 65 64 2a 	movabs $0x2a2a2a64657461,%rdi
    1dbe:	2a 2a 00 
    1dc1:	48 89 34 02          	mov    %rsi,(%rdx,%rax,1)
    1dc5:	48 89 7c 02 08       	mov    %rdi,0x8(%rdx,%rax,1)
    1dca:	e8 3b fe ff ff       	call   1c0a <explode_bomb>

0000000000001dcf <phase_defused>:
    1dcf:	f3 0f 1e fa          	endbr64 
    1dd3:	48 81 ec 98 00 00 00 	sub    $0x98,%rsp
    1dda:	bf 01 00 00 00       	mov    $0x1,%edi
    1ddf:	e8 52 fd ff ff       	call   1b36 <send_msg>
    1de4:	83 3d 4d 3d 00 00 06 	cmpl   $0x6,0x3d4d(%rip)        # 5b38 <num_input_strings>
    1deb:	74 08                	je     1df5 <phase_defused+0x26>
    1ded:	48 81 c4 98 00 00 00 	add    $0x98,%rsp
    1df4:	c3                   	ret    
    1df5:	48 8d 4c 24 08       	lea    0x8(%rsp),%rcx
    1dfa:	48 8d 54 24 0c       	lea    0xc(%rsp),%rdx
    1dff:	4c 8d 44 24 10       	lea    0x10(%rsp),%r8
    1e04:	48 8d 35 fa 15 00 00 	lea    0x15fa(%rip),%rsi        # 3405 <array.0+0x225>
    1e0b:	48 8d 3d 96 3e 00 00 	lea    0x3e96(%rip),%rdi        # 5ca8 <input_strings+0x168>
    1e12:	b8 00 00 00 00       	mov    $0x0,%eax
    1e17:	e8 c4 f4 ff ff       	call   12e0 <__isoc99_sscanf@plt>
    1e1c:	83 f8 03             	cmp    $0x3,%eax
    1e1f:	74 1a                	je     1e3b <phase_defused+0x6c>
    1e21:	48 8d 3d b8 14 00 00 	lea    0x14b8(%rip),%rdi        # 32e0 <array.0+0x100>
    1e28:	e8 e3 f3 ff ff       	call   1210 <puts@plt>
    1e2d:	48 8d 3d dc 14 00 00 	lea    0x14dc(%rip),%rdi        # 3310 <array.0+0x130>
    1e34:	e8 d7 f3 ff ff       	call   1210 <puts@plt>
    1e39:	eb b2                	jmp    1ded <phase_defused+0x1e>
    1e3b:	48 8d 7c 24 10       	lea    0x10(%rsp),%rdi
    1e40:	48 8d 35 c7 15 00 00 	lea    0x15c7(%rip),%rsi        # 340e <array.0+0x22e>
    1e47:	e8 c0 fb ff ff       	call   1a0c <strings_not_equal>
    1e4c:	85 c0                	test   %eax,%eax
    1e4e:	75 d1                	jne    1e21 <phase_defused+0x52>
    1e50:	48 8d 3d 29 14 00 00 	lea    0x1429(%rip),%rdi        # 3280 <array.0+0xa0>
    1e57:	e8 b4 f3 ff ff       	call   1210 <puts@plt>
    1e5c:	48 8d 3d 45 14 00 00 	lea    0x1445(%rip),%rdi        # 32a8 <array.0+0xc8>
    1e63:	e8 a8 f3 ff ff       	call   1210 <puts@plt>
    1e68:	b8 00 00 00 00       	mov    $0x0,%eax
    1e6d:	e8 8f fa ff ff       	call   1901 <secret_phase>
    1e72:	eb ad                	jmp    1e21 <phase_defused+0x52>

0000000000001e74 <sigalrm_handler>:
    1e74:	f3 0f 1e fa          	endbr64 
    1e78:	50                   	push   %rax
    1e79:	58                   	pop    %rax
    1e7a:	48 83 ec 08          	sub    $0x8,%rsp
    1e7e:	b9 00 00 00 00       	mov    $0x0,%ecx
    1e83:	48 8d 15 de 15 00 00 	lea    0x15de(%rip),%rdx        # 3468 <array.0+0x288>
    1e8a:	be 01 00 00 00       	mov    $0x1,%esi
    1e8f:	48 8b 3d 0a 3c 00 00 	mov    0x3c0a(%rip),%rdi        # 5aa0 <stderr@GLIBC_2.2.5>
    1e96:	b8 00 00 00 00       	mov    $0x0,%eax
    1e9b:	e8 90 f4 ff ff       	call   1330 <__fprintf_chk@plt>
    1ea0:	bf 01 00 00 00       	mov    $0x1,%edi
    1ea5:	e8 66 f4 ff ff       	call   1310 <exit@plt>

0000000000001eaa <rio_readlineb>:
    1eaa:	41 56                	push   %r14
    1eac:	41 55                	push   %r13
    1eae:	41 54                	push   %r12
    1eb0:	55                   	push   %rbp
    1eb1:	53                   	push   %rbx
    1eb2:	49 89 f4             	mov    %rsi,%r12
    1eb5:	48 83 fa 01          	cmp    $0x1,%rdx
    1eb9:	0f 86 92 00 00 00    	jbe    1f51 <rio_readlineb+0xa7>
    1ebf:	48 89 fb             	mov    %rdi,%rbx
    1ec2:	4c 8d 74 16 ff       	lea    -0x1(%rsi,%rdx,1),%r14
    1ec7:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    1ecd:	48 8d 6f 10          	lea    0x10(%rdi),%rbp
    1ed1:	eb 56                	jmp    1f29 <rio_readlineb+0x7f>
    1ed3:	e8 18 f3 ff ff       	call   11f0 <__errno_location@plt>
    1ed8:	83 38 04             	cmpl   $0x4,(%rax)
    1edb:	75 55                	jne    1f32 <rio_readlineb+0x88>
    1edd:	ba 00 20 00 00       	mov    $0x2000,%edx
    1ee2:	48 89 ee             	mov    %rbp,%rsi
    1ee5:	8b 3b                	mov    (%rbx),%edi
    1ee7:	e8 74 f3 ff ff       	call   1260 <read@plt>
    1eec:	89 c2                	mov    %eax,%edx
    1eee:	89 43 04             	mov    %eax,0x4(%rbx)
    1ef1:	85 c0                	test   %eax,%eax
    1ef3:	78 de                	js     1ed3 <rio_readlineb+0x29>
    1ef5:	85 c0                	test   %eax,%eax
    1ef7:	74 42                	je     1f3b <rio_readlineb+0x91>
    1ef9:	48 89 6b 08          	mov    %rbp,0x8(%rbx)
    1efd:	48 8b 43 08          	mov    0x8(%rbx),%rax
    1f01:	0f b6 08             	movzbl (%rax),%ecx
    1f04:	48 83 c0 01          	add    $0x1,%rax
    1f08:	48 89 43 08          	mov    %rax,0x8(%rbx)
    1f0c:	83 ea 01             	sub    $0x1,%edx
    1f0f:	89 53 04             	mov    %edx,0x4(%rbx)
    1f12:	49 83 c4 01          	add    $0x1,%r12
    1f16:	41 88 4c 24 ff       	mov    %cl,-0x1(%r12)
    1f1b:	80 f9 0a             	cmp    $0xa,%cl
    1f1e:	74 3c                	je     1f5c <rio_readlineb+0xb2>
    1f20:	41 83 c5 01          	add    $0x1,%r13d
    1f24:	4d 39 f4             	cmp    %r14,%r12
    1f27:	74 30                	je     1f59 <rio_readlineb+0xaf>
    1f29:	8b 53 04             	mov    0x4(%rbx),%edx
    1f2c:	85 d2                	test   %edx,%edx
    1f2e:	7e ad                	jle    1edd <rio_readlineb+0x33>
    1f30:	eb cb                	jmp    1efd <rio_readlineb+0x53>
    1f32:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    1f39:	eb 05                	jmp    1f40 <rio_readlineb+0x96>
    1f3b:	b8 00 00 00 00       	mov    $0x0,%eax
    1f40:	85 c0                	test   %eax,%eax
    1f42:	75 29                	jne    1f6d <rio_readlineb+0xc3>
    1f44:	b8 00 00 00 00       	mov    $0x0,%eax
    1f49:	41 83 fd 01          	cmp    $0x1,%r13d
    1f4d:	75 0d                	jne    1f5c <rio_readlineb+0xb2>
    1f4f:	eb 13                	jmp    1f64 <rio_readlineb+0xba>
    1f51:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    1f57:	eb 03                	jmp    1f5c <rio_readlineb+0xb2>
    1f59:	4d 89 f4             	mov    %r14,%r12
    1f5c:	41 c6 04 24 00       	movb   $0x0,(%r12)
    1f61:	49 63 c5             	movslq %r13d,%rax
    1f64:	5b                   	pop    %rbx
    1f65:	5d                   	pop    %rbp
    1f66:	41 5c                	pop    %r12
    1f68:	41 5d                	pop    %r13
    1f6a:	41 5e                	pop    %r14
    1f6c:	c3                   	ret    
    1f6d:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    1f74:	eb ee                	jmp    1f64 <rio_readlineb+0xba>

0000000000001f76 <submitr>:
    1f76:	f3 0f 1e fa          	endbr64 
    1f7a:	41 57                	push   %r15
    1f7c:	41 56                	push   %r14
    1f7e:	41 55                	push   %r13
    1f80:	41 54                	push   %r12
    1f82:	55                   	push   %rbp
    1f83:	53                   	push   %rbx
    1f84:	4c 8d 9c 24 00 60 ff 	lea    -0xa000(%rsp),%r11
    1f8b:	ff 
    1f8c:	48 81 ec 00 10 00 00 	sub    $0x1000,%rsp
    1f93:	48 83 0c 24 00       	orq    $0x0,(%rsp)
    1f98:	4c 39 dc             	cmp    %r11,%rsp
    1f9b:	75 ef                	jne    1f8c <submitr+0x16>
    1f9d:	48 83 ec 68          	sub    $0x68,%rsp
    1fa1:	49 89 fd             	mov    %rdi,%r13
    1fa4:	89 f5                	mov    %esi,%ebp
    1fa6:	48 89 14 24          	mov    %rdx,(%rsp)
    1faa:	48 89 4c 24 08       	mov    %rcx,0x8(%rsp)
    1faf:	4c 89 44 24 10       	mov    %r8,0x10(%rsp)
    1fb4:	4c 89 cb             	mov    %r9,%rbx
    1fb7:	4c 8b bc 24 a0 a0 00 	mov    0xa0a0(%rsp),%r15
    1fbe:	00 
    1fbf:	c7 84 24 3c 20 00 00 	movl   $0x0,0x203c(%rsp)
    1fc6:	00 00 00 00 
    1fca:	ba 00 00 00 00       	mov    $0x0,%edx
    1fcf:	be 01 00 00 00       	mov    $0x1,%esi
    1fd4:	bf 02 00 00 00       	mov    $0x2,%edi
    1fd9:	e8 92 f3 ff ff       	call   1370 <socket@plt>
    1fde:	85 c0                	test   %eax,%eax
    1fe0:	0f 88 20 01 00 00    	js     2106 <submitr+0x190>
    1fe6:	41 89 c4             	mov    %eax,%r12d
    1fe9:	4c 89 ef             	mov    %r13,%rdi
    1fec:	e8 af f2 ff ff       	call   12a0 <gethostbyname@plt>
    1ff1:	48 85 c0             	test   %rax,%rax
    1ff4:	0f 84 5c 01 00 00    	je     2156 <submitr+0x1e0>
    1ffa:	4c 8d ac 24 50 a0 00 	lea    0xa050(%rsp),%r13
    2001:	00 
    2002:	48 c7 84 24 50 a0 00 	movq   $0x0,0xa050(%rsp)
    2009:	00 00 00 00 00 
    200e:	48 c7 84 24 58 a0 00 	movq   $0x0,0xa058(%rsp)
    2015:	00 00 00 00 00 
    201a:	66 c7 84 24 50 a0 00 	movw   $0x2,0xa050(%rsp)
    2021:	00 02 00 
    2024:	48 63 50 14          	movslq 0x14(%rax),%rdx
    2028:	48 8b 40 18          	mov    0x18(%rax),%rax
    202c:	48 8d bc 24 54 a0 00 	lea    0xa054(%rsp),%rdi
    2033:	00 
    2034:	b9 0c 00 00 00       	mov    $0xc,%ecx
    2039:	48 8b 30             	mov    (%rax),%rsi
    203c:	e8 6f f2 ff ff       	call   12b0 <__memmove_chk@plt>
    2041:	66 c1 c5 08          	rol    $0x8,%bp
    2045:	66 89 ac 24 52 a0 00 	mov    %bp,0xa052(%rsp)
    204c:	00 
    204d:	ba 10 00 00 00       	mov    $0x10,%edx
    2052:	4c 89 ee             	mov    %r13,%rsi
    2055:	44 89 e7             	mov    %r12d,%edi
    2058:	e8 c3 f2 ff ff       	call   1320 <connect@plt>
    205d:	85 c0                	test   %eax,%eax
    205f:	0f 88 5c 01 00 00    	js     21c1 <submitr+0x24b>
    2065:	48 89 df             	mov    %rbx,%rdi
    2068:	e8 c3 f1 ff ff       	call   1230 <strlen@plt>
    206d:	48 89 c5             	mov    %rax,%rbp
    2070:	48 8b 3c 24          	mov    (%rsp),%rdi
    2074:	e8 b7 f1 ff ff       	call   1230 <strlen@plt>
    2079:	49 89 c6             	mov    %rax,%r14
    207c:	48 8b 7c 24 08       	mov    0x8(%rsp),%rdi
    2081:	e8 aa f1 ff ff       	call   1230 <strlen@plt>
    2086:	49 89 c5             	mov    %rax,%r13
    2089:	48 8b 7c 24 10       	mov    0x10(%rsp),%rdi
    208e:	e8 9d f1 ff ff       	call   1230 <strlen@plt>
    2093:	48 89 c2             	mov    %rax,%rdx
    2096:	4b 8d 84 2e 80 00 00 	lea    0x80(%r14,%r13,1),%rax
    209d:	00 
    209e:	48 01 d0             	add    %rdx,%rax
    20a1:	48 8d 54 6d 00       	lea    0x0(%rbp,%rbp,2),%rdx
    20a6:	48 01 d0             	add    %rdx,%rax
    20a9:	48 3d 00 20 00 00    	cmp    $0x2000,%rax
    20af:	0f 87 69 01 00 00    	ja     221e <submitr+0x2a8>
    20b5:	48 8d 94 24 40 40 00 	lea    0x4040(%rsp),%rdx
    20bc:	00 
    20bd:	b9 00 04 00 00       	mov    $0x400,%ecx
    20c2:	b8 00 00 00 00       	mov    $0x0,%eax
    20c7:	48 89 d7             	mov    %rdx,%rdi
    20ca:	f3 48 ab             	rep stos %rax,%es:(%rdi)
    20cd:	48 89 df             	mov    %rbx,%rdi
    20d0:	e8 5b f1 ff ff       	call   1230 <strlen@plt>
    20d5:	85 c0                	test   %eax,%eax
    20d7:	0f 84 e1 04 00 00    	je     25be <submitr+0x648>
    20dd:	8d 40 ff             	lea    -0x1(%rax),%eax
    20e0:	4c 8d 6c 03 01       	lea    0x1(%rbx,%rax,1),%r13
    20e5:	48 8d ac 24 40 40 00 	lea    0x4040(%rsp),%rbp
    20ec:	00 
    20ed:	48 8d 44 24 28       	lea    0x28(%rsp),%rax
    20f2:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    20f7:	49 be d9 ff 00 00 00 	movabs $0x2000000000ffd9,%r14
    20fe:	00 20 00 
    2101:	e9 a6 01 00 00       	jmp    22ac <submitr+0x336>
    2106:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    210d:	3a 20 43 
    2110:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2117:	20 75 6e 
    211a:	49 89 07             	mov    %rax,(%r15)
    211d:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2121:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2128:	74 6f 20 
    212b:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    2132:	65 20 73 
    2135:	49 89 47 10          	mov    %rax,0x10(%r15)
    2139:	49 89 57 18          	mov    %rdx,0x18(%r15)
    213d:	41 c7 47 20 6f 63 6b 	movl   $0x656b636f,0x20(%r15)
    2144:	65 
    2145:	66 41 c7 47 24 74 00 	movw   $0x74,0x24(%r15)
    214c:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2151:	e9 f7 02 00 00       	jmp    244d <submitr+0x4d7>
    2156:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    215d:	3a 20 44 
    2160:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    2167:	20 75 6e 
    216a:	49 89 07             	mov    %rax,(%r15)
    216d:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2171:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2178:	74 6f 20 
    217b:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    2182:	76 65 20 
    2185:	49 89 47 10          	mov    %rax,0x10(%r15)
    2189:	49 89 57 18          	mov    %rdx,0x18(%r15)
    218d:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    2194:	72 20 61 
    2197:	49 89 47 20          	mov    %rax,0x20(%r15)
    219b:	41 c7 47 28 64 64 72 	movl   $0x65726464,0x28(%r15)
    21a2:	65 
    21a3:	66 41 c7 47 2c 73 73 	movw   $0x7373,0x2c(%r15)
    21aa:	41 c6 47 2e 00       	movb   $0x0,0x2e(%r15)
    21af:	44 89 e7             	mov    %r12d,%edi
    21b2:	e8 99 f0 ff ff       	call   1250 <close@plt>
    21b7:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    21bc:	e9 8c 02 00 00       	jmp    244d <submitr+0x4d7>
    21c1:	48 b8 45 72 72 6f 72 	movabs $0x55203a726f727245,%rax
    21c8:	3a 20 55 
    21cb:	48 ba 6e 61 62 6c 65 	movabs $0x6f7420656c62616e,%rdx
    21d2:	20 74 6f 
    21d5:	49 89 07             	mov    %rax,(%r15)
    21d8:	49 89 57 08          	mov    %rdx,0x8(%r15)
    21dc:	48 b8 20 63 6f 6e 6e 	movabs $0x7463656e6e6f6320,%rax
    21e3:	65 63 74 
    21e6:	48 ba 20 74 6f 20 74 	movabs $0x20656874206f7420,%rdx
    21ed:	68 65 20 
    21f0:	49 89 47 10          	mov    %rax,0x10(%r15)
    21f4:	49 89 57 18          	mov    %rdx,0x18(%r15)
    21f8:	41 c7 47 20 73 65 72 	movl   $0x76726573,0x20(%r15)
    21ff:	76 
    2200:	66 41 c7 47 24 65 72 	movw   $0x7265,0x24(%r15)
    2207:	41 c6 47 26 00       	movb   $0x0,0x26(%r15)
    220c:	44 89 e7             	mov    %r12d,%edi
    220f:	e8 3c f0 ff ff       	call   1250 <close@plt>
    2214:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2219:	e9 2f 02 00 00       	jmp    244d <submitr+0x4d7>
    221e:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    2225:	3a 20 52 
    2228:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    222f:	20 73 74 
    2232:	49 89 07             	mov    %rax,(%r15)
    2235:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2239:	48 b8 72 69 6e 67 20 	movabs $0x6f6f7420676e6972,%rax
    2240:	74 6f 6f 
    2243:	48 ba 20 6c 61 72 67 	movabs $0x202e656772616c20,%rdx
    224a:	65 2e 20 
    224d:	49 89 47 10          	mov    %rax,0x10(%r15)
    2251:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2255:	48 b8 49 6e 63 72 65 	movabs $0x6573616572636e49,%rax
    225c:	61 73 65 
    225f:	48 ba 20 53 55 42 4d 	movabs $0x5254494d42555320,%rdx
    2266:	49 54 52 
    2269:	49 89 47 20          	mov    %rax,0x20(%r15)
    226d:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2271:	48 b8 5f 4d 41 58 42 	movabs $0x46554258414d5f,%rax
    2278:	55 46 00 
    227b:	49 89 47 30          	mov    %rax,0x30(%r15)
    227f:	44 89 e7             	mov    %r12d,%edi
    2282:	e8 c9 ef ff ff       	call   1250 <close@plt>
    2287:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    228c:	e9 bc 01 00 00       	jmp    244d <submitr+0x4d7>
    2291:	49 0f a3 c6          	bt     %rax,%r14
    2295:	73 21                	jae    22b8 <submitr+0x342>
    2297:	44 88 45 00          	mov    %r8b,0x0(%rbp)
    229b:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    229f:	48 83 c3 01          	add    $0x1,%rbx
    22a3:	4c 39 eb             	cmp    %r13,%rbx
    22a6:	0f 84 12 03 00 00    	je     25be <submitr+0x648>
    22ac:	44 0f b6 03          	movzbl (%rbx),%r8d
    22b0:	41 8d 40 d6          	lea    -0x2a(%r8),%eax
    22b4:	3c 35                	cmp    $0x35,%al
    22b6:	76 d9                	jbe    2291 <submitr+0x31b>
    22b8:	44 89 c0             	mov    %r8d,%eax
    22bb:	83 e0 df             	and    $0xffffffdf,%eax
    22be:	83 e8 41             	sub    $0x41,%eax
    22c1:	3c 19                	cmp    $0x19,%al
    22c3:	76 d2                	jbe    2297 <submitr+0x321>
    22c5:	41 80 f8 20          	cmp    $0x20,%r8b
    22c9:	74 54                	je     231f <submitr+0x3a9>
    22cb:	41 8d 40 e0          	lea    -0x20(%r8),%eax
    22cf:	3c 5f                	cmp    $0x5f,%al
    22d1:	76 0a                	jbe    22dd <submitr+0x367>
    22d3:	41 80 f8 09          	cmp    $0x9,%r8b
    22d7:	0f 85 54 02 00 00    	jne    2531 <submitr+0x5bb>
    22dd:	45 0f b6 c0          	movzbl %r8b,%r8d
    22e1:	48 8d 0d 6e 12 00 00 	lea    0x126e(%rip),%rcx        # 3556 <array.0+0x376>
    22e8:	ba 08 00 00 00       	mov    $0x8,%edx
    22ed:	be 01 00 00 00       	mov    $0x1,%esi
    22f2:	48 8b 7c 24 18       	mov    0x18(%rsp),%rdi
    22f7:	b8 00 00 00 00       	mov    $0x0,%eax
    22fc:	e8 5f f0 ff ff       	call   1360 <__sprintf_chk@plt>
    2301:	0f b6 44 24 28       	movzbl 0x28(%rsp),%eax
    2306:	88 45 00             	mov    %al,0x0(%rbp)
    2309:	0f b6 44 24 29       	movzbl 0x29(%rsp),%eax
    230e:	88 45 01             	mov    %al,0x1(%rbp)
    2311:	0f b6 44 24 2a       	movzbl 0x2a(%rsp),%eax
    2316:	88 45 02             	mov    %al,0x2(%rbp)
    2319:	48 8d 6d 03          	lea    0x3(%rbp),%rbp
    231d:	eb 80                	jmp    229f <submitr+0x329>
    231f:	c6 45 00 2b          	movb   $0x2b,0x0(%rbp)
    2323:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    2327:	e9 73 ff ff ff       	jmp    229f <submitr+0x329>
    232c:	48 01 c5             	add    %rax,%rbp
    232f:	48 29 c3             	sub    %rax,%rbx
    2332:	0f 84 e9 02 00 00    	je     2621 <submitr+0x6ab>
    2338:	48 89 da             	mov    %rbx,%rdx
    233b:	48 89 ee             	mov    %rbp,%rsi
    233e:	44 89 e7             	mov    %r12d,%edi
    2341:	e8 da ee ff ff       	call   1220 <write@plt>
    2346:	48 85 c0             	test   %rax,%rax
    2349:	7f e1                	jg     232c <submitr+0x3b6>
    234b:	e8 a0 ee ff ff       	call   11f0 <__errno_location@plt>
    2350:	83 38 04             	cmpl   $0x4,(%rax)
    2353:	0f 85 79 01 00 00    	jne    24d2 <submitr+0x55c>
    2359:	4c 89 e8             	mov    %r13,%rax
    235c:	eb ce                	jmp    232c <submitr+0x3b6>
    235e:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2365:	3a 20 43 
    2368:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    236f:	20 75 6e 
    2372:	49 89 07             	mov    %rax,(%r15)
    2375:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2379:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2380:	74 6f 20 
    2383:	48 ba 72 65 61 64 20 	movabs $0x7269662064616572,%rdx
    238a:	66 69 72 
    238d:	49 89 47 10          	mov    %rax,0x10(%r15)
    2391:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2395:	48 b8 73 74 20 68 65 	movabs $0x6564616568207473,%rax
    239c:	61 64 65 
    239f:	48 ba 72 20 66 72 6f 	movabs $0x73206d6f72662072,%rdx
    23a6:	6d 20 73 
    23a9:	49 89 47 20          	mov    %rax,0x20(%r15)
    23ad:	49 89 57 28          	mov    %rdx,0x28(%r15)
    23b1:	41 c7 47 30 65 72 76 	movl   $0x65767265,0x30(%r15)
    23b8:	65 
    23b9:	66 41 c7 47 34 72 00 	movw   $0x72,0x34(%r15)
    23c0:	44 89 e7             	mov    %r12d,%edi
    23c3:	e8 88 ee ff ff       	call   1250 <close@plt>
    23c8:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    23cd:	eb 7e                	jmp    244d <submitr+0x4d7>
    23cf:	4c 8d 4c 24 30       	lea    0x30(%rsp),%r9
    23d4:	48 8d 0d b5 10 00 00 	lea    0x10b5(%rip),%rcx        # 3490 <array.0+0x2b0>
    23db:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    23e2:	be 01 00 00 00       	mov    $0x1,%esi
    23e7:	4c 89 ff             	mov    %r15,%rdi
    23ea:	b8 00 00 00 00       	mov    $0x0,%eax
    23ef:	e8 6c ef ff ff       	call   1360 <__sprintf_chk@plt>
    23f4:	44 89 e7             	mov    %r12d,%edi
    23f7:	e8 54 ee ff ff       	call   1250 <close@plt>
    23fc:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2401:	eb 4a                	jmp    244d <submitr+0x4d7>
    2403:	48 8d b4 24 40 60 00 	lea    0x6040(%rsp),%rsi
    240a:	00 
    240b:	48 8d bc 24 40 80 00 	lea    0x8040(%rsp),%rdi
    2412:	00 
    2413:	ba 00 20 00 00       	mov    $0x2000,%edx
    2418:	e8 8d fa ff ff       	call   1eaa <rio_readlineb>
    241d:	48 85 c0             	test   %rax,%rax
    2420:	7e 3d                	jle    245f <submitr+0x4e9>
    2422:	48 8d b4 24 40 60 00 	lea    0x6040(%rsp),%rsi
    2429:	00 
    242a:	4c 89 ff             	mov    %r15,%rdi
    242d:	e8 ce ed ff ff       	call   1200 <strcpy@plt>
    2432:	44 89 e7             	mov    %r12d,%edi
    2435:	e8 16 ee ff ff       	call   1250 <close@plt>
    243a:	48 8d 35 30 11 00 00 	lea    0x1130(%rip),%rsi        # 3571 <array.0+0x391>
    2441:	4c 89 ff             	mov    %r15,%rdi
    2444:	e8 37 ee ff ff       	call   1280 <strcmp@plt>
    2449:	f7 d8                	neg    %eax
    244b:	19 c0                	sbb    %eax,%eax
    244d:	48 81 c4 68 a0 00 00 	add    $0xa068,%rsp
    2454:	5b                   	pop    %rbx
    2455:	5d                   	pop    %rbp
    2456:	41 5c                	pop    %r12
    2458:	41 5d                	pop    %r13
    245a:	41 5e                	pop    %r14
    245c:	41 5f                	pop    %r15
    245e:	c3                   	ret    
    245f:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2466:	3a 20 43 
    2469:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2470:	20 75 6e 
    2473:	49 89 07             	mov    %rax,(%r15)
    2476:	49 89 57 08          	mov    %rdx,0x8(%r15)
    247a:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2481:	74 6f 20 
    2484:	48 ba 72 65 61 64 20 	movabs $0x6174732064616572,%rdx
    248b:	73 74 61 
    248e:	49 89 47 10          	mov    %rax,0x10(%r15)
    2492:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2496:	48 b8 74 75 73 20 6d 	movabs $0x7373656d20737574,%rax
    249d:	65 73 73 
    24a0:	48 ba 61 67 65 20 66 	movabs $0x6d6f726620656761,%rdx
    24a7:	72 6f 6d 
    24aa:	49 89 47 20          	mov    %rax,0x20(%r15)
    24ae:	49 89 57 28          	mov    %rdx,0x28(%r15)
    24b2:	48 b8 20 73 65 72 76 	movabs $0x72657672657320,%rax
    24b9:	65 72 00 
    24bc:	49 89 47 30          	mov    %rax,0x30(%r15)
    24c0:	44 89 e7             	mov    %r12d,%edi
    24c3:	e8 88 ed ff ff       	call   1250 <close@plt>
    24c8:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    24cd:	e9 7b ff ff ff       	jmp    244d <submitr+0x4d7>
    24d2:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    24d9:	3a 20 43 
    24dc:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    24e3:	20 75 6e 
    24e6:	49 89 07             	mov    %rax,(%r15)
    24e9:	49 89 57 08          	mov    %rdx,0x8(%r15)
    24ed:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    24f4:	74 6f 20 
    24f7:	48 ba 77 72 69 74 65 	movabs $0x6f74206574697277,%rdx
    24fe:	20 74 6f 
    2501:	49 89 47 10          	mov    %rax,0x10(%r15)
    2505:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2509:	48 b8 20 74 68 65 20 	movabs $0x7265732065687420,%rax
    2510:	73 65 72 
    2513:	49 89 47 20          	mov    %rax,0x20(%r15)
    2517:	41 c7 47 28 76 65 72 	movl   $0x726576,0x28(%r15)
    251e:	00 
    251f:	44 89 e7             	mov    %r12d,%edi
    2522:	e8 29 ed ff ff       	call   1250 <close@plt>
    2527:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    252c:	e9 1c ff ff ff       	jmp    244d <submitr+0x4d7>
    2531:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    2538:	3a 20 52 
    253b:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2542:	20 73 74 
    2545:	49 89 07             	mov    %rax,(%r15)
    2548:	49 89 57 08          	mov    %rdx,0x8(%r15)
    254c:	48 b8 72 69 6e 67 20 	movabs $0x6e6f6320676e6972,%rax
    2553:	63 6f 6e 
    2556:	48 ba 74 61 69 6e 73 	movabs $0x6e6120736e696174,%rdx
    255d:	20 61 6e 
    2560:	49 89 47 10          	mov    %rax,0x10(%r15)
    2564:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2568:	48 b8 20 69 6c 6c 65 	movabs $0x6c6167656c6c6920,%rax
    256f:	67 61 6c 
    2572:	48 ba 20 6f 72 20 75 	movabs $0x72706e7520726f20,%rdx
    2579:	6e 70 72 
    257c:	49 89 47 20          	mov    %rax,0x20(%r15)
    2580:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2584:	48 b8 69 6e 74 61 62 	movabs $0x20656c6261746e69,%rax
    258b:	6c 65 20 
    258e:	48 ba 63 68 61 72 61 	movabs $0x6574636172616863,%rdx
    2595:	63 74 65 
    2598:	49 89 47 30          	mov    %rax,0x30(%r15)
    259c:	49 89 57 38          	mov    %rdx,0x38(%r15)
    25a0:	66 41 c7 47 40 72 2e 	movw   $0x2e72,0x40(%r15)
    25a7:	41 c6 47 42 00       	movb   $0x0,0x42(%r15)
    25ac:	44 89 e7             	mov    %r12d,%edi
    25af:	e8 9c ec ff ff       	call   1250 <close@plt>
    25b4:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    25b9:	e9 8f fe ff ff       	jmp    244d <submitr+0x4d7>
    25be:	48 8d 9c 24 40 60 00 	lea    0x6040(%rsp),%rbx
    25c5:	00 
    25c6:	48 8d 84 24 40 40 00 	lea    0x4040(%rsp),%rax
    25cd:	00 
    25ce:	50                   	push   %rax
    25cf:	ff 74 24 18          	push   0x18(%rsp)
    25d3:	4c 8b 4c 24 18       	mov    0x18(%rsp),%r9
    25d8:	4c 8b 44 24 10       	mov    0x10(%rsp),%r8
    25dd:	48 8d 0d dc 0e 00 00 	lea    0xedc(%rip),%rcx        # 34c0 <array.0+0x2e0>
    25e4:	ba 00 20 00 00       	mov    $0x2000,%edx
    25e9:	be 01 00 00 00       	mov    $0x1,%esi
    25ee:	48 89 df             	mov    %rbx,%rdi
    25f1:	b8 00 00 00 00       	mov    $0x0,%eax
    25f6:	e8 65 ed ff ff       	call   1360 <__sprintf_chk@plt>
    25fb:	48 89 df             	mov    %rbx,%rdi
    25fe:	e8 2d ec ff ff       	call   1230 <strlen@plt>
    2603:	48 89 c3             	mov    %rax,%rbx
    2606:	48 83 c4 10          	add    $0x10,%rsp
    260a:	48 8d ac 24 40 60 00 	lea    0x6040(%rsp),%rbp
    2611:	00 
    2612:	41 bd 00 00 00 00    	mov    $0x0,%r13d
    2618:	48 85 c0             	test   %rax,%rax
    261b:	0f 85 17 fd ff ff    	jne    2338 <submitr+0x3c2>
    2621:	44 89 a4 24 40 80 00 	mov    %r12d,0x8040(%rsp)
    2628:	00 
    2629:	c7 84 24 44 80 00 00 	movl   $0x0,0x8044(%rsp)
    2630:	00 00 00 00 
    2634:	48 8d bc 24 40 80 00 	lea    0x8040(%rsp),%rdi
    263b:	00 
    263c:	48 8d 84 24 50 80 00 	lea    0x8050(%rsp),%rax
    2643:	00 
    2644:	48 89 84 24 48 80 00 	mov    %rax,0x8048(%rsp)
    264b:	00 
    264c:	48 8d b4 24 40 60 00 	lea    0x6040(%rsp),%rsi
    2653:	00 
    2654:	ba 00 20 00 00       	mov    $0x2000,%edx
    2659:	e8 4c f8 ff ff       	call   1eaa <rio_readlineb>
    265e:	48 85 c0             	test   %rax,%rax
    2661:	0f 8e f7 fc ff ff    	jle    235e <submitr+0x3e8>
    2667:	48 8d 8c 24 3c 20 00 	lea    0x203c(%rsp),%rcx
    266e:	00 
    266f:	48 8d 94 24 40 20 00 	lea    0x2040(%rsp),%rdx
    2676:	00 
    2677:	48 8d bc 24 40 60 00 	lea    0x6040(%rsp),%rdi
    267e:	00 
    267f:	4c 8d 44 24 30       	lea    0x30(%rsp),%r8
    2684:	48 8d 35 d2 0e 00 00 	lea    0xed2(%rip),%rsi        # 355d <array.0+0x37d>
    268b:	b8 00 00 00 00       	mov    $0x0,%eax
    2690:	e8 4b ec ff ff       	call   12e0 <__isoc99_sscanf@plt>
    2695:	44 8b 84 24 3c 20 00 	mov    0x203c(%rsp),%r8d
    269c:	00 
    269d:	41 81 f8 c8 00 00 00 	cmp    $0xc8,%r8d
    26a4:	0f 85 25 fd ff ff    	jne    23cf <submitr+0x459>
    26aa:	48 8d 1d bd 0e 00 00 	lea    0xebd(%rip),%rbx        # 356e <array.0+0x38e>
    26b1:	48 8d bc 24 40 60 00 	lea    0x6040(%rsp),%rdi
    26b8:	00 
    26b9:	48 89 de             	mov    %rbx,%rsi
    26bc:	e8 bf eb ff ff       	call   1280 <strcmp@plt>
    26c1:	85 c0                	test   %eax,%eax
    26c3:	0f 84 3a fd ff ff    	je     2403 <submitr+0x48d>
    26c9:	48 8d b4 24 40 60 00 	lea    0x6040(%rsp),%rsi
    26d0:	00 
    26d1:	48 8d bc 24 40 80 00 	lea    0x8040(%rsp),%rdi
    26d8:	00 
    26d9:	ba 00 20 00 00       	mov    $0x2000,%edx
    26de:	e8 c7 f7 ff ff       	call   1eaa <rio_readlineb>
    26e3:	48 85 c0             	test   %rax,%rax
    26e6:	7f c9                	jg     26b1 <submitr+0x73b>
    26e8:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    26ef:	3a 20 43 
    26f2:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    26f9:	20 75 6e 
    26fc:	49 89 07             	mov    %rax,(%r15)
    26ff:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2703:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    270a:	74 6f 20 
    270d:	48 ba 72 65 61 64 20 	movabs $0x6165682064616572,%rdx
    2714:	68 65 61 
    2717:	49 89 47 10          	mov    %rax,0x10(%r15)
    271b:	49 89 57 18          	mov    %rdx,0x18(%r15)
    271f:	48 b8 64 65 72 73 20 	movabs $0x6f72662073726564,%rax
    2726:	66 72 6f 
    2729:	48 ba 6d 20 73 65 72 	movabs $0x726576726573206d,%rdx
    2730:	76 65 72 
    2733:	49 89 47 20          	mov    %rax,0x20(%r15)
    2737:	49 89 57 28          	mov    %rdx,0x28(%r15)
    273b:	41 c6 47 30 00       	movb   $0x0,0x30(%r15)
    2740:	44 89 e7             	mov    %r12d,%edi
    2743:	e8 08 eb ff ff       	call   1250 <close@plt>
    2748:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    274d:	e9 fb fc ff ff       	jmp    244d <submitr+0x4d7>

0000000000002752 <init_timeout>:
    2752:	f3 0f 1e fa          	endbr64 
    2756:	85 ff                	test   %edi,%edi
    2758:	75 01                	jne    275b <init_timeout+0x9>
    275a:	c3                   	ret    
    275b:	53                   	push   %rbx
    275c:	89 fb                	mov    %edi,%ebx
    275e:	48 8d 35 0f f7 ff ff 	lea    -0x8f1(%rip),%rsi        # 1e74 <sigalrm_handler>
    2765:	bf 0e 00 00 00       	mov    $0xe,%edi
    276a:	e8 21 eb ff ff       	call   1290 <signal@plt>
    276f:	85 db                	test   %ebx,%ebx
    2771:	b8 00 00 00 00       	mov    $0x0,%eax
    2776:	0f 49 c3             	cmovns %ebx,%eax
    2779:	89 c7                	mov    %eax,%edi
    277b:	e8 c0 ea ff ff       	call   1240 <alarm@plt>
    2780:	5b                   	pop    %rbx
    2781:	c3                   	ret    

0000000000002782 <init_driver>:
    2782:	f3 0f 1e fa          	endbr64 
    2786:	41 54                	push   %r12
    2788:	55                   	push   %rbp
    2789:	53                   	push   %rbx
    278a:	48 83 ec 10          	sub    $0x10,%rsp
    278e:	48 89 fd             	mov    %rdi,%rbp
    2791:	be 01 00 00 00       	mov    $0x1,%esi
    2796:	bf 0d 00 00 00       	mov    $0xd,%edi
    279b:	e8 f0 ea ff ff       	call   1290 <signal@plt>
    27a0:	be 01 00 00 00       	mov    $0x1,%esi
    27a5:	bf 1d 00 00 00       	mov    $0x1d,%edi
    27aa:	e8 e1 ea ff ff       	call   1290 <signal@plt>
    27af:	be 01 00 00 00       	mov    $0x1,%esi
    27b4:	bf 1d 00 00 00       	mov    $0x1d,%edi
    27b9:	e8 d2 ea ff ff       	call   1290 <signal@plt>
    27be:	ba 00 00 00 00       	mov    $0x0,%edx
    27c3:	be 01 00 00 00       	mov    $0x1,%esi
    27c8:	bf 02 00 00 00       	mov    $0x2,%edi
    27cd:	e8 9e eb ff ff       	call   1370 <socket@plt>
    27d2:	85 c0                	test   %eax,%eax
    27d4:	0f 88 88 00 00 00    	js     2862 <init_driver+0xe0>
    27da:	89 c3                	mov    %eax,%ebx
    27dc:	48 8d 3d 2d 0d 00 00 	lea    0xd2d(%rip),%rdi        # 3510 <array.0+0x330>
    27e3:	e8 b8 ea ff ff       	call   12a0 <gethostbyname@plt>
    27e8:	48 85 c0             	test   %rax,%rax
    27eb:	0f 84 bd 00 00 00    	je     28ae <init_driver+0x12c>
    27f1:	49 89 e4             	mov    %rsp,%r12
    27f4:	48 c7 04 24 00 00 00 	movq   $0x0,(%rsp)
    27fb:	00 
    27fc:	48 c7 44 24 08 00 00 	movq   $0x0,0x8(%rsp)
    2803:	00 00 
    2805:	66 c7 04 24 02 00    	movw   $0x2,(%rsp)
    280b:	48 63 50 14          	movslq 0x14(%rax),%rdx
    280f:	48 8b 40 18          	mov    0x18(%rax),%rax
    2813:	48 8d 7c 24 04       	lea    0x4(%rsp),%rdi
    2818:	b9 0c 00 00 00       	mov    $0xc,%ecx
    281d:	48 8b 30             	mov    (%rax),%rsi
    2820:	e8 8b ea ff ff       	call   12b0 <__memmove_chk@plt>
    2825:	66 c7 44 24 02 3b 6e 	movw   $0x6e3b,0x2(%rsp)
    282c:	ba 10 00 00 00       	mov    $0x10,%edx
    2831:	4c 89 e6             	mov    %r12,%rsi
    2834:	89 df                	mov    %ebx,%edi
    2836:	e8 e5 ea ff ff       	call   1320 <connect@plt>
    283b:	85 c0                	test   %eax,%eax
    283d:	0f 88 d3 00 00 00    	js     2916 <init_driver+0x194>
    2843:	89 df                	mov    %ebx,%edi
    2845:	e8 06 ea ff ff       	call   1250 <close@plt>
    284a:	66 c7 45 00 4f 4b    	movw   $0x4b4f,0x0(%rbp)
    2850:	c6 45 02 00          	movb   $0x0,0x2(%rbp)
    2854:	b8 00 00 00 00       	mov    $0x0,%eax
    2859:	48 83 c4 10          	add    $0x10,%rsp
    285d:	5b                   	pop    %rbx
    285e:	5d                   	pop    %rbp
    285f:	41 5c                	pop    %r12
    2861:	c3                   	ret    
    2862:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2869:	3a 20 43 
    286c:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2873:	20 75 6e 
    2876:	48 89 45 00          	mov    %rax,0x0(%rbp)
    287a:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    287e:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2885:	74 6f 20 
    2888:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    288f:	65 20 73 
    2892:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2896:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    289a:	c7 45 20 6f 63 6b 65 	movl   $0x656b636f,0x20(%rbp)
    28a1:	66 c7 45 24 74 00    	movw   $0x74,0x24(%rbp)
    28a7:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    28ac:	eb ab                	jmp    2859 <init_driver+0xd7>
    28ae:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    28b5:	3a 20 44 
    28b8:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    28bf:	20 75 6e 
    28c2:	48 89 45 00          	mov    %rax,0x0(%rbp)
    28c6:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    28ca:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    28d1:	74 6f 20 
    28d4:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    28db:	76 65 20 
    28de:	48 89 45 10          	mov    %rax,0x10(%rbp)
    28e2:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    28e6:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    28ed:	72 20 61 
    28f0:	48 89 45 20          	mov    %rax,0x20(%rbp)
    28f4:	c7 45 28 64 64 72 65 	movl   $0x65726464,0x28(%rbp)
    28fb:	66 c7 45 2c 73 73    	movw   $0x7373,0x2c(%rbp)
    2901:	c6 45 2e 00          	movb   $0x0,0x2e(%rbp)
    2905:	89 df                	mov    %ebx,%edi
    2907:	e8 44 e9 ff ff       	call   1250 <close@plt>
    290c:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2911:	e9 43 ff ff ff       	jmp    2859 <init_driver+0xd7>
    2916:	4c 8d 05 f3 0b 00 00 	lea    0xbf3(%rip),%r8        # 3510 <array.0+0x330>
    291d:	48 8d 0d 0c 0c 00 00 	lea    0xc0c(%rip),%rcx        # 3530 <array.0+0x350>
    2924:	48 c7 c2 ff ff ff ff 	mov    $0xffffffffffffffff,%rdx
    292b:	be 01 00 00 00       	mov    $0x1,%esi
    2930:	48 89 ef             	mov    %rbp,%rdi
    2933:	b8 00 00 00 00       	mov    $0x0,%eax
    2938:	e8 23 ea ff ff       	call   1360 <__sprintf_chk@plt>
    293d:	89 df                	mov    %ebx,%edi
    293f:	e8 0c e9 ff ff       	call   1250 <close@plt>
    2944:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2949:	e9 0b ff ff ff       	jmp    2859 <init_driver+0xd7>

000000000000294e <driver_post>:
    294e:	f3 0f 1e fa          	endbr64 
    2952:	53                   	push   %rbx
    2953:	48 89 cb             	mov    %rcx,%rbx
    2956:	85 d2                	test   %edx,%edx
    2958:	75 17                	jne    2971 <driver_post+0x23>
    295a:	48 85 ff             	test   %rdi,%rdi
    295d:	74 05                	je     2964 <driver_post+0x16>
    295f:	80 3f 00             	cmpb   $0x0,(%rdi)
    2962:	75 36                	jne    299a <driver_post+0x4c>
    2964:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    2969:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    296d:	89 d0                	mov    %edx,%eax
    296f:	5b                   	pop    %rbx
    2970:	c3                   	ret    
    2971:	48 89 f2             	mov    %rsi,%rdx
    2974:	48 8d 35 f9 0b 00 00 	lea    0xbf9(%rip),%rsi        # 3574 <array.0+0x394>
    297b:	bf 01 00 00 00       	mov    $0x1,%edi
    2980:	b8 00 00 00 00       	mov    $0x0,%eax
    2985:	e8 66 e9 ff ff       	call   12f0 <__printf_chk@plt>
    298a:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    298f:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    2993:	b8 00 00 00 00       	mov    $0x0,%eax
    2998:	eb d5                	jmp    296f <driver_post+0x21>
    299a:	48 83 ec 08          	sub    $0x8,%rsp
    299e:	51                   	push   %rcx
    299f:	49 89 f1             	mov    %rsi,%r9
    29a2:	4c 8d 05 e2 0b 00 00 	lea    0xbe2(%rip),%r8        # 358b <array.0+0x3ab>
    29a9:	48 89 f9             	mov    %rdi,%rcx
    29ac:	48 8d 15 ec 0b 00 00 	lea    0xbec(%rip),%rdx        # 359f <array.0+0x3bf>
    29b3:	be 6e 3b 00 00       	mov    $0x3b6e,%esi
    29b8:	48 8d 3d 51 0b 00 00 	lea    0xb51(%rip),%rdi        # 3510 <array.0+0x330>
    29bf:	e8 b2 f5 ff ff       	call   1f76 <submitr>
    29c4:	48 83 c4 10          	add    $0x10,%rsp
    29c8:	eb a5                	jmp    296f <driver_post+0x21>

Disassembly of section .fini:

00000000000029cc <_fini>:
    29cc:	f3 0f 1e fa          	endbr64 
    29d0:	48 83 ec 08          	sub    $0x8,%rsp
    29d4:	48 83 c4 08          	add    $0x8,%rsp
    29d8:	c3                   	ret    
