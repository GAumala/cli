# cli

Convenient bash scripts using GNU coreutils plus other tools where specified.

To install just add any script to your path. My preferred way is with `ln`

### example:

```
sudo ln -s /home/gabriel/Projects/cli/fatzip /usr/bin/fatzip
```

## Available scripts:

### fatzip

Compresses a file and splits it into parts below the 4GB limit of FAT
filesystems, showing a progress bar until the task is done. Requires `bzip2` 
and `pv` to be installed.

### fatunzip

Decompresses the output of `fatzip`, showing a progress bar until the task is
done. Requires `bzip2` and `pv` to be installed.

### webjpg

Compresses an image, optimizing it for the web using `imagemagick`. 
