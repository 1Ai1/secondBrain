![[Pasted image 20240327121414.png]]

```java
sum -= left;
sum += right

 for (int i = 0; i < n - k + 1; i++) {
            int current_sum = 0;
            for (int j = 0; j < k; j++)
                current_sum = current_sum + arr[i + j];
                
            max_sum = Math.max(current_sum, max_sum);
        }
```



[[Algorithms]]
