# alarm

linux command-line alarm clock

# usage

If you want your computer to wake up at 9:00 to play a song, do:

```
alarm 9:00
```

If you don't have a song "configured" one will be downloaded from the internet.

You could also do:

```
$ youtube-dl https://www.youtube.com/watch?v=1cAdJ3Ns1gE -o weatherchannel.mp4
$ at 9:00 'mplayer -vo none weatherchannel.mp4'
```

# install

With [bpkg](https://github.com/bpkg/bpkg) do:

```
bpkg install substack/alarm
```

Or, copy `at` and `alarm` into your $PATH somewhere.

Modify `alarm` to play an audio file of your chosing.

Also install youtube-dl:

```
sudo apt-get install youtube-dl
```

# license

MIT
