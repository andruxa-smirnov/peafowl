add_executable(rtp_extraction rtp_extraction.c)
target_link_libraries(rtp_extraction LINK_PUBLIC peafowl pcap)
