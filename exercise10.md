# Exercise 10 - Understanding Commits

1. Look at your commit log

        git log --oneline

2. Choose a commit hash

3. See what type of object that hash names

        git cat-file -t <hash>

4. Examine the contents of that commit closely

        git cat-file -p <hash>

5. Find the parent's hash in the commit log

6. Look at the contents of the tree

        git cat-file -p <hash>

PS C:\Users\mkhan\Desktop\cisw 17\msac-lab6> git cat-file -p e79b7f1fe3a4c668db7d027424cdd707e3996690
100644 blob 00ee51cbab22ca55af8a2359bf7fceb2957e1dec    README.md
100644 blob b7cc97ea4eb0a783b7abc1ceb9360a67b2868b15    exercise01.md
100644 blob 7085bedba0007f7a73325c4d44d9a6a99771fffa    exercise02.md
100644 blob 71f15a38e3ebea233bd574760585bf2c39d9b3e2    exercise03.md
100644 blob 8d139ca20ba2ba480daf72d5cc03aef8df7ef07f    exercise04.md
100644 blob 70530694c772a0fc53fbd9a40a393cc52c31a10a    exercise05.md
100644 blob 8d306f5dc20f925af1c08793b289a28d0fe198e3    exercise06.md
100644 blob d2c663ef64cc575b55a55fd4edc5236bfca3ac07    exercise07.md
100644 blob c624a89cdf3af9ca1cf4e712ecb28b8ca1f2f1a5    exercise08.md
100644 blob 1bfceffc1508140d6a92a242cb05aa94fe5871dc    exercise09.md
100644 blob 9d035070f05cc4efe3cddb63e49a8647b7f70b80    exercise10.md
100644 blob eb9c7c9561db6fe1b6e77dbed49940734afb0246    fruits.txt
040000 tree 3e16b4a1ccbaba45e0b3327f5c3e518c5947be33    mainDirectory
100644 blob b7bf9ccb965fd5b19aa450cb08797c040b41a269    vegetables.txt

7. Examine the contents of one of the blobs

8. What type of object does the parent hash represent?

        git cat-file -t <hash>

9. Examine the contents of the parent and its tree

10. Do the trees you looked at have any matching hashes listed?
YEs they have matching hashes listed.