# Bicheng Feng V00834906
Describe the input_file.txt for seng265 Assign01
input_file.txt:
Joshua Boyle spoke to reporters after landing in Canada with his wife Caitlan Coleman and children following almost five years in captivity.
Both sets of parents have previously questioned why the couple were in Afghanistan in the first place.

output_file:
(part A)
COUNT[02]=06
COUNT[03]=05
COUNT[04]=07
COUNT[05]=06
COUNT[06]=04
COUNT[07]=04
COUNT[08]=01
COUNT[09]=03
COUNT[10]=02
COUNT[11]=01
(part B)
COUNT[04]=07
COUNT[02]=06
COUNT[05]=06
COUNT[03]=05
COUNT[06]=04
COUNT[07]=04
COUNT[09]=03
COUNT[10]=02
COUNT[08]=01
COUNT[11]=01

1st thing to check: I make a word "Afghanistan", which length is 11, so the output should be COUNT[11]=01(which isn't COUNT[011]=01)
2nd thing to check: Is it followed two rules? So there are some words with different length, but with the same frequency.
3rd thing to check: Is the code doing well on changing line(\n).
