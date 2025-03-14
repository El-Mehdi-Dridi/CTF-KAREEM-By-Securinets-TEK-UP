The encrypted flag bytes are stored in little-endian format in the decompiled code

```C++
*(_QWORD *)flag = 0xECE7E0FBFCEAECDALL;          // Bytes: DA EC EA FC FB E0 E7 EC
*(_QWORD *)&flag[8] = 0xBEB1BBB0ECF2FAFDLL;      // Bytes: FD FA F2 EC B0 BB B1 BE
*(_QWORD *)&flag[16] = 0xB1BBB8BDEABAEDBELL;     // Bytes: BE ED BA EA BD B8 BB B1
*(_QWORD *)&flag[24] = 0xEBBFBCBAB8EDEAEALL;     // Bytes: EA EA ED B8 BA BC BF EB
*(_QWORD *)&flag[32] = 0xEFBCEDB8B9E8BABELL;     // Bytes: BE BA E8 B9 B8 ED BC EF
*(_QWORD *)&flag[40] = 0xEFBABBBDBDBDBBBCLL;     // Bytes: BC BB BD BD BD BB BA EF
*(_QWORD *)&flag[48] = 0xB1BEBBEBBEBCBBEFLL;     // Bytes: EF BB BC BE EB BB BE B1
*(_DWORD *)&flag[56] = -1162298690;              // Bytes (hex) BA BE BE BA
*(_QWORD *)&flag[60] = 0xEABBEFBFEDB9BABCLL;     // Bytes: BC BA B9 ED BF EF BB EA
*(_QWORD *)&flag[68] = 0xF4ECEDB8B1EFB8BFLL;     // Bytes: BF B8 EF B1 B8 ED EC F4
```

Also the encrypted Flag is xored by `0x89` 

```C++
 for ( i = 0; i < (int)strlen(input); ++i )
    enc[i] = input[i] ^ 0x89;
```
Check solver.py to see the solver script 
