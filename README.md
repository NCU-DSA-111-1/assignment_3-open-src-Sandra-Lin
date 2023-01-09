# Arithemtic Coding vs. Huffman Coding

## compile
Arcd: gcc -o arcd arcd_stream.c arcd.c arcd.h adaptive_model.h adapt_model.c<br />
Huffman: make
## run
Arcd: <br />
./arcd -e <input_file_name | tee encoding_file_name <br />
./arcd -d <input_file_name | tee decoding_file_name <br />
huffman: <br />
./huffcode -i input_file_name -o encoding_file_name -c <br />
./huffcode -i input_file_name -o decoding_file_name -d <br />

## uasge
The original content of file: <br />
Observation of the family from the monster.
Monster want to be accepted.
Safie’s father and the family.
Safie’s appearance.
The monster learning and trying to talk to the family.<br /><br />

Arcd encoding:<br />
OK x+0      1    u  ˆ#    1C R    MjώGa  -D*    Đ    \/ d 5c  ^   R; Hv m  +j{ZK  i  1 i z C  =S     }( 'd =! F j3 <br />
the coding time is 0.000219 sec.<br />
Arcd decoding:<br />
Observation of the family from the monster
Monster want to be accepted
Safie’s father and the family
Safie’s appearance
The monster learning and trying to talk to the family<br />
the coding time is 0.000263 sec.<br />

Huffman encoding:<br />
the coding time is 0.000271 sec.<br />
Huffman decoding:<br />
the coding time is 0.000087 sec.<br />

## Reference
https://github.com/drichardson/huffman<br />
https://github.com/wonder-mice/arcd