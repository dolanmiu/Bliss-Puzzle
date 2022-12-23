./PuzzleSolver "../Scans/bliss/cleaned" ../output --guided --estimated-piece-size 100 --verify-contours

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 25 --corners-blocksize 10 -r -a "../Scans/bliss/cleaned" ../output

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 25 --corners-blocksize 25 -r -a "../Scans/bliss/cleaned" ../output

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 15 --corners-blocksize 15 -r -a "../Scans/bliss/cleaned" ../output

Regular scans:

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 15 --corners-blocksize 15 -r -a "../Scans/bliss" ../output

High resolution

./PuzzleSolver --guided --verbose --estimated-size 80 --threshold 20 --corners-blocksize 20 -r -a "../Scans/bliss/high-resolution-black" ../output

./PuzzleSolver --guided --verbose --estimated-size 160 --threshold 20 --corners-blocksize 20 -r -a "../Scans/bliss/high-resolution-black/archive" ../output

./PuzzleSolver --guided --verbose --estimated-size 300 -r -a "../Scans/bliss/high-resolution-black/archive" ../output