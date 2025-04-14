# Mini-task CLI usage

This is a bare minimum usage of CLI, according to mini task on **Day 1** (14/04/25)

# Without loop

```cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
type nul > latihan1.txt
type nul > latihan2.txt
type nul > latihan3.txt
type nul > latihan4.txt
type nul > latihan5.txt
dir
del "latihan4.txt"
mkdir "latihan4.txt"
del "latihan5.txt"
mkdir "latihan5.txt"
dir
rmdir "latihan4.txt"
```

# With loop
```cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
for /l %i in (1,1,5) do copy nul > latihan%i.txt
dir
del "latihan4.txt"
mkdir "latihan4.txt"
del "latihan5.txt"
mkdir "latihan5.txt"
dir
rmdir "latihan4.txt"
```