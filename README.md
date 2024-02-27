<!--
 * @Author: Hao Yang
 * @Date: 2024-02-27 12:27:22
 * @LastEditTime: 2024-02-27 13:06:58
 * @LastEditors: momo.local
 * @Description: In User Settings Edit
 * @FilePath: /cpp_checker/README.md
-->
# To run this meomory leak checking and format checker in Linux:

# check and installed g++:
```
g++ --version
sudo apt-get update
sudo apt-get install g++
```

# check and installed Valgrind:
```
valgrind --version
sudo apt-get install valgrind
```


# check and install clang:
```
clang++ --version
sudo apt install clang
```


# check and install clang-tidy:
```
clang-tidy --version
sudo apt-get install clang-tidy
```

# check and install clang-format:
```
clang-format --version
sudo apt-get install clang-format
```

# check and install llvm:
```
sudo apt install clang
```

# pull all .clang-format .clang-tidy, check-code-coverage.sh, creat-output.sh and runit.sh to your folder:

# change the mod for *.sh file to executable 
```
chmod +x *.sh
```

# run
```
./create-output.sh > output.txt 2>&1
```

# examine the output.txt file for any issues that need fixing