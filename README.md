# create new keyboard
qmk new-keymap -kb crkbd

# flush
qmk flash -kb crkbd -km koleaby4 -e CONVERT_TO=promicro_rp2040

# compile
qmk compile -kb crkbd -km koleaby4 -e CONVERT_TO=promicro_rp2040

qmk compile -kb crkbd -km koleaby4 -e CONVERT_TO=elite_pi
