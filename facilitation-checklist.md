## Pre-facilitation Checklist

<img src="https://i.imgur.com/ymFNZU2.png" width="250">

- [ ] Put charged AA batteries into Sony UTX-B2 Microphone Transmitter.

***

<img src="https://i.imgur.com/VyD6GXK.png" width="250">

- [ ] Put charged AA batteries into Sony URX-P2 Microphone Receiver.

***

- [ ] Plug M-Audio Fast Track Pro USB cable into your MacBook ([drivers](http://avid.force.com/pkb/articles/en_US/Download/Fast-Track-Pro-Drivers)).
- [ ] Open QuickTime Player and start a new screen recording (CTRL+CMD+N).

***

<img src="https://i.imgur.com/x2fa4K6.png" width="250">

- [ ] Click the triangle and select "M-Audio Fast Track Pro USB".

***

<img src="https://i.imgur.com/J52oEvU.png" width="500">

- [ ] Check your audio levels. Speak at the volume you will when presenting: "Testing Testing 1 2 3." Adjust audio so that it is loud enough, but not clipping.

***

- [ ] When ready, click "record".

## Post-facilitation Checklist

- [ ] Save your screencast to the Desktop.
- [ ] Start the conversion process using `vimeo_sync`:

If you don't have this tool already, follow the instructions, [here](https://github.com/launchacademy/vimeo_sync).

```no-highlight
$ cd ~/Desktop
$ ./~/vimeo_sync/vimeo_converter Video.mov
```

- [ ] Remove AA batteries from Sony UTX-B2 Microphone Transmitter.
- [ ] Remove AA batteries into Sony URX-P2 Microphone Receiver.
- [ ] Put batteries into Charger.
- [ ] Upload your video to Vimeo using `vimeo_sync`.

```no-highlight
$ cd ~/Desktop
$ python ~/vimeo_sync/vimeo_sync.py Video.mp4 "Video Title"
```

### Troubleshooting

- [ ] Verify that all devices are powered on.
- [ ] Unplug and reinsert the M-Audio USB cable.
- [ ] Ask Richard.
