mport java.util.*;
public class Search{
	public static int BSearch(int a[],int n, int key){
		int low=0;
		int high=n-1;
		while(low<=high){
			int mid = (low+high)/2;
			if(a[mid] == key)
				return mid;
			else if(a[mid]>key)
				low = mid + 1;
			else
				high = mid - 1;
		}
		return -1;
	}

	public static void main(String[] args){
		Scanner sc = new Scanner(System.in);
		System.out.println("enter the number of elements in array:");
		int n = sc.nextInt();
		int arr[] = new int[n];
		System.out.println("enter the elements: ");
		int i;
		for(i=0;i<n;i++){
			arr[i] = sc.nextInt();
		}
		System.out.println("enter the key:");
		int key =  sc.nextInt();
		int pos = BSearch(arr,n,key);
		if(pos==-1)
			System.out.println("key is not found");
		else
			System.out.println("key is found at index:"+pos);
	}
}
