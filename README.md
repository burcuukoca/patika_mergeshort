# [16,21,11,8,12,22] Merge Sort dizinin sort türüne göre aşamalarını yazınız

STEP 1 [16,21.11] [8,12,22]
STEP 2 [16] [21,11] [8,12] [22]
STEP 3 [16] [21] [11] [8] [12] [22]
STEP 4 [16] [11,21] [8,12] [22]
STEP 5  [11,16,21] [8,12,22]
STEP 6 [8,11,12,16,21,22]

# BigO: O(nlogn)

# Time Complexity: T(n) = 2T(n/2) + θ(n)
