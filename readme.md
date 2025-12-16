# CI dependencies for the qat compiler

- The `qat` compiler requires a version of LLVM built as static libraries, with clang, lld and compiler-rt components as well. Not all packages provided by native platforms fulfill this requirement. So this is where we build files to be used by the CI system
