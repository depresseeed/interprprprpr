cmake_minimum_required(VERSION 3.2)

project(CRat)

set(surce_src executer.cpp ident.cpp interpretator.cpp lex.cpp main.cpp parser.cpp poliz.cpp scanner.cpp table_ident.cpp table_label.cpp table_str.cpp type_of_lex.cpp)
set(headers_hdr executer.h executor.h ident.h interpretator.h lex.h parser.h poliz.h scanner.h table_ident.h table_label.h table_str.h type_of_lex.h)

add_executable(${PROJECT_NAME} ${surce_src} ${headers_hdr})