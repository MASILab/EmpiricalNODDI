Gradient table information

1) bval - combined bval information from all sequences(b=1000,1500,2000,2500,3000) in a single session with 4 repeats
2) bvec - combined bvec information from all sequences(b=1000,1500,2000,2500,3000) in a single session with 4 repeats
3) indices - within each shell based on b-value, indices list that can give equal spacing subsampling
These are the index number (numbers from 1 to 97) of the volume that you want to extract to get a semi-uniform sampling. The indices start with 1, which is the b0 image. So if you wanted 24 DWI's you would extract indices(1:25).
