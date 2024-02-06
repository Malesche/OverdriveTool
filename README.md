Download and combine OverDrive.com audiobooks into a single m4b file without transcoding.

Useage:

```console
OverdriveDownloader "path\to\odmfile.odm"
```

OverdriveTool will acquire a license and save it to the ODM file for future use. Then it downloads all mp3 parts to the odm file's directory (or loads the mp3s if they've already downloaded). It then merges all mp3 parts into a single m4b file, complete with metadata tags and chapter markers.

based on [https://github.com/Mbucari/OverdriveDownloader](https://github.com/Mbucari/OverdriveDownloader)

### todo

- retry download attemps or cancel
- download files to folder or name parts (avoid mp3 reuse)
- improve final file name
- split main task into sub functions
- rename solution, project and namespace
- debug possible m4b file length issue (vs cumulative mp3 files)
