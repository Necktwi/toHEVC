toHEVC
------

Converts all the files with the given extension in the present working directory to HEVC format
```
toHEVC mkv
```

To convert a single file, rename the file extension to a distinct name and run toHEVC with that
extension!
```
mv Movie.mkv Movie.my.mkv
toHEVC my.mkv
```

### Dependencies

##### FFMPEG
https://trac.ffmpeg.org/wiki/CompilationGuide/

#### trash-cli

##### Ubuntu
sudo apt install trash-cli

##### macOS
brew install trash

