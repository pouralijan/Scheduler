cmake_minimum_required(VERSION 3.7)
project(BosmaScheduler)

set(CMAKE_CXX_STANDARD 11)

install(FILES Cron.h InterruptableSleep.h Scheduler.h DESTINATION include/cron/)
