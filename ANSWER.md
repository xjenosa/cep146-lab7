# Exercise 1:
1. Why did the conflict occur?
- editing the same lines in multiple branches
2. What lines in the file were changed in both branches?
- line 8-10
3. What would have prevented this conflict?
- delagating different sections to different people
4. In real life, how do you avoid conflicts when working on multiple devices?
- frequently pulling for person working on branch, or branch person frequently pushes, whichever finish editing first
5. What was the most challenging part of resolving the conflict?
- difference betwen <<< and >>>, current and incoming
6. How did Git help you identify where the conflict was?
- green and red colors

# Exercise 2:
1. How many times did you have to check the temperature before Git found the bug?
- 3 times
2. If you had 100 commits instead of 7, about how many checks would bisect need?
- 7 checks
3. How is bisect different from manually checking each commit with git checkout?
- linear search slow, bisect divides test by half each time
4. When would git bisect be most useful in real projects?
- only one bug is present, you can easily test it
5. What information do you need to start a bisect session?
- good and bad commits, good no bug present, bad bug is present

<img width="735" height="437" alt="1" src="https://github.com/user-attachments/assets/7edd59c5-a53a-4bee-a92c-0a741b0348d9" />
<img width="1920" height="1200" alt="2" src="https://github.com/user-attachments/assets/a5003d55-08d9-4bef-b1a8-15db41012df6" />
