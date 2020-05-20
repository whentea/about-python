# Bubble  

```
def bubble_sort(alist):
    for i in range(len(alist) - 1, 0, -1):
        print(" ")
        print("i = {}".format(i))
        print("---------------------------------")
        for j in range(0, i):
            print("j = {}".format(j))
            if alist[j + 1] < alist[j]:
                alist[j], alist[j + 1] = alist[j + 1], alist[j]
                print("Swap")
                print("alist[",j,"], alist[",j+1,"] = alist[",j+1,"],alist[",j,"]")
                print(alist)
                print("------------")                
            else:
                print("No Swap")
                print("------------")
        
alist = "12 3 7".split()
alist = [int(x) for x in alist]
bubble_sort(alist)
# Melihat Hasil Akhir Sorting ------------------------
print(alist)

```
