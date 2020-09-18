# History
- `apt` is package manager for `ubuntu` and `debian` and related linux versions
- 2016, ubuntu decided to merge `apt-get` and `apt-cache` into single tool `apt`
    - example 1
        ```
        apt-cache search graphical ftp
        apt search graphical ftp
        ``` 
    - example 2
        ```
        apt-get install filezilla
        apt install filezilla
        ```
    - example 3
        ```
        apt-get purge filezilla
        apt purge filezilla
        ```

- 
# Advance Package Tool (apt-get)
- Upgrade apt-get tool
```
apt-get update
```
- Install new package
```
apt-get install php5
```
- Remove package
```
apt-get purge ph5
```
- Clean up
```
apt-get autoremove
```
- Show package details
```
apt-get show firefox
```
- Search package
```
apt-get search firefox
```
- To know version of installed package
```
apt-cache policy firefox
```
- Install specific version
```
apt-get install <package name>=<version>
apt-get install gparted=0.16.1-1
```


