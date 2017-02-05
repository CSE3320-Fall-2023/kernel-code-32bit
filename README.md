##Building the kernel
1. Change to your kernel source directory

```
cd linux-3.16.36/
```

2. Build your source. Note that the command uses a capital letter O not the letter 0
```
...make O=../build
```

3. Once the build is done, change to your build directory
```
cd ../build
```

4. Change to root using your password
```
su
```

5. Install the new kernel
```
make install
```
