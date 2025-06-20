# Implemention of Trie

# Implement the Trie class:
• Trie() Initializes the trie object.
• void insert(String word) Inserts the string word into the trie.
• boolean search(String word) Returns true if the string word is in the trie (i.e., was
inserted before), and false otherwise.
• boolean startsWith(String prefix) Returns true if there is a previously inserted
string word that has the prefix prefix, and false otherwise.

# Example 1:

Input
["Trie", "insert", "search", "search", "startsWith", "insert", "search"]
[[], ["apple"], ["apple"], ["app"], ["app"], ["app"], ["app"]]

Output
[null, null, true, false, true, null, true]


