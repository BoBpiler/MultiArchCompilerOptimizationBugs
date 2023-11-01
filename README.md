| 컴파일러 | 아키텍처 | 버그 유형 | BVE 번호 | 링크 | 비고 |
| --- | --- | --- | --- | --- | --- |
| MSVC | x86-64 | 컴파일러 크래시 | 21, 22 | [BVE-21](https://developercommunity.visualstudio.com/t/Internal-Compiler-Error-with-for-loop-an/10486573), [BVE-22](https://developercommunity.visualstudio.com/t/fatal-error-C1001:-Internal-Compiler-Err/10485991?sort=newest) | Under Consideration |
|  |  | 부정확한 최적화 연산 | 5, 15 | [BVE-5](https://developercommunity.visualstudio.com/t/O2-and-Ox-Optimizations-Result-in-Incorr/10476654?sort=newest), [BVE-15](https://developercommunity.visualstudio.com/t/Comparison-of-incorrect-register-values/10480763?sort=newest) | Under Consideration |
|  |  | 다른 변수 주소 동일 인식 | 7 | [BVE-7](https://developercommunity.visualstudio.com/t/Bugs-that-recognize-the-same-address-val/10484681?sort=newest) | Under Consideration |
|  |  | 무한 루프 | 9 | [BVE-9](https://developercommunity.visualstudio.com/t/Optimization-Levels-O1-O2-Ox-Incorrect/10478781?sort=newest) | Under Consideration |
|  |  | 상수의 부정확한 계산 및 비교 | 12 | [BVE-12](https://developercommunity.visualstudio.com/t/Incorrectly-compiled-comparison-and-cons/10480723?sort=newest) | Under Consideration |
|  |  | 부호 확장 문제 | 13, 16, 19 | [BVE-13](https://developercommunity.visualstudio.com/t/Incorrect-unsigned-extension-when-upcast/10481317?sort=newest), [BVE-16](https://developercommunity.visualstudio.com/t/Impact-of-printf-on-CL-Compiler-Optimiza/10481033?sort=newest), [BVE-19](https://developercommunity.visualstudio.com/t/cl-Compiler-Misinterprets-Hexadecimal-Li/10483175) | Under Consideration |
|  |  | 지역 변수의 스택 초기화 누락 | 20 | [BVE-20](https://developercommunity.visualstudio.com/t/Function-pointer-address-comparison-erro/10485960?sort=newest) | Under Consideration |
| llvm | riscv | 부호 확장 문제 | 23 | [BVE-23](https://github.com/llvm/llvm-project/issues/68855) | Resolved |
|  | arm64 | 포인터 역참조 생략 | 24 | [BVE-24](https://github.com/llvm/llvm-project/issues/69294) | Open |
|  | mips64el | 부정확한 최적화 연산 | 25 | [BVE-25](https://github.com/llvm/llvm-project/issues/69328) | Open |
|  | mips64 | 부정확한 최적화 연산 | 27 | [BVE-27](https://github.com/llvm/llvm-project/issues/70495) | Open |
| gcc | s390x | 잘못된 코드 생성 | 28, 29 | [BVE-28](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112112), [BVE-29](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112274) | Open |



| 컴파일러 | 아키텍처 | 버그 유형 |
| --- | --- | --- |
| MSVC | x86-64 | [컴파일러 크래시](https://developercommunity.visualstudio.com/t/Internal-Compiler-Error-with-for-loop-an/10486573), [컴파일러 크래시](https://developercommunity.visualstudio.com/t/fatal-error-C1001:-Internal-Compiler-Err/10485991?sort=newest), [부정확한 최적화 연산](https://developercommunity.visualstudio.com/t/O2-and-Ox-Optimizations-Result-in-Incorr/10476654?sort=newest), [부정확한 최적화 연산](https://developercommunity.visualstudio.com/t/Comparison-of-incorrect-register-values/10480763?sort=newest), [다른 변수 주소 동일 인식](https://developercommunity.visualstudio.com/t/Bugs-that-recognize-the-same-address-val/10484681?sort=newest), [무한 루프](https://developercommunity.visualstudio.com/t/Optimization-Levels-O1-O2-Ox-Incorrect/10478781?sort=newest), [상수의 부정확한 계산 및 비교](https://developercommunity.visualstudio.com/t/Incorrectly-compiled-comparison-and-cons/10480723?sort=newest), [부호 확장 문제](https://developercommunity.visualstudio.com/t/Incorrect-unsigned-extension-when-upcast/10481317?sort=newest), [부호 확장 문제](https://developercommunity.visualstudio.com/t/Impact-of-printf-on-CL-Compiler-Optimiza/10481033?sort=newest), [부호 확장 문제](https://developercommunity.visualstudio.com/t/cl-Compiler-Misinterprets-Hexadecimal-Li/10483175), [지역 변수의 스택 초기화 누락](https://developercommunity.visualstudio.com/t/Function-pointer-address-comparison-erro/10485960?sort=newest) |
| llvm | riscv | [부호 확장 문제](https://github.com/llvm/llvm-project/issues/68855) |
|  | arm64 | [포인터 역참조 생략](https://github.com/llvm/llvm-project/issues/69294) |
|  | mips64el | [부정확한 최적화 연산](https://github.com/llvm/llvm-project/issues/69328) |
|  | mips64 | [부정확한 최적화 연산](https://github.com/llvm/llvm-project/issues/70495) |
| gcc | s390x | [잘못된 코드 생성](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112112), [잘못된 코드 생성](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112274) |


| 컴파일러 | 아키텍처 | 버그 유형 | 링크 |
| --- | --- | --- | --- |
| MSVC | x86-64 | 컴파일러 크래시 | [Link](https://developercommunity.visualstudio.com/t/Internal-Compiler-Error-with-for-loop-an/10486573) |
| MSVC | x86-64 | 컴파일러 크래시 | [Link](https://developercommunity.visualstudio.com/t/fatal-error-C1001:-Internal-Compiler-Err/10485991?sort=newest) |
| MSVC | x86-64 | 부정확한 최적화 연산 | [Link](https://developercommunity.visualstudio.com/t/O2-and-Ox-Optimizations-Result-in-Incorr/10476654?sort=newest) |
| MSVC | x86-64 | 부정확한 최적화 연산 | [Link](https://developercommunity.visualstudio.com/t/Comparison-of-incorrect-register-values/10480763?sort=newest) |
| MSVC | x86-64 | 다른 변수 주소 동일 인식 | [Link](https://developercommunity.visualstudio.com/t/Bugs-that-recognize-the-same-address-val/10484681?sort=newest) |
| MSVC | x86-64 | 무한 루프 | [Link](https://developercommunity.visualstudio.com/t/Optimization-Levels-O1-O2-Ox-Incorrect/10478781?sort=newest) |
| MSVC | x86-64 | 상수의 부정확한 계산 및 비교 | [Link](https://developercommunity.visualstudio.com/t/Incorrectly-compiled-comparison-and-cons/10480723?sort=newest) |
| MSVC | x86-64 | 부호 확장 문제 | [Link](https://developercommunity.visualstudio.com/t/Incorrect-unsigned-extension-when-upcast/10481317?sort=newest) |
| MSVC | x86-64 | 부호 확장 문제 | [Link](https://developercommunity.visualstudio.com/t/Impact-of-printf-on-CL-Compiler-Optimiza/10481033?sort=newest) |
| MSVC | x86-64 | 부호 확장 문제 | [Link](https://developercommunity.visualstudio.com/t/cl-Compiler-Misinterprets-Hexadecimal-Li/10483175) |
| MSVC | x86-64 | 지역 변수의 스택 초기화 누락 | [Link](https://developercommunity.visualstudio.com/t/Function-pointer-address-comparison-erro/10485960?sort=newest) |
| llvm | riscv | 부호 확장 문제 | [Link](https://github.com/llvm/llvm-project/issues/68855) |
| llvm | arm64 | 포인터 역참조 생략 | [Link](https://github.com/llvm/llvm-project/issues/69294) |
| llvm | mips64el | 부정확한 최적화 연산 | [Link](https://github.com/llvm/llvm-project/issues/69328) |
| llvm | mips64 | 부정확한 최적화 연산 | [Link](https://github.com/llvm/llvm-project/issues/70495) |
| gcc | s390x | 잘못된 코드 생성 | [Link](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112112) |
| gcc | s390x | 잘못된 코드 생성 | [Link](https://gcc.gnu.org/bugzilla/show_bug.cgi?id=112274) |
