# Can-Rohan-Steal-All-the-Jewelry-
In a quiet village, a young man named Rohan dreamed of becoming rich overnight. He and his N friends (including himself) came up with a daring plan to rob a house full of precious jewelry under the cover of darkness. The house contained a total of X kg of jewelry, and each of Rohan's friends, including him, could carry up to Y kg of jewelry.
Now, Rohan is wondering if their combined strength will be enough to steal all the jewelry in one go. Can you help Rohan figure out whether he and his friends can successfully carry all the jewelry out of the house?

def can_rohan_steal_all_jewelry(N, X, Y):

    total_capacity = N * Y  
    if total_capacity >= X:
        print("Yes")
    else:
        print("No")

N, X, Y = map(int, input().split())

can_rohan_steal_all_jewelry(N, X, Y)
