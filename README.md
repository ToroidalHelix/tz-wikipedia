# tz-wikipedia

## Script usage:
```
./create_tz_wiki_pages [TZ_VERSION]
```
e.g.
```
./create_tz_wiki_pages 2025a
```
If tz version is not provided as an argument, the script will pull the latest development files (code & data) from the main tz git repository.
<br>The script will intentionally abort if you try and run it as root on a Linux server.  But you would not try that anyway.

## Working directory for temporary files:
`/tmp/tz`

## Output files created by the script:
```
./output/wikipedia_replacement_List_of_tz_database_time_zones.txt
./output/wikipedia_replacement_TZ_comments.txt
./output/wikipedia_replacement_TZ_coordinates.txt
./output/wikipedia_replacement_TZ_country_code.txt
./output/wikipedia_replacement_TZ_rulefile.txt
./output/wikipedia_replacement_TZ_utc_dst_offset.txt
./output/wikipedia_replacement_TZ_utc_offset.txt
```

