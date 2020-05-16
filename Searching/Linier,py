def binarySearch (arr, l, r, x):
    if r >= l:
        mid = l + (r - l)
        if arr[mid] == x:
            return mid
        elif arr[mid] > x:
            return binarySearch(arr, l, mid-1, x) 
        else:
            return binarySearch(arr, mid + 1, r, x)
    else:
        return -1

print('data array')
print('[ 2, 3, 4, 10, 40 ]')
arr = [ 2, 3, 4, 10, 40 ] 
x = input('data yang dicari:')

result = binarySearch(arr, 0, len(arr)-1, int(x)) 

if result != -1: 
	print(x+" ada di array ke "+str(result)) 
else: 
	print('data yang dicari tidak ditemukan') 
