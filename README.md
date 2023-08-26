# Polybags
T = int(input())
for _ in range(T):
    N = int(input())
    polybags = N // 10
    if N % 10 != 0:
        polybags += 1
    print(polybags)
