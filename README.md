<!--
 * @Author: Hao Yang
 * @Date: 2024-02-27 12:27:22
 * @LastEditTime: 2024-02-27 12:38:03
 * @LastEditors: momo.local
 * @Description: In User Settings Edit
 * @FilePath: /cpp_checker/README.md
-->
# To run this meomory leak checking and format checker in Linux:

# check if you have installed g++:
```
g++ --version
```
# if not, install g++:
```
sudo apt-get update
sudo apt-get install g++
```

# check if you have installed Valgrind:
```
valgrind --version
```

# if not, install Valgrind
```
sudo apt-get install valgrind
```

# check if you install clang-tidy:
```
clang-tidy --version
```

# check if you install clang-format:
```
clang-format --version
```

# install clang-tidy and clang-format:
```
sudo apt-get install clang-tidy
```
```
sudo apt-get install clang-format
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