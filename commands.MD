./PuzzleSolver "../Scans/bliss" ../output --guided --estimated-piece-size 100 --verify-contours

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 25 --corners-blocksize 10 -r -a "../Scans/bliss" ../output

./PuzzleSolver --guided --verbose --estimated-size 100 --threshold 25 --corners-blocksize 25 -r -a "../Scans/bliss" ../output