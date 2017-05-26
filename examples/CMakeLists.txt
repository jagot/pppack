add_executable(iiex iiex.f)
target_link_libraries(iiex pppack)

add_executable(ivex ivex.f)
target_link_libraries(ivex pppack)

add_executable(ixex ixex.f)
target_link_libraries(ixex pppack)

add_executable(l2ex2 l2main.f l2appr.f l2err.f l2knts.f setdatex2.f)
target_link_libraries(l2ex2 pppack)

add_executable(l2ex3 l2main.f l2appr.f l2err.f l2knts.f setdatex3.f newnotfake.f)
target_link_libraries(l2ex3 pppack)

add_executable(l2ex4 l2main.f l2appr.f l2err.f l2knts.f setdatex4.f titand.f)
target_link_libraries(l2ex4 pppack)

add_executable(xex1 xex1.f)
target_link_libraries(xex1 pppack)

add_executable(xex2 xex2.f)
target_link_libraries(xex2 pppack)

add_executable(xex3 xex3.f)
target_link_libraries(xex3 pppack)

add_executable(xex4 xex4.f)
target_link_libraries(xex4 pppack)

add_executable(xiiex2 xiiex2.f)
target_link_libraries(xiiex2 pppack)

add_executable(xiiex3 xiiex3.f)
target_link_libraries(xiiex3 pppack)

add_executable(xiiex4 xiiex4.f)
target_link_libraries(xiiex4 pppack)

add_executable(xiiiex1 xiiiex1.f round.f)
target_link_libraries(xiiiex1 pppack)

add_executable(xiiiex2 xiiiex2.f)
target_link_libraries(xiiiex2 pppack)

add_executable(xiiiex2m xiiiex2m.f)
target_link_libraries(xiiiex2m pppack)

add_executable(xiiiex3 xiiiex3.f titand.f)
target_link_libraries(xiiiex3 pppack)

add_executable(xivex1 xivex1.f)
target_link_libraries(xivex1 pppack)

add_executable(xvex xvex.f)
target_link_libraries(xvex pppack)

add_executable(xviex2 xviex2.f titand.f)
target_link_libraries(xviex2 pppack)

add_executable(xviex3 xviex3.f)
target_link_libraries(xviex3 pppack)

add_executable(xviiex2 xviiex2.f)
target_link_libraries(xviiex2 pppack)

add_executable(xviiex3 xviiex3.f)
target_link_libraries(xviiex3 pppack)

