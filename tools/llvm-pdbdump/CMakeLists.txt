set(LLVM_LINK_COMPONENTS
  Support
  DebugInfoPDB
  )

add_llvm_tool(llvm-pdbdump
  llvm-pdbdump.cpp
  BuiltinDumper.cpp
  ClassDefinitionDumper.cpp
  CompilandDumper.cpp
  EnumDumper.cpp
  FunctionDumper.cpp
  LinePrinter.cpp
  TypeDumper.cpp
  TypedefDumper.cpp
  VariableDumper.cpp
  )
