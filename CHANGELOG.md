# Changelog

All notable changes to this project will be documented in this file.

## [1.1.3](https://github.com/B3DScanner/cpu-x86/compare/v1.1.2...v1.1.3) (2025-05-21)


### Bug Fixes

* **src/x86:** Changed __cpuid to cpux86::cpuid from cpu_x86_Linux and cpu_x86_Windows in cpu_x86.cpp ([8aa5a52](https://github.com/B3DScanner/cpu-x86/commit/8aa5a52876ec1fe228fdd1e14727f3cfd933ec25))

## [1.1.2](https://github.com/B3DScanner/cpu-x86/compare/v1.1.1...v1.1.2) (2025-05-21)


### Bug Fixes

* **src\x86:** Added missing function __cpuid for Clang and gcc compilers ([0658305](https://github.com/B3DScanner/cpu-x86/commit/0658305c2273cb657e262d37bdeec00a37450c82))

## [1.1.1](https://github.com/B3DScanner/cpu-x86/compare/v1.1.0...v1.1.1) (2025-04-23)


### Bug Fixes

* Added the missing hasAVX2() function to the cpu_x86.h file. ([5e37980](https://github.com/B3DScanner/cpu-x86/commit/5e379803773fbc7200b973f5837aa8d92dc98bfc))

# [1.1.0](https://github.com/B3DScanner/cpu-x86/compare/v1.0.0...v1.1.0) (2025-04-23)


### Features

* Added function to detect AVX and get brand cpu name ([b419d67](https://github.com/B3DScanner/cpu-x86/commit/b419d6793cc7172251515384fb73cc1bea48673f))

# 1.0.0 (2025-03-30)


### Features

* Added an automated release system and an automated versioning system using Git tags ([444187f](https://github.com/B3DScanner/cpu-x86/commit/444187f145174d47e3526311fbed857f333d1597))
