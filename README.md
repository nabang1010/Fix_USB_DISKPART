# Fix USB Using DISKPART

**@nabang1010**

* Open DISKPART

```console
diskpart
```

* List all disk

```console
list disk
```

* Select USB disk

```console
select disk ?
```

```console
clean
```

```console
create partition primary
```

```console
format fs=fat32 quick
```

```console
assign
```

```console
exit
```
