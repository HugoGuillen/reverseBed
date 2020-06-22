# reverseBed
Change relative strand orientation of a BED or GTF file. 
The only prerequisite is bedtools in the PATH.
*Note: Current implementation works with tracks on a single chromosome and uncompressed files.*

```bash
usage:
  reverseBed.sh [options]
    -i <bed/gtf> Input file.
    -c <center> Center to reverse the bed. Omit to use the midpoint of the input annotation.
```

![example](test/example.png)

---
# TODO
- Implement working with compressed files.
- Implement grouping by chromosome.
