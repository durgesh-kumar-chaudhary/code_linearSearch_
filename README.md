def l_search(arr,target): # python code for linear search
    for i in range(len(arr)):
        if arr[i]==target:
            return i
    return -1
arr=[2,4,6,4,3]
target=4
print(l_search(arr,target))
