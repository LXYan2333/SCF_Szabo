cmake_minimum_required(VERSION 3.10.0)
project(SCF_Szabo VERSION 0.1.0 LANGUAGES C)

add_executable(SCF_Szabo main.c calc_integrals.c format_integrals.c perform_scf.c)

target_link_libraries(SCF_Szabo PUBLIC m)