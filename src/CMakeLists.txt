cmake_minimum_required(VERSION 2.8)

project(GatewayServer)

#link_libraries(profiler)

gen_server("Base" "GatewayServer")

target_link_libraries(GatewayServer mysqlclient dl)
