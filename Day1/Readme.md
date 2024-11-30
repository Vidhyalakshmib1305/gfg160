Used a map to count the frequency of characters
add the count of each character in s1
subtract it if the same character is in s2
This will end up in the freq map with 0's if the given two strings are anagrams

TC : O(3N) = O(N)
SC : O(26) / O(N) (since using a map of size of the given strings)
