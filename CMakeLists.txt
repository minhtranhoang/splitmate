cmake_minimum_required(VERSION 3.20)
set(OKBAN "Hello1" "Hello2")
message("Hello")

foreach(VAR in lists OKBAN)
    message("VAR IS: ${VAR}")
endforeach()
