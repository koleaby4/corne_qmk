# create new keyboard
qmk new-keymap -kb crkbd

# flush
qmk flash -kb crkbd -km koleaby4 -e CONVERT_TO=rp2040_ce

# compile
qmk compile -kb crkbd -km default -e CONVERT_TO=rp2040_ce
qmk compile -kb crkbd -km koleaby4 -e CONVERT_TO=elite_pi
